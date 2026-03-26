# Operations runbook

## English

This runbook lists the first operational actions to take for common incidents.

### Provider outage

1. confirm the failing provider and scope
2. keep capability reporting honest
3. disable provider selection in UI if needed
4. continue serving cache hits where possible

### Database recovery

1. stop writes if corruption is suspected
2. inspect latest backup or snapshot
3. restore to a clean environment first
4. verify migrations and seed assumptions before switching traffic

### Secret rotation

1. rotate server secret in secret manager
2. restart affected runtime
3. verify session issuance and provider calls
4. invalidate compromised tokens if needed

### Remote cache disablement

1. disable remote cache writes
2. preserve local cache path
3. confirm extension fallback remains usable

## 한국어

이 런북은 자주 만나는 운영 이슈에 대한 첫 대응 절차를 정리합니다.

### Provider 장애

1. 어떤 provider가 어느 범위에서 실패하는지 확인
2. capability 보고를 실제 상태와 맞춤
3. 필요하면 UI에서 해당 provider 선택을 비활성화
4. 가능하면 cache hit 경로는 계속 제공

### 데이터베이스 복구

1. 손상이 의심되면 쓰기를 중단
2. 최신 백업 또는 스냅샷 확인
3. 먼저 깨끗한 환경에 복구
4. 트래픽 전환 전 migration과 seed 가정 검증

### 시크릿 교체

1. secret manager에서 서버 시크릿 교체
2. 영향받는 런타임 재시작
3. 세션 발급과 provider 호출 확인
4. 필요하면 노출된 토큰 무효화

### 원격 캐시 비활성화

1. 원격 캐시 쓰기를 중단
2. 로컬 캐시 경로는 유지
3. extension fallback이 계속 usable한지 확인
