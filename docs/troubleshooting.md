# Troubleshooting

## English

### `pnpm local:setup` fails

Check:

- `pnpm` is installed
- Docker is running
- port `54329` is available
- expected env values match [environment-variables.md](./environment-variables.md)

### Server fails to start

Check:

- `.env` exists
- `SESSION_TOKEN_SECRET` is set
- `DATABASE_URL` is reachable

### Google sign-in does not work

Check:

- `GOOGLE_CLIENT_ID`
- `GOOGLE_CLIENT_SECRET`
- `GOOGLE_OAUTH_REDIRECT_URI`
- Chrome extension redirect flow configuration

### Provider planning fails

Check:

- selected provider has a valid API key in `.env`
- privacy mode is not `strict-local`
- current site is enabled
- capability and debug clues in [diagnostics-and-observability.md](./diagnostics-and-observability.md)

### Extension does not affect the page

Check:

- host permission was granted
- content script is registered for the origin
- selected site is enabled
- cache status and diagnostics in the side panel
- outage and degraded-mode handling in [operations-runbook.md](./operations-runbook.md)

## 한국어

### `pnpm local:setup` 실패

다음을 확인:

- `pnpm` 설치 여부
- Docker 실행 여부
- `54329` 포트 사용 가능 여부
- 필요한 환경변수가 [environment-variables.md](./environment-variables.md) 와 맞는지

### 서버가 시작되지 않음

다음을 확인:

- `.env` 존재 여부
- `SESSION_TOKEN_SECRET` 설정 여부
- `DATABASE_URL` 연결 가능 여부

### Google 로그인 실패

다음을 확인:

- `GOOGLE_CLIENT_ID`
- `GOOGLE_CLIENT_SECRET`
- `GOOGLE_OAUTH_REDIRECT_URI`
- Chrome extension redirect flow 설정

### Provider planning 실패

다음을 확인:

- 선택한 provider의 API 키가 `.env`에 존재하는지
- privacy mode가 `strict-local`이 아닌지
- 현재 사이트가 enable 상태인지
- capability와 디버그 단서는 [diagnostics-and-observability.md](./diagnostics-and-observability.md) 참고

### 확장이 페이지에 영향을 주지 않음

다음을 확인:

- host permission이 부여되었는지
- content script가 해당 origin에 등록되었는지
- 사이트가 enable 상태인지
- 사이드패널 cache status와 diagnostics
- 장애/저하 대응은 [operations-runbook.md](./operations-runbook.md) 참고
