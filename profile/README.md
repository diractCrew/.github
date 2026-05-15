<div align="center">

# <img src="https://github.com/user-attachments/assets/bd715fbd-8be3-466c-9a74-e6f73b5fe39a" alt="DirAct" height="40"/>

<!-- TODO: 한 줄 소개를 여기에 채워주세요 -->
DirAct는 연습 영상 리뷰와 피드백 공유 과정에서 발생하는 커뮤니케이션 병목과 비효율을 해결하기 위해,

실제 댄스팀 사용자 리서치와 반복적인 사용성 테스트를 거쳐 설계 되었습니다.

그리고 DirAct를 시작점으로 댄스팀의 전체 워크플로우를 통합 지원하는 플랫폼으로 확장하고자 합니다.

<table align="center"><tr>
<td valign="middle">
  <a href="https://apps.apple.com/kr/app/diract/id6754757174">
    <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/75518683/268173445-322afec8-38fa-46ba-bbe0-3fffd0c93f5b.png" alt="App Store에서 다운로드 하기" height="60"/>
  </a>
</td>
<td valign="middle">
  <a href="https://play.google.com/store/apps/details?id=com.baek.diract">
    <img src="https://play.google.com/intl/ko_kr/badges/static/images/badges/ko_badge_web_generic.png" alt="Google Play에서 다운로드 하기" height="50"/>
  </a>
</td>
</tr></table>

</div>

---

## ✨ Features

<!-- TODO: 핵심 기능 3~5개를 한 줄씩 나열 -->
- Feature 1: 댄스팀(댄서)들을 위한 자유로운 파일 설계 (무대, 곡 순서 등)
- Feature 2: 타임스탬프 기반 영상 피드백 시스템 (피드백 제공자, 수용자 UX 설계)
- Feature 3: 영상 위 드로잉 어노테이션 (시각적 설명 수단을 제공)


## 🛠 Tech Stack

| Layer | Stack |
|---|---|
| **App (현재)** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white) |
| **App (레거시)** | ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) |
| **Backend** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) |
| **Collaboration** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) |

---

## 📚 초기 DirAct팀의 여정

[DirAct의 여정을 살펴보세요](https://www.figma.com/design/cnhKICzxCT5wdRBHsQ7SDT/DirAct%EC%9D%98-%EC%97%AC%EC%A0%95?node-id=0-1&p=f&t=shxJx6is4XsyJ8gA-0)

---

[DirAct의 여정을 살펴보세요](https://www.figma.com/design/cnhKICzxCT5wdRBHsQ7SDT/DirAct%EC%9D%98-%EC%97%AC%EC%A0%95?node-id=0-1&p=f&t=shxJx6is4XsyJ8gA-0)

## 👥 Team

### 🍎 Original Team — Native (2024 – 2025)
DirAct의 시작을 함께한 아카데미 팀원들. iOS / Android 네이티브 버전을 만들어주신 분들.

<!-- TODO: 팀원 이름 / GitHub 핸들 / 역할 채우기 -->
| Role | Name | GitHub |
|---|---|---|
| iOS | 김진혁 | [벨코](https://github.com/Velko716) |
| iOS | 조재훈 | [카단](https://github.com/jHoon99) |
| iOS | 김준구 | [파이디온](https://github.com/devPaidion) |
| Android | 백서영 | [백서영](https://github.com/BaekCCI) |
| Android | 김병관 | [백서영](https://github.com/BaekCCI) |
| Design | 김경주 | [제이콥](https://github.com/Gimgang00) |
| Design | 이주은 | [줄리앤](https://github.com/Julianne0101) |
| PM | 배연경 | [리비](https://github.com/ykbeeee) |


### 🚀 Flutter Migration — 2026 ~
크로스플랫폼 단일 코드베이스로의 전환을 진행 중.

| Role | Name | GitHub |
|---|---|---|
| Mobile / Maintainer | 조재훈 | [@jHoon99](https://github.com/jHoon99) |

### 🚀 Backend — 2026 ~
->

| Role | Name | GitHub |
|---|---|---|
| ? / ? | 강현호 |  |

---

## 📌 Our Repositories

| Repository | Status | Description |
|---|---|---|
| [`diract_flutter`](https://github.com/diractCrew/diract_flutter) | 🟢 Active | 현재 메인 — Flutter 마이그레이션 |
| [`diract_backend`](https://github.com/diractCrew/diract_backend) | 🟢 Active | API / 서버 |
| [`diract_iOS`](https://github.com/diractCrew/diract_iOS) | 🟡 Legacy | 초기 iOS 네이티브 (Swift) |
| [`diract_android`](https://github.com/diractCrew/diract_android) | 🟡 Legacy | 초기 Android 네이티브 (Kotlin) |

> 🟢 Active · 🟡 Legacy(유지보수 종료) · 🔴 Archived

---

## 📂 Repository Rule

이 Organization에서 관리되는 레포지토리는 DirAct 운영·개발 산출물입니다. 외부 컨트리뷰션 정책은 아래를 따릅니다.

### 👀 Visibility Policy
- 운영 중인 프로덕션 코드(`diract_flutter`, `diract_backend`)는 **Private**을 기본으로 합니다.
- 데모 / 학습 / 템플릿 성격의 레포는 **Public**으로 열어둘 수 있습니다.
- 가시성 변경은 Owner 협의 후 진행합니다.

### 🌿 Branch Strategy
- `main` — 배포 가능한 안정 브랜치 (보호됨)
- `develop` — 통합 개발 브랜치
- `feat/<scope>` · `fix/<scope>` · `chore/<scope>` — 작업 단위 브랜치
- 머지는 **Squash & Merge**를 기본으로 합니다.

### 🤝 Contribution
- 외부 기여는 **Fork → PR**로 받습니다.
- PR 본문에는 변경 의도 / 영향 범위 / 테스트 방법을 적어주세요.
- 코드 스타일은 각 레포의 lint 설정을 따릅니다 (`flutter analyze`, `ktlint`, `spotless` 등).

### ⚠️ Caution
- Public 레포에 올라간 자산(이미지·문구·디자인)의 권리는 DirAct에 있습니다.
- 사용자 데이터·API 키·서명 정보 등을 커밋에 포함하지 않도록 주의해주세요.

---

<div align="center">

**DirAct** © 2024 – 2026 · diractCrew
<br/>

</div>
