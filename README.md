<img src="./assets/banner.svg" alt="성석민 — AI 풀스택 개발자" width="100%" />

<p>
  <a href="https://github.com/SungSeokMin/harness-template"><img src="https://img.shields.io/badge/Claude_Code-harness--template-D97757?style=flat-square&logo=claude&logoColor=white" alt="harness-template" /></a>
</p>

프론트엔드 3년 6개월, 백엔드 1년 4개월. **서비스 3개를 혼자 맡아 앱스토어·플레이스토어에 출시**했습니다.
**Claude Code로 계획·리뷰·테스트를 자동화**해, 빠르게 출시하면서도 품질을 지킵니다.

## 🚀 Shipped

<table>
<tr>
<td width="50%" valign="top">

**🍽️ 위브닝** <sub>Full-Stack · 2026.05 ~ 2026.09</sub><br />
낯선 사람들을 저녁 식탁으로 잇는 소셜 다이닝
<br /><a href="https://apps.apple.com/kr/app/id6778737553"><img src="https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=appstore&logoColor=white" alt="App Store" /></a> <a href="https://play.google.com/store/apps/details?id=com.pulsenode.wevening"><img src="https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play" /></a>
</td>
<td width="50%" valign="top">

**📚 아이리딩** <sub>Back-End · Side Project · 운영 중</sub><br />
독서 습관과 진도를 기록하는 독서 관리 서비스
<br /><a href="https://apps.apple.com/kr/app/id6758334207"><img src="https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=appstore&logoColor=white" alt="App Store" /></a> <a href="https://play.google.com/store/apps/details?id=io.ireading.ireading"><img src="https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play" /></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">

**🚚 Push** <sub>Back-End · 2025.05 ~ 2025.09</sub><br />
푸드트럭 사장님과 손님을 잇는 예약·결제 서비스

</td>
<td width="50%" valign="top">

**🖥️ 빌리오** <sub>Front-End · 2021.11 ~ 2025.05</sub><br />
공간 호스트의 예약·정산을 돕는 B2B 서비스

</td>
</tr>
</table>

## 🤖 How I build with AI

AI가 쓴 코드도 사람이 쓴 코드처럼 검증을 거치도록, 에이전트마다 역할을 나누고 사람이 승인하는 지점을 정해 두었습니다.

> `plan` → `critique` → 👤 `approve` → `implement` → `review`

- **계획을 먼저 공격** — 구현 전에 비판 에이전트가 계획의 빈틈을 찾고, 사람이 승인해야 구현이 시작됨
- **훅으로 강제** — 파일을 고치면 관련 테스트가 바로 돌고, 전체 테스트가 통과하기 전엔 작업이 끝나지 않음
- **결과** — 위브닝에서 PR당 변경 파일 **−31%**, 주당 머지 PR **+28%**
- **2모델 교차 검증** — 원인 분석은 Codex, 구현은 Claude Code. 한 모델의 오진이 그대로 코드가 되지 않게
- 이 구성을 누구나 쓸 수 있게 템플릿으로 공개했습니다 → [**harness-template**](https://github.com/SungSeokMin/harness-template)

## 🛠 Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" title="TypeScript" height="48" />
  <img src="https://skillicons.dev/icons?i=nestjs" alt="NestJS" title="NestJS" height="48" />
  <img src="https://skillicons.dev/icons?i=react" alt="React" title="React" height="48" />
  <img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" title="Next.js" height="48" />
  <img src="https://skillicons.dev/icons?i=prisma" alt="Prisma" title="Prisma" height="48" />
  <img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" title="MySQL" height="48" />
  <img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" title="PostgreSQL" height="48" />
  <img src="https://skillicons.dev/icons?i=aws" alt="AWS" title="AWS" height="48" />
  <img src="https://skillicons.dev/icons?i=docker" alt="Docker" title="Docker" height="48" />
  <img src="./assets/claude.svg" alt="Claude" title="Claude Code" height="48" />
</p>

**Domain** · 예약·결제·정산 · Apple/Google 인앱결제 · 실시간 채팅(Socket.IO) · 푸시(FCM) · 동시성 제어

