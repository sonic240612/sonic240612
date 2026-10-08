## Seongwoo Choi

**Major:** Computer Engineering  
**Interests:** Stable Diffusion, AI Agents, LLM

---

## 🤖 AI-First Development

> **이 포트폴리오의 모든 프로젝트는 AI를 활용해 1인 제작했습니다.**

프론트엔드·백엔드·배포까지 LLM과 코딩 에이전트와 함께 개발하고 있습니다. AI를 개발 도구로 쓰는 것뿐 아니라, 제품 안에 AI 기능을 직접 구현하는 것도 관심사입니다 (iF). 관심 분야를 실제 서비스로 만들어보며, 관심을 프로젝트로 꾸준히 이어가고 있습니다.

1인이 기획부터 배포까지 전체를 책임지는 구조에서, **어떤 기술을 조합할지 결정하고 AI가 만든 결과를 검증·마무리하는 것**이 제 주된 역할입니다.

## 📦 Projects Portal

제가 만든 프로젝트를 한 번에 볼 수 있는 포털 페이지입니다.

🔗 [projects-portal (GitHub)](https://github.com/sonic240612/projects-portal) · [Live Demo](https://projects-portal-beta.vercel.app)

| 🎮 Playground | 🔧 Tools | 🧪 Lab | ☕ Life |
|--------------|----------|--------|--------|
| open-survivor · LADDER · TikaTuka · iF · Mars Panic!!! | WhereTo? · PixelCircle | Lodex · hand-in-hand | HueWorld · zen_pebble · Focus Forest |

## 🏆 Competitions

**2nd / 81 · Top 2.5% · 최우수상** - [2026 국립공원 위성 모니터링 AI 챌린지 — 주제 2: 산사태 붕괴지 탐지 및 위험도 분석](https://aifactory.space/ko/competitions/9305)

## 🚀 Featured Projects

### Lodex — 로컬 LLM 기반 데스크톱 AI 에이전트

> 로컬 LLM과 OpenRouter 모델을 연결해 프로젝트의 계획 수립부터 코드 수정·검증까지 수행하는 데스크톱 AI 에이전트입니다. 현재 초기 개발 단계입니다.

- **Plan / Build 분리** — 읽기 전용 계획 수립과 권한 설정에 따른 실행을 구분
- **모델 라우팅·병렬 작업** — Plan·Build·서브에이전트별 모델 선택, Git worktree로 격리된 Build 서브에이전트 실행
- **확장과 컨텍스트 관리** — Skills·MCP 연동, 대화 압축과 로컬 작업 기록 유지
- Tauri + React 데스크톱 UI, Node.js 에이전트 데몬, SQLite 로컬 저장소

🔗 [GitHub](https://github.com/sonic240612/Lodex)

### iF — AI 캐릭터 채팅 & 인터랙티브 스토리텔링 플랫폼

> 유저가 서사의 주체가 되는 AI 캐릭터 채팅 플랫폼입니다. 대화할수록 캐릭터의 관계와 말투가 변합니다.

- **FSM 감정 엔진** — `[호감도, 집착도, 혐오, 질투]` 4차원 감정 벡터를 실시간 갱신해 캐릭터의 어조가 동적으로 변화
- **RAG 장기기억** — 대화 이력을 기억하는 캐릭터 구현
- FastAPI + LLM (Gemma · Gemini) 아키텍처, Docker 배포

🔗 [GitHub](https://github.com/sonic240612/iF) · [Live Demo](https://if-chat-plum.vercel.app)

### WhereTo? — 랜덤 장소 추천 서비스

> 결정 장애를 위한 랜덤 장소 추천. 지도에서 범위를 드래그하면 그 안에서 무작위 장소를 추천합니다.

- 모바일 터치 드래그로 범위 지정 지원
- Google Maps · Apple Maps 길찾기 링크 연동, 방문 기록 저장
- React 19 + Leaflet 프론트엔드, Express + PostgreSQL (Neon) 백엔드

🔗 [GitHub](https://github.com/sonic240612/whereto) · [Live Demo](https://whereto-swart.vercel.app)

### Mars Panic!!! — 비공개 프로젝트

Playground(게임) 카테고리의 비공개 프로젝트입니다. 개인적으로 제작 중인 멀티플레이 게임이며, 상세 내용은 추후 공개 예정입니다.

## 🛠️ 사용한 기술

> 아래는 프로젝트에 적용된 스택입니다. AI와 함께 개발하면서 직접 다루며 익혀가는 중이에요.

| 구분 | 기술 |
|------|------|
| Frontend | TypeScript · React (Vite), JavaScript |
| Backend | Node.js (Express · Fastify), Python (FastAPI) |
| AI / ML | LLM Integration, RAG |
| DB / Realtime | PostgreSQL (+ PostGIS), Supabase Realtime, Socket.IO |
| Infra | Docker, Vercel |
