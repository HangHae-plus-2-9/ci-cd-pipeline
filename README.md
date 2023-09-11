# hhplus

## 1주차

### 과제 목록

- [ ]  phase 별로 빌드 및 배포 정책을 세분화합니다.
  - [ ]  `develop` 브랜치에 작업 후 로컬에서 Docker-compose를 통해 개발합니다.
  - [ ]  `alpha` 브랜치에 푸시하면 `alpha` 환경으로 배포합니다.
  - [ ]  `main` 브랜치에 푸시하면 `prod` 환경으로 배포합니다.

- [ ]  AWS ECR/ECS 를 통해 CI/CD 파이프라인을 구성합니다.
  - [ ] 계정세팅 - 각자 계정 + 팀 계정(팀장님)
  - [ ] 인프라 세팅 - vpc / network / security 등
    - [ ] 헬스체크 / 테스트 코드 작성
  - [ ] Docker, Docker-Compose yaml 작성
  - [ ] github action yaml 작성
    - [ ] `develop`에 `push` 시 자동으로 test를 수행합니다.
    - [ ] `alpha`에 `merge` 시 자동으로 test를 수행하고, 배포합니다.
    - [ ] `main`에 `merge` 시 자동으로 test를 수행하고, 배포합니다.
    - [ ] (optional) 각 phase의 결과를 hook으로 통보합니다.

- [ ]  배포 파이프라인 및 협업 정책을 문서화 합니다.
  - [x]  Organization 계정에 CI/CD 레포지토리를 생성합니다.
  - [ ]  과제목록과 README.md를 지속적으로 고도화합니다.

### 과제 계획

- 9.9(토): OT, 계획
- 9.10(일): 각자 연습 / 학습
- 9.11(월): 온라인 미팅
- 9.12(화):
- 9.13(수):
- 9.14(목):
- 9.15(금): 제출일
