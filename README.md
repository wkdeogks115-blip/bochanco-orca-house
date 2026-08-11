# 보찬코 올카 운영본부

이 저장소는 ORCA/멀티AI 코워크 프로젝트의 **장기 Manager Control Plane**이다.

사람과 AI 모두 **`AI_START_HERE.md`부터 시작**한다. 과거 채팅 전체나 Archive를 기본 로드하지 않는다.

## 역할
- ChatGPT Work: 정책 / 판단 / Context / Risk / Budget / Evidence Gate
- ORCA: Run / Task / Dispatch / Worktree / Terminal / Worker 실행
- Codex: 코드 / 테스트 / 저장소 변경 전문 실행
- SOURCE_MAP: Source → Claim → Pattern → Decision → Artifact → Eval 계보
- GitHub: durable state / code / evidence pointer

## 핵심 원칙
1. `01_현재상태/CANONICAL_STATE.json`이 이 운영본부의 현재 상태 SSOT다.
2. `03_다음작업/NEXT_ACTION.md`에서 한 번에 한 Gate만 연다.
3. `ACTIVE / CANDIDATE / UNVERIFIED / FROZEN`을 혼합하지 않는다.
4. 외부 evidence 없이 self-review를 independent review로 승격하지 않는다.
5. 새 아이디어만으로 Frozen/Closed 트랙을 재오픈하지 않는다.
6. 이 public 저장소에는 credential, 원본 private artifact, 대용량 ZIP, 사용자 로컬 경로를 넣지 않는다.
