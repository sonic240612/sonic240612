# Seongwoo Choi

Computer Engineering · AI-First Development

<sub>Stable Diffusion · AI Agents · LLM</sub>

[sonic-blog ↗](https://sonic240612.github.io/sonic-blog/) · [Featured Projects](#featured-projects) · [Competitions](#competitions)

## AI-First Development

> **이 포트폴리오의 모든 프로젝트는 AI를 활용해 1인 제작했습니다.**

프론트엔드·백엔드·배포까지 LLM과 코딩 에이전트와 함께 개발하고 있습니다. AI를 개발 도구로 쓰는 것뿐 아니라, 제품 안에 AI 기능을 직접 구현하는 것도 관심사입니다 (iF). 관심 분야를 실제 서비스로 만들어보며, 관심을 프로젝트로 꾸준히 이어가고 있습니다.

1인이 기획부터 배포까지 전체를 책임지는 구조에서, **어떤 기술을 조합할지 결정하고 AI가 만든 결과를 검증·마무리하는 것**이 제 주된 역할입니다.

## sonic-blog

제가 만든 프로젝트들을 한 번에 볼 수 있는 블로그입니다.

[프로젝트 둘러보기 ↗](https://sonic240612.github.io/sonic-blog/) · [GitHub](https://github.com/sonic240612/sonic-blog)

| Category | Projects |
| :--- | :--- |
| **Playground** | [open-survivor](https://github.com/sonic240612/open-survivor) · [LADDER](https://github.com/sonic240612/LADDER) · [TikaTuka](https://github.com/sonic240612/TikaTuka) · [iF](https://github.com/sonic240612/iF) · [beatsync](https://github.com/sonic240612/beatsync) · Mars Panic!!! |
| **Tools** | [WhereTo?](https://github.com/sonic240612/whereto) · [PixelCircle](https://github.com/sonic240612/pixel-circle) |
| **Lab** | [Lodex](https://github.com/sonic240612/Lodex) · [hand-in-hand](https://github.com/sonic240612/hand-in-hand) · [pi-telegram](https://github.com/sonic240612/pi-telegram) · [pi-compact-model](https://github.com/sonic240612/pi-compact-model) |
| **Life** | [HueWorld](https://github.com/sonic240612/HueWorld) · [zen_pebble](https://github.com/sonic240612/zen_pebble) · [Focus Forest](https://github.com/sonic240612/Focus-Forest) |

## Competitions

**2nd / 81 · Top 2.5% · 최우수상** - [2026 국립공원 위성 모니터링 AI 챌린지 — 주제 2: 산사태 붕괴지 탐지 및 위험도 분석](https://aifactory.space/ko/competitions/9305)

## Featured Projects

### <img src="assets/project-icons/lodex.svg" width="32" height="32" align="middle" alt="" /> &nbsp; Lodex

**로컬 LLM 기반 데스크톱 AI 에이전트** · 초기 개발

로컬 LLM과 OpenRouter 모델을 연결해 프로젝트의 계획 수립부터 코드 수정·검증까지 수행하는 데스크톱 AI 에이전트입니다.

- **Plan / Build 분리** — 읽기 전용 계획 수립과 권한 설정에 따른 실행을 구분
- **모델 라우팅·병렬 작업** — Plan·Build·서브에이전트별 모델 선택, Git worktree로 격리된 Build 서브에이전트 실행
- **확장과 컨텍스트 관리** — Skills·MCP 연동, 대화 압축과 로컬 작업 기록 유지

**Stack** · Tauri + React 데스크톱 UI, Node.js 에이전트 데몬, SQLite 로컬 저장소

[GitHub ↗](https://github.com/sonic240612/Lodex)

### <img src="assets/project-icons/if.svg" width="32" height="32" align="middle" alt="" /> &nbsp; iF

**AI 캐릭터 채팅 & 인터랙티브 스토리텔링 플랫폼**

유저가 서사의 주체가 되는 AI 캐릭터 채팅 플랫폼입니다. 대화할수록 캐릭터의 관계와 말투가 변합니다.

- **FSM 감정 엔진** — `[호감도, 집착도, 혐오, 질투]` 4차원 감정 벡터를 실시간 갱신해 캐릭터의 어조가 동적으로 변화
- **RAG 장기기억** — 대화 이력을 기억하는 캐릭터 구현

**Stack** · FastAPI + LLM (Gemma · Gemini), Docker 배포

[Live Demo ↗](https://if-chat-plum.vercel.app) · [GitHub](https://github.com/sonic240612/iF)

### <img src="assets/project-icons/whereto.svg" width="32" height="32" align="middle" alt="" /> &nbsp; WhereTo?

**지도 기반 랜덤 장소 탐색 서비스**

어디로 갈지 고민될 때, 원하는 지역과 카테고리 안에서 다음 목적지를 뽑아보는 앱입니다. 위치 권한 없이도 지역 검색이나 지도 이동으로 시작할 수 있습니다.

- **영역·카테고리별 추첨** — 지도에 점을 찍어 다각형 범위를 지정하고, 음식점·카페 등 원하는 분류의 장소 후보를 무작위로 추천
- **Liquid Glass UI** — 지도 위 유리 굴절·반사광과 스프링 모션, 클래식 디자인 전환 및 효과 조절
- **공유·방문 기록** — 장소 링크 공유, 카카오맵·Google Maps·Apple Maps 길찾기, 브라우저 내 기록 관리와 JSON 백업·복원

**Stack** · React 19 + TypeScript + Vite + Tailwind CSS, Kakao Maps SDK · 선택적 백엔드: Express + Prisma + PostgreSQL

[Live Demo ↗](https://whereto-swart.vercel.app) · [GitHub](https://github.com/sonic240612/whereto)

### <img src="assets/project-icons/beatsync.svg" width="32" height="32" align="middle" alt="" /> &nbsp; BeatSync

**실시간 멀티플레이어 음악 퀴즈 & 타임라인 카드 배틀**

음원을 듣고 제목과 가수를 맞히는 스피드 퀴즈와 발매연도를 추리해 타임라인 슬롯에 카드를 배치하는 전략 파티 게임입니다. Spotify 무료 계정이나 비로그인 상태에서도 30초 고음질 실음원으로 즉시 플레이할 수 있습니다.

- **다국어 정답 판정 엔진** — K-Pop, J-Pop, Pop의 한·일·영 공식 표기 및 음차/번역 매칭, 아티스트 성/이름 규칙 지원
- **무중단 30초 스트리밍** — Spotify Web API와 iTunes/Deezer 자동 폴백 오디오 파이프라인으로 유료 구독 장벽 제거
- **Liquid Glass UI & 소켓 동기화** — visionOS 스타일 광학 굴절 인터페이스와 Socket.IO 기반 실시간 룸 상태 머신

**Stack** · Next.js 15 (React 19) + Express 5, Socket.IO, Tailwind CSS, Zustand, Spotify Web API

[GitHub ↗](https://github.com/sonic240612/beatsync)

### <img src="assets/project-icons/pi-telegram.svg" width="32" height="32" align="middle" alt="" /> &nbsp; pi-telegram

**pi 코딩 에이전트용 Telegram 원격 브리지 확장**

터미널에서 실행 중인 pi 코딩 에이전트 세션을 모바일이나 외부 Telegram 채팅에서 제어할 수 있도록 연결하는 확장 프로그램입니다. 터미널의 실시간 출력을 미러링하고 모바일에서도 주요 명령을 실행할 수 있습니다.

- **원격 세션 미러링** — 터미널 진행 상황, 모델의 사고 과정(Thinking), 도구 실행 결과 및 오류를 Telegram 메시지로 실시간 중계
- **인라인 키보드 인터랙션** — 주요 pi 명령어와 선택지를 인라인 버튼으로 구성해 모바일에서도 손쉬운 제어 지원
- **보안 페어링** — 일회용 코드 기반 터미널 승인 절차를 거친 인가된 사용자만 세션에 접근 가능하도록 보호

**Stack** · TypeScript, Node.js, Telegram Bot API, pi Agent SDK

[GitHub ↗](https://github.com/sonic240612/pi-telegram)
