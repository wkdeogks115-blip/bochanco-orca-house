# NEXT ACTION — 한 번에 한 Gate

## Primary Governance Gate
SOURCE_MAP R1 reviewer packet을 **실제로 독립적인 Provider/Reviewer**에게 전달하고 결과를 회수한다.
- 같은 Builder/Manager Provider self-review는 independent PASS로 인정하지 않는다.
- packet self-check 후에만 review 진행.
- 반환물: `CHALLENGER_REVIEW.md` + schema-conformant `agent_result_receipt.json`.
- 결과 반환 전 SOURCE_MAP Candidate 패치/Freeze 금지.

## Parallel-safe Runtime Gate
외부 리뷰 대기 중에는 실제 사용자 ORCA live terminal에서 R1 read-only probe 1회만 병렬 허용.

Windows:
`orca orchestration run-current --json`

PASS:
- 정상 JSON 반환
- `run: null`도 PASS

FAIL/HOLD:
- `stable_pane_required`
- runtime unreachable
- terminal identity resolution failure
- orchestration capability unavailable

R1에서는 `run-create`, `run-use`, `task-create`, `dispatch`, `worker-start`, `reset` 실행 금지.

## 지금의 우선순위
1. 독립 Reviewer가 가능하면 SOURCE_MAP NEXT-001.
2. 독립 Reviewer가 당장 불가능하고 실제 ORCA terminal 접근이 가능하면 Runtime R1만 수행.
3. 둘 다 불가능하면 새 패치를 만들지 않고 BLOCKED를 보존.
