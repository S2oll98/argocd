<!-- 표준 MR 템플릿 (전 repo 공통). 제목 = Conventional Commits: `<type>(<scope?>): <제목>` (예: feat: 재시도 정책 / fix(serving): 응답 수정). type ∈ feat·fix·docs·style·refactor·perf·test·build·ci·chore·revert. squash merge 강제 → 제목이 곧 커밋. -->

## 관련 work item (Plane)
[ISSUE-KEY]
<!-- 예: [DATA-142]. 대괄호 유지 → Plane 링크 + 상태 자동연동. 제목/설명 어디든 인식. 모든 작업은 이슈 기반(예외 없음). -->

## 변경 요약


## 종류
- [ ] 기능 (feat)
- [ ] 버그 수정 (fix)
- [ ] 인프라 / 설정 (build · ci · chore)
- [ ] 문서 (docs)
- [ ] 리팩터 / 성능 / 테스트 (refactor · perf · test)

## 체크리스트
- [ ] 로컬 검증 통과 (`make verify` 또는 프로젝트 테스트)
- [ ] CI 게이트 통과 (commit-lint · secret-detection · SAST · 해당 시 iac-scan / dependency-scan)
- [ ] 제목이 Conventional Commits 형식
- [ ] Plane work item `[<KEY>]` 연결 (필수)
- [ ] 버전 핀 유지 (`:latest` · `@main` 등 부동 참조 없음)
- [ ] 배포 영향 시 ArgoCD `envs/<env>/...` bump 연계 확인

/assign me
