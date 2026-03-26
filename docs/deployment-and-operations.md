# Deployment and operations

## English

This repository is optimized for local development first, but the operational boundaries are already visible.

### Backend runtime requirements

- Postgres
- server-side provider credentials
- Google OAuth client configuration if product sign-in is enabled

### Operational concerns

- session token secret rotation
- provider key management
- database backup policy
- remote cache retention policy
- feedback and transform run log growth

### Recommended deployment split

- extension bundle served only through Chrome load/unpacked or future release packaging
- server deployed separately with environment-managed secrets
- web app deployed separately or together with the backend origin strategy

See also:

- [environment-variables.md](./environment-variables.md)
- [diagnostics-and-observability.md](./diagnostics-and-observability.md)
- [operations-runbook.md](./operations-runbook.md)
- [release-playbook.md](./release-playbook.md)

## 한국어

이 저장소는 로컬 개발을 우선으로 하지만, 운영 경계도 이미 드러나 있습니다.

### 백엔드 런타임 요구사항

- Postgres
- 서버 측 provider credential
- 제품 로그인 사용 시 Google OAuth client 설정

### 운영 관심사

- 세션 토큰 시크릿 교체
- provider 키 관리
- 데이터베이스 백업 정책
- 원격 캐시 보존 정책
- feedback, transform run 로그 증가 관리

### 권장 배포 분리

- 확장 번들은 Chrome 로드/패키징 경로로 관리
- 서버는 환경변수 기반 시크릿과 함께 별도 배포
- 웹앱은 서버와 분리 또는 같은 origin 전략에 맞춰 배포

함께 보면 좋은 문서:

- [environment-variables.md](./environment-variables.md)
- [diagnostics-and-observability.md](./diagnostics-and-observability.md)
- [operations-runbook.md](./operations-runbook.md)
- [release-playbook.md](./release-playbook.md)
