# Release playbook

## English

This playbook is the sequence-oriented companion to the release checklist.

### Suggested release order

1. confirm docs and smoke evidence are current
2. run verification suite
3. build the extension bundle
4. apply server migrations if needed
5. deploy server
6. deploy web app
7. refresh extension package or load-unpacked validation artifact
8. re-run targeted smoke checks

### When schema changes exist

- review migration rollback path
- verify seed expectations
- note whether extension compatibility depends on the new server response shape

### Rollback posture

- server rollback must consider database compatibility
- extension rollback must consider manifest version and packaged artifacts
- docs should record any operator-only workaround used during rollback

## 한국어

이 플레이북은 release checklist를 실제 순서 중심으로 보완하는 문서입니다.

### 권장 릴리스 순서

1. 문서와 smoke evidence가 최신인지 확인
2. 검증 스위트 실행
3. extension 번들 빌드
4. 필요하면 서버 migration 적용
5. 서버 배포
6. 웹앱 배포
7. extension 패키지 또는 load-unpacked 검증 아티팩트 갱신
8. 핵심 smoke 체크 재실행

### 스키마 변경이 있을 때

- migration rollback 경로 검토
- seed 가정 검증
- extension 호환성이 새 서버 응답 형태에 의존하는지 기록

### 롤백 관점

- 서버 롤백은 DB 호환성을 함께 봐야 함
- extension 롤백은 manifest 버전과 패키징 아티팩트를 같이 봐야 함
- 롤백 중 사용한 운영자 전용 우회책은 문서에 남겨야 함
