<!-- ===================== HEADER ===================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3FB950,100:9BE15D&height=200&section=header&text=LimSGum&fontSize=64&fontColor=ffffff&fontAlignY=36&desc=Build%20tools%20that%20make%20everyday%20work%20easier&descSize=18&descAlignY=58&animation=fadeIn" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=3FB950&center=true&vCenter=true&width=600&lines=Hi+there%2C+I'm+LimSGum+%F0%9F%91%8B;I+automate+the+boring+stuff;C%23+%C2%B7+React+%C2%B7+Node.js+%C2%B7+Kotlin" alt="Typing SVG" />
</p>

<!-- ===================== ABOUT ===================== -->
## 🙋‍♂️ About Me

- 🧩 하나의 도구는 **하나의 일만 잘하도록** 만듭니다. 그래서 기능마다 저장소를 따로 두고, 각 저장소는 무엇을 하는지 한눈에 보이게 정리해 둡니다.
- 🛠️ 반복되는 일을 **자동화하는 도구**를 만드는 걸 좋아합니다.
- 📈 요즘은 **경제·자산 데이터**를 모으고 AI로 요약·분석하는 프로젝트에 빠져 있습니다.
- 📱 데스크톱, 웹, 안드로이드까지 필요한 곳이면 어디든 만들어 봅니다.
- 🤖 Claude Code와 함께 아이디어를 빠르게 실제 서비스로 옮기고 있습니다.

<!-- ===================== TECH STACK ===================== -->
## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,js,react,nodejs,express,materialui,vue&perline=8" /><br/>
  <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,python,html,css,docker,aws,azure&perline=8" /><br/>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode,visualstudio&perline=8" />
</p>

<!-- ===================== PROJECTS ===================== -->
## 📂 Projects

> 🔒 표시가 있는 저장소는 비공개입니다. 코드는 공개하지 않고 소개만 남겨 둡니다.

<!-- PROJECT-TABLE:START (새 프로젝트 행은 표 마지막 행 아래, END 위에 추가. 규칙은 CLAUDE.md 참고) -->
| 프로젝트 | 한 줄 소개 | 기술 | 상태 |
|:--|:--|:--|:--:|
| 📈 [**stock_investigate**](https://github.com/LimSGum/stock_investigate) 🔒 | 종목 한 줄 요청 → 리서치·원고·4중 리뷰 → 검증된 주식 리포트(HTML) 자동 생성 | `Python` `Node.js` `Claude Code` `yfinance` | 🟢 개발 중 |
| 📚 [**book-librarian**](https://github.com/LimSGum/book-librarian) 🔒 | 읽은 책을 한 권씩 채워 가는 개인 서재, 책별 학습 노트 저장소를 주제별로 연결 | `Markdown` `학습 노트` | 🟢 진행 중 |
| 🖼️ [**img_to_md**](https://github.com/LimSGum/img_to_md) 🔒 | 사진·스캔 이미지 → OCR로 글자 추출 → 마크다운 문서로 변환 | `Python` `Tesseract` `OCR` | 🟢 개발 중 |
| 🤖 [**claudecord-bot**](https://github.com/LimSGum/claudecord-bot) 🔒 | 모바일 Discord 메시지 한 통으로 내 PC의 Claude Code에 작업을 시키는 봇 | `Python` `Discord` `Claude Code` | ✅ 운영 중 |
| 💰 [**OurAsset**](https://github.com/LimSGum/OurAsset) 🔒 | 흩어진 가족 자산을 한 화면에 모으고 AI로 변화를 추적 | `Excel 파싱` `AI 분석` | 🟢 설계 중 |
| 📰 [**Economy_Search**](https://github.com/LimSGum/Economy_Search) 🔒 | 경제 뉴스 36곳 스크랩 → AI 요약 → 매일 아침 메일 발송 | `React` `Node.js` `Puppeteer` `Docker` | ✅ 운영 중 |
| 🎧 [**system-subtitle**](https://github.com/LimSGum/system-subtitle) 🔒 | 폰에서 나오는 소리를 실시간 번역 자막으로 띄우는 안드로이드 앱 | `Kotlin` `Android` `Azure Speech` | ✅ v1.0.51 |
| 🎵 [**youtube_music_extract**](https://github.com/LimSGum/youtube_music_extract) 🔒 | 영상 속 음악을 골라내 듣기 좋게 정리하는 개인용 도구 | `Audio` `Automation` | 🟢 개발 중 |
| 🗂️ [**portfolio**](https://github.com/LimSGum/portfolio) 🔒 | 경력과 프로젝트를 정리한 개인 포트폴리오 웹사이트 | `HTML` `CSS` `JavaScript` | ✅ 배포 완료 |
<!-- PROJECT-TABLE:END -->

<!-- PROJECT-DETAILS:START (새 프로젝트 상세는 표와 같은 순서로 이 사이에 추가) -->
<details>
<summary><b>📈 stock_investigate</b> 자세히 보기</summary>
<br/>

> 자연어 한 줄이면 토스 스타일 종목 리포트가 나옵니다.

- **원샷 파이프라인**: 계획 → 리서치 → 원고 → 리뷰 → 빌드를 Claude Code 명령 하나로 순서대로 실행
- **4중 리뷰**: 서로 다른 관점의 리뷰어가 원고를 검토하고, 통과해야만 최종 빌드
- **가격 차트 내장**: yfinance 일봉 데이터를 받아 리포트에 차트로 삽입
- **계약 기반 검증**: 필수 항목·섹션 정합성을 스크립트로 검사해 깨진 리포트는 만들어지지 않음

</details>

<details>
<summary><b>📚 book-librarian</b> 자세히 보기</summary>
<br/>

> 읽은 책을 한 권씩 채워 나가는 개인 서재

- **주제별 서재**: 책을 AI 같은 주제별 표로 나눠 한 줄 소개·형태·진행 상태를 정리
- **링크 중심 구조**: 책 내용은 복사하지 않고, 책마다 따로 둔 저장소를 링크로 가리킴
- **책별 학습 노트**: 사진 → 마크다운 전사 → 장별 개인 노트 흐름으로 각 책을 정리
- **쉬운 확장**: 새 책은 맞는 주제 표에 한 줄과 상세 블록만 붙이면 끝

</details>

<details>
<summary><b>🖼️ img_to_md</b> 자세히 보기</summary>
<br/>

> 찍어 둔 사진을 바로 검색되는 문서로

- **OCR 변환**: 이미지 속 한글·영어 글자를 읽어 마크다운(.md)으로 저장
- **폴더 일괄 처리**: 폴더째 넣으면 이미지마다 문서 생성, 원하면 하나로 병합
- **전처리 자동화**: 회전 보정·흑백·대비 조정으로 인식률을 높이고 낮은 신뢰도 글자는 노이즈로 제거
- **원본 링크 포함**: 필요하면 원본 이미지 링크를 문서에 함께 삽입

</details>

<details>
<summary><b>🤖 claudecord-bot</b> 자세히 보기</summary>
<br/>

> PC 앞을 떠나도 멈추지 않는 AI 비서

- **모바일에서 PC 제어**: Discord 메시지로 Claude Code 작업을 지시
- **등록된 사용자만 사용**: 허용한 사용자와 채널에서만 동작
- **작업별 격리 실행**: 작업마다 분리된 폴더에서 실행
- **결과물 자동 전송**: 만들어진 파일을 Discord로 바로 보내줌

</details>

<details>
<summary><b>💰 OurAsset</b> 자세히 보기</summary>
<br/>

> 둘이 하나의 포트폴리오로. 흩어진 자산을 한곳에서 보고, 기록을 쌓아 AI로 분석합니다.

- **통합 자산 현황**: 여러 증권사 계좌를 합산해 종목별 보유량, 손익, 비중을 한눈에 표시
- **기록 축적**: 데이터를 받을 때마다 스냅샷을 저장해 주·월 단위 변화 추적
- **AI 트래킹**: 포트폴리오와 총자산 변화를 AI가 요약
- **기초 지표**: 환율, 금리를 매일 수집해 함께 표시

</details>

<details>
<summary><b>📰 Economy_Search</b> 자세히 보기</summary>
<br/>

> PC도 클라우드도 없이, 집 NAS 하나로 도는 경제 뉴스 비서

- **36개 매체 자동 스크랩**: Puppeteer·Cheerio로 경제 뉴스 수집
- **매체별 AI 요약**: Claude Code CLI로 매체마다 따로 핵심만 요약
- **매일 08:00 메일 발송**: NAS 작업 스케줄러 + Docker 컨테이너에서 완전 자동 실행
- **웹 대시보드**: React + MUI + Recharts로 조사 결과 확인

</details>

<details>
<summary><b>🎧 system-subtitle</b> 자세히 보기</summary>
<br/>

> 유튜브, 게임, 영상 어디서든 실시간 번역 자막

- **시스템 오디오 캡처**: Android AudioPlaybackCapture API로 재생 중인 소리를 그대로 캡처
- **스트리밍 인식 + 번역**: Azure Speech로 영어·일본어·중국어를 한국어로 실시간 번역
- **두 단계 자막**: 말하는 중에는 흐린 임시 자막, 문장이 끝나면 또렷하게 확정
- **오버레이 표시**: 다른 앱 위에 자막을 띄우고 글꼴 크기·투명도 조절 가능

</details>

<details>
<summary><b>🎵 youtube_music_extract</b> 자세히 보기</summary>
<br/>

> 좋아하는 음악을 내 방식대로 모아 듣기 위한 작은 도구

- **음악 추출**: 영상에서 음악 부분만 골라냄
- **정리 자동화**: 반복되는 손작업을 줄여 한 번에 처리
- **개인용 라이브러리**: 모은 음악을 듣기 편한 형태로 보관

</details>

<details>
<summary><b>🗂️ portfolio</b> 자세히 보기</summary>
<br/>

> 지금까지의 경력과 프로젝트를 정리한 웹 포트폴리오

- **About / Skills / Projects** 섹션으로 구성된 단일 페이지 사이트
- 프로젝트 시연 영상과 사용 기술을 함께 정리
- 개인 서버에 직접 배포

</details>
<!-- PROJECT-DETAILS:END -->

<!-- ===================== HANDS-FREE ===================== -->
## 🎙️ Hands-free

> 📱 프로젝트 이야기를 핸즈프리로 나누고 싶다면, 폰에서 **Claude 앱 → Projects → 이 저장소** 를 열고 **핸즈프리(음성) 모드**를 켜 보세요. 말로 편하게 대화할 수 있어요 🎧

<!-- ===================== ACTIVITY ===================== -->
## 📊 Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LimSGum&locale=ko&hide_border=true&background=0D1117&ring=3FB950&fire=3FB950&currStreakLabel=3FB950&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E&stroke=30363D" alt="GitHub Streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LimSGum/LimSGum/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LimSGum/LimSGum/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/LimSGum/LimSGum/output/github-snake.svg" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LimSGum/LimSGum/output/pacman-contribution-graph-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LimSGum/LimSGum/output/pacman-contribution-graph.svg" />
    <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/LimSGum/LimSGum/output/pacman-contribution-graph.svg" />
  </picture>
</p>

<!-- ===================== FOOTER ===================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9BE15D,100:3FB950&height=120&section=footer" width="100%" />
