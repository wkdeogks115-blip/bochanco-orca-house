# Decision Log

## D-001 — Work + GitHub 하이브리드
장기 운영은 Chat 단독이 아니라 `GitHub durable state + ChatGPT Work Manager` 구조로 전환한다.

## D-002 — 한국어 운영본부 + 영문 기계키
사람이 보는 구조/문서 제목은 한국어 중심으로 하고, `AI_START_HERE.md`, `CANONICAL_STATE.json`, `NEXT_ACTION.md` 같은 기계 참조 핵심 파일명은 안정적으로 유지한다.

## D-003 — Public-safe control plane
`bochanco-orca-house`는 public이므로 raw private artifacts/credentials를 넣지 않고 pointer 중심으로 운영한다.

## D-004 — Endless patch 방지
각 트랙별 Stop Line을 두고 Gate PASS 이후 Freeze한다. 새 아이디어만으로 재오픈하지 않는다.
