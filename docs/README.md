# Morph UI docs

## English

This folder contains bilingual engineering documentation for Morph UI.

Recommended reading order:

1. [architecture.md](./architecture.md)
2. [extension-runtime.md](./extension-runtime.md)
3. [transform-plan-spec.md](./transform-plan-spec.md)
4. [cache-and-fingerprint.md](./cache-and-fingerprint.md)
5. [privacy-and-data-flow.md](./privacy-and-data-flow.md)
6. [provider-capabilities.md](./provider-capabilities.md)
7. [auth-and-session-flow.md](./auth-and-session-flow.md)
8. [permissions-and-security.md](./permissions-and-security.md)
9. [preferences-and-profiles.md](./preferences-and-profiles.md)
10. [ai-provider-integration.md](./ai-provider-integration.md)
11. [api-contracts.md](./api-contracts.md)
12. [backend-route-reference.md](./backend-route-reference.md)
13. [data-model.md](./data-model.md)
14. [extension-messaging-reference.md](./extension-messaging-reference.md)
15. [storage-and-sync-layout.md](./storage-and-sync-layout.md)
16. [user-workflow-guide.md](./user-workflow-guide.md)
17. [environment-variables.md](./environment-variables.md)
18. [diagnostics-and-observability.md](./diagnostics-and-observability.md)
19. [local-development.md](./local-development.md)
20. [testing-matrix.md](./testing-matrix.md)
21. [troubleshooting.md](./troubleshooting.md)
22. [deployment-and-operations.md](./deployment-and-operations.md)
23. [operations-runbook.md](./operations-runbook.md)
24. [release-checklist.md](./release-checklist.md)
25. [release-playbook.md](./release-playbook.md)
26. [testing-fixtures.md](./testing-fixtures.md)

Document index:

- [architecture.md](./architecture.md)
  overall monorepo structure, responsibilities, runtime flow
- [extension-runtime.md](./extension-runtime.md)
  MV3 extension surfaces, messaging, permissions, apply lifecycle
- [transform-plan-spec.md](./transform-plan-spec.md)
  AI output contract and compilation rules
- [auth-and-session-flow.md](./auth-and-session-flow.md)
  product auth, exchange-code flow, and server session boundaries
- [permissions-and-security.md](./permissions-and-security.md)
  extension permissions and review-oriented security posture
- [preferences-and-profiles.md](./preferences-and-profiles.md)
  profile structure and seeded preferences
- [ai-provider-integration.md](./ai-provider-integration.md)
  provider adapter boundaries and screenshot usage rules
- [cache-and-fingerprint.md](./cache-and-fingerprint.md)
  local and remote cache behavior plus fingerprint policy
- [privacy-and-data-flow.md](./privacy-and-data-flow.md)
  local versus remote boundaries and sensitive-site policy
- [provider-capabilities.md](./provider-capabilities.md)
  honest capability matrix for OpenAI and Gemini
- [api-contracts.md](./api-contracts.md)
  implemented server endpoints and request/response contracts
- [backend-route-reference.md](./backend-route-reference.md)
  operational route map for server modules
- [data-model.md](./data-model.md)
  Postgres tables, indexes, and seeded records
- [extension-messaging-reference.md](./extension-messaging-reference.md)
  typed message names used across extension surfaces
- [storage-and-sync-layout.md](./storage-and-sync-layout.md)
  browser and remote storage split
- [user-workflow-guide.md](./user-workflow-guide.md)
  end-user flow from onboarding to revisit cache hits
- [environment-variables.md](./environment-variables.md)
  config reference and missing-value failure modes
- [diagnostics-and-observability.md](./diagnostics-and-observability.md)
  logs, health, diagnostics, and evidence inspection guide
- [local-development.md](./local-development.md)
  setup and run commands
- [testing-matrix.md](./testing-matrix.md)
  requirement-to-verification coverage map
- [troubleshooting.md](./troubleshooting.md)
  common failure modes and first checks
- [deployment-and-operations.md](./deployment-and-operations.md)
  operational boundaries and deployment split
- [operations-runbook.md](./operations-runbook.md)
  first-response procedures for incidents and degradations
- [release-checklist.md](./release-checklist.md)
  release-gate checklist for shipping
- [release-playbook.md](./release-playbook.md)
  ordered ship and rollback sequence
- [testing-fixtures.md](./testing-fixtures.md)
  fixture pages and test strategy
- [../tests/README.md](../tests/README.md)
  root-level smoke notes and manual evidence
- [../CONTRIBUTING.md](../CONTRIBUTING.md)
  contributor workflow and verification expectations

## 한국어

이 폴더에는 Morph UI의 bilingual 엔지니어링 문서가 들어 있습니다.

추천 읽기 순서:

1. [architecture.md](./architecture.md)
2. [extension-runtime.md](./extension-runtime.md)
3. [transform-plan-spec.md](./transform-plan-spec.md)
4. [cache-and-fingerprint.md](./cache-and-fingerprint.md)
5. [privacy-and-data-flow.md](./privacy-and-data-flow.md)
6. [provider-capabilities.md](./provider-capabilities.md)
7. [auth-and-session-flow.md](./auth-and-session-flow.md)
8. [permissions-and-security.md](./permissions-and-security.md)
9. [preferences-and-profiles.md](./preferences-and-profiles.md)
10. [ai-provider-integration.md](./ai-provider-integration.md)
11. [api-contracts.md](./api-contracts.md)
12. [backend-route-reference.md](./backend-route-reference.md)
13. [data-model.md](./data-model.md)
14. [extension-messaging-reference.md](./extension-messaging-reference.md)
15. [storage-and-sync-layout.md](./storage-and-sync-layout.md)
16. [user-workflow-guide.md](./user-workflow-guide.md)
17. [environment-variables.md](./environment-variables.md)
18. [diagnostics-and-observability.md](./diagnostics-and-observability.md)
19. [local-development.md](./local-development.md)
20. [testing-matrix.md](./testing-matrix.md)
21. [troubleshooting.md](./troubleshooting.md)
22. [deployment-and-operations.md](./deployment-and-operations.md)
23. [operations-runbook.md](./operations-runbook.md)
24. [release-checklist.md](./release-checklist.md)
25. [release-playbook.md](./release-playbook.md)
26. [testing-fixtures.md](./testing-fixtures.md)

문서 인덱스:

- [architecture.md](./architecture.md)
  모노레포 구조, 책임 분리, 전체 런타임 흐름
- [extension-runtime.md](./extension-runtime.md)
  MV3 확장 surface, 메시징, 권한, 적용 수명주기
- [transform-plan-spec.md](./transform-plan-spec.md)
  AI 출력 계약과 컴파일 규칙
- [auth-and-session-flow.md](./auth-and-session-flow.md)
  제품 인증, exchange-code 흐름, 서버 세션 경계
- [permissions-and-security.md](./permissions-and-security.md)
  확장 권한과 심사 관점의 보안 자세
- [preferences-and-profiles.md](./preferences-and-profiles.md)
  프로필 구조와 시드 preference
- [ai-provider-integration.md](./ai-provider-integration.md)
  provider adapter 경계와 screenshot 사용 규칙
- [cache-and-fingerprint.md](./cache-and-fingerprint.md)
  로컬/원격 캐시 동작과 fingerprint 정책
- [privacy-and-data-flow.md](./privacy-and-data-flow.md)
  로컬/원격 경계와 민감 사이트 정책
- [provider-capabilities.md](./provider-capabilities.md)
  OpenAI/Gemini capability를 정직하게 설명한 문서
- [api-contracts.md](./api-contracts.md)
  실제 구현된 서버 엔드포인트와 요청/응답 계약
- [backend-route-reference.md](./backend-route-reference.md)
  서버 모듈 관점의 route 지도
- [data-model.md](./data-model.md)
  Postgres 테이블, 인덱스, 시드 데이터
- [extension-messaging-reference.md](./extension-messaging-reference.md)
  확장 surface 간 타입 메시지 이름 정리
- [storage-and-sync-layout.md](./storage-and-sync-layout.md)
  브라우저/원격 저장소 분리 전략
- [user-workflow-guide.md](./user-workflow-guide.md)
  온보딩부터 재방문 cache hit까지의 사용자 흐름
- [environment-variables.md](./environment-variables.md)
  설정값 기준과 누락 시 실패 형태
- [diagnostics-and-observability.md](./diagnostics-and-observability.md)
  로그, health, diagnostics, evidence 해석 가이드
- [local-development.md](./local-development.md)
  설치와 실행 방법
- [testing-matrix.md](./testing-matrix.md)
  요구사항과 검증 계층의 대응 표
- [troubleshooting.md](./troubleshooting.md)
  자주 만나는 문제와 1차 점검 포인트
- [deployment-and-operations.md](./deployment-and-operations.md)
  운영 경계와 배포 분리 전략
- [operations-runbook.md](./operations-runbook.md)
  장애/성능저하 시 첫 대응 절차
- [release-checklist.md](./release-checklist.md)
  릴리스 전 점검 체크리스트
- [release-playbook.md](./release-playbook.md)
  실제 배포 및 롤백 순서 안내
- [testing-fixtures.md](./testing-fixtures.md)
  fixture 페이지와 테스트 전략
- [../tests/README.md](../tests/README.md)
  루트 스모크 노트와 수동 검증 증거
- [../CONTRIBUTING.md](../CONTRIBUTING.md)
  기여 흐름과 검증 기대사항
