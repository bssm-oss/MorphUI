# Release checklist

## English

Before shipping a release candidate, confirm:

- `pnpm local:verify` passes
- extension bundle is rebuilt
- docs remain in sync with implemented APIs and runtime behavior
- provider capability copy still reflects real support
- privacy disclosures still match actual data flow
- smoke checklist under `tests/smoke/` is reviewed
- latest local smoke note exists or is intentionally updated
- release sequence is checked against [release-playbook.md](./release-playbook.md)
- contributor expectations remain aligned with [../CONTRIBUTING.md](../CONTRIBUTING.md)

## 한국어

릴리스 후보를 배포하기 전에 다음을 확인합니다.

- `pnpm local:verify` 통과
- extension bundle 재빌드 완료
- 문서가 실제 API와 런타임 동작과 동기화되어 있는지
- provider capability 설명이 실제 지원 범위와 일치하는지
- privacy 안내가 실제 데이터 흐름과 일치하는지
- `tests/smoke/`의 체크리스트를 검토했는지
- 최신 로컬 smoke note가 존재하거나 의도적으로 갱신되었는지
- 릴리스 순서를 [release-playbook.md](./release-playbook.md) 와 대조했는지
- 기여 규칙이 [../CONTRIBUTING.md](../CONTRIBUTING.md) 와 맞는지
