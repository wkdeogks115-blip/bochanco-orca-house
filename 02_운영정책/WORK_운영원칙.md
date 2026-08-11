# Work 운영 원칙

## Work의 역할
Work는 장기 Manager Runtime이다. 대화 자체를 영구 SSOT로 믿지 않고 GitHub의 Canonical State와 Evidence를 읽어 판단한다.

## 매 세션 부팅
1. `AI_START_HERE.md`
2. `01_현재상태/CANONICAL_STATE.json`
3. `01_현재상태/미검증_목록.md`
4. `03_다음작업/NEXT_ACTION.md`
5. 필요한 근거만 JIT

## Response Pack
과거 Response Pack은 복구/Checkpoint 용도다. 단순 답변마다 새 Pack을 만들지 않는다. Material state change가 있을 때만 갱신한다.

## 끝없는 패치 방지
현재 Gate를 닫기 위한 Material Delta만 허용하고, 새 아이디어/미관/미래 확장만으로 재패치하지 않는다.
