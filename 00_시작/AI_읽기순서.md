# AI 읽기 순서

모든 AI는 전체 저장소를 처음부터 읽지 않는다.

기본:
`AI_START_HERE.md → CANONICAL_STATE.json → 미검증_목록.md → NEXT_ACTION.md`

그 다음 현재 작업에 필요한 트랙/근거만 읽는다.

현재 사실이 시간에 따라 바뀔 수 있는 GitHub/Runtime 정보라면 live source를 재확인하고 snapshot을 자동 승격하지 않는다.
