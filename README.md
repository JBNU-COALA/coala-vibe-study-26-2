# COALA 바이브코딩 스터디 2026-2

코딩 에이전트와 함께 아이디어를 실제 서비스로 만들고, GitHub 공유부터 Docker와 CI/CD까지 경험하는 7주 스터디입니다.

## 목표

- 각자 하나의 웹 또는 모바일 프로젝트를 완성합니다.
- GPT, Claude 등의 코딩 에이전트를 프로젝트 전 과정에 활용합니다.
- 아이디어를 빠르게 구현하고, 공유·배포·운영하는 기본 흐름을 익힙니다.
- 결과뿐 아니라 사용한 프롬프트, 에이전트 지침, 시행착오도 함께 기록합니다.

## 참여자

| GitHub 계정 | 개인 폴더 | 저장소 권한 |
| --- | --- | --- |
| [nguyenthingocduyen0405](https://github.com/nguyenthingocduyen0405) | [`members/nguyenthingocduyen0405`](members/nguyenthingocduyen0405/) | 초대 발송 |
| [jhhj5044-cloud](https://github.com/jhhj5044-cloud) | [`members/jhhj5044-cloud`](members/jhhj5044-cloud/) | 초대 발송 |
| GitHub 사용자명 확인 필요 | [`members/hyeonmin200215`](members/hyeonmin200215/) | 확인 후 초대 예정 |

> 공개 저장소이므로 개인 이메일은 문서에 기록하지 않습니다. GitHub 사용자명이 확인되면 위 표와 폴더 이름을 갱신합니다.

## 일정

| 주차 | 날짜 | 주제 | 문서 |
| --- | --- | --- | --- |
| 1주차 | 2026-09-21 | 아이디어 고민, JCloud 인스턴스, 개발 환경과 Git 기초 | [`docs/1week`](docs/1week/) |
| 2주차 | 2026-09-28 | 아이디어 구체화, 에이전트 하네스와 프로젝트 구조 | [`docs/2week`](docs/2week/) |
| 3주차 | 2026-10-05 | 개별 프로젝트 개발, 프롬프트·하네스·스킬 공유 | [`docs/3week`](docs/3week/) |
| 4주차 | 2026-11-02 | 프로젝트 마무리, 공개와 결과물 공유 | [`docs/4week`](docs/4week/) |
| 5주차 | 2026-11-09 | Docker와 컨테이너 기초 | [`docs/5week`](docs/5week/) |
| 6주차 | 2026-11-16 | GitHub Actions로 CI/CD 구축 | [`docs/6week`](docs/6week/) |
| 7주차 | 2026-11-23 | 프로젝트 발표와 회고 | [`docs/7week`](docs/7week/) |

3주차와 4주차 사이에는 중간고사 기간을 둡니다.

## 저장소 구조

```text
.
├─ docs/                 # 공통 주차별 학습 자료와 과제
│  ├─ 1week/
│  └─ ...
│     └─ 7week/
└─ members/              # 참여자별 프로젝트 기록
   ├─ nguyenthingocduyen0405/
   ├─ jhhj5044-cloud/
   └─ hyeonmin200215/    # GitHub 사용자명 확인 대기
```

## 진행 방법

1. 주차별 안내는 해당 `docs/<주차>/README.md`에서 확인합니다.
2. 각자 작업 과정과 링크는 자신의 `members/<GitHub 사용자명>/README.md`에 누적합니다.
3. 기능 코드는 개인 프로젝트 저장소에서 개발하고, 이 저장소에는 학습 기록과 결과 링크를 공유합니다.
4. 공통 자료를 수정할 때는 브랜치를 만든 뒤 Pull Request로 합칩니다.

권장 브랜치 이름은 `<github-id>/week-<주차>-<주제>`입니다.
