# 근거 계층

이 폴더는 상세 artifact 저장소가 아니라 **AI가 현재 사실을 재검증할 수 있는 pointer index**다.

- `EVIDENCE_INDEX.json`: claim / location / status / truth boundary
- `GITHUB_STATUS.json`: 구현 저장소 PR/CI의 마지막 확인 snapshot

Currentness가 필요한 판단에서는 snapshot만 믿지 말고 연결된 GitHub live state를 다시 조회한다.
