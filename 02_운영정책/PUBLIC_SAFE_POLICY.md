# Public Safe Policy

이 저장소는 public 운영본부다.

금지:
- API key, token, password, cookie, secret
- 사용자 로컬 절대경로
- private artifact 원본 ZIP/로그의 무분별한 업로드
- 실계정 데이터
- 불필요한 개인정보

허용:
- 상태 enum
- 검증된 commit/run pointer
- 공개 가능한 운영정책
- 재현 가능한 테스트 명령
- private 구현 저장소의 최소 식별 포인터

상세 evidence는 권한이 있는 연결 저장소/Artifact에서 JIT로 조회한다.
