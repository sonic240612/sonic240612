## Seongwoo Choi

**Major:** Computer Engineering  
**Interests:** Stable Diffusion, AI Agents, LLM

---

## 🤖 AI-First Development

> **이 포트폴리오의 모든 프로젝트는 AI를 활용해 1인 제작했습니다.**

프론트엔드·백엔드·배포까지 LLM과 코딩 에이전트와 함께 개발하고 있습니다. AI를 개발 도구로 쓰는 것뿐 아니라, 제품 안에 AI 기능을 직접 구현하는 것도 관심사입니다 (iF). 관심 분야를 실제 서비스로 만들어보며, 관심을 프로젝트로 꾸준히 이어가고 있습니다.

1인이 기획부터 배포까지 전체를 책임지는 구조에서, **어떤 기술을 조합할지 결정하고 AI가 만든 결과를 검증·마무리하는 것**이 제 주된 역할입니다.

## 📦 Projects Portal

프로젝트와 대회 참여 기록을 한 번에 볼 수 있는 포털 페이지입니다.

🔗 [projects-portal (GitHub)](https://github.com/sonic240612/projects-portal) · [Live Demo](https://projects-portal-beta.vercel.app)

| 🎮 Playground | 🔧 Tools | 🧪 Lab | ☕ Life |
|--------------|----------|--------|--------|
| open-survivor · LADDER · TikaTuka · Apex Button · iF · Mars Panic!!! | WhereTo? · PixelCircle | Lodex · hand-in-hand | HueWorld · zen_pebble · Focus Forest |

## 🏆 Competitions

**2 / 81** - 2026 국립공원 위성 모니터링 AI 챌린지 — 주제 2: 산사태 붕괴지 탐지 및 위험도 분석

## 🚀 Featured Projects

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

### HueWorld — 실시간 글로벌 무드 맵

> 사람들이 지금 느끼는 감정을 색깔로 표현하고, 어두운 세계 지도 위에 LED 픽셀로 시각화합니다.

- **실시간 업데이트** — Supabase Realtime으로 새 무드가 즉시 지도에 표시
- **프라이버시 보호** — GPS 좌표 ±100m 지터, 세션 전용 UUID, 계정 불필요
- **대시보드** — 글로벌 평균 무드, 지역별 분포, 국가별 랭킹 제공
- React 19 + MapLibre GL JS 프론트엔드, FastAPI + PostGIS (Supabase) 백엔드

🔗 [GitHub](https://github.com/sonic240612/HueWorld) · [Live Demo](https://hueworld.vercel.app)

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
