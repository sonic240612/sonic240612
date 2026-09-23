# Seongwoo Choi

컴퓨터공학을 전공하며 AI 에이전트와 실제로 사용할 수 있는 서비스를 만드는 1인 개발자입니다.

아이디어를 기획하고 기술을 선택해 구현·배포까지 이어갑니다. 모든 프로젝트에서 LLM과 코딩 에이전트를 활용하며, 생성된 결과를 직접 검토하고 검증합니다. AI를 개발 과정에 활용하는 것뿐 아니라 제품의 기능으로 구현하는 데도 관심이 있습니다.

**관심 분야:** AI Agents · LLM · Stable Diffusion

## 🚀 대표 프로젝트

### Lodex — 데스크톱 AI 에이전트

로컬 LLM과 OpenRouter 모델을 연결해 프로젝트 작업을 수행하는 데스크톱 에이전트 하네스입니다. 현재 개발 초기 단계입니다.

- Plan·Build·서브에이전트마다 모델을 선택하고 로컬 프로젝트 폴더에서 작업할 수 있습니다.
- 파일 변경 검토와 검증, 권한 단계, Git worktree 등 에이전트 작업 흐름을 구현했습니다.

[GitHub](https://github.com/sonic240612/Lodex)

### hand-in-hand — Codex 세션 협업 프로토타입

여러 사람이 하나의 프로젝트와 Codex 세션을 이어서 사용하는 협업 실험입니다.

- 참여자는 자신의 기기에 연결된 Codex로 차례대로 작업하고, 이전 대화와 도구 결과를 같은 세션에서 이어받습니다.
- 호스트가 프로젝트와 세션 원본을 보관하며, Tailscale 기반 사설 연결과 작업 승인·기록 확인을 지원합니다.

[GitHub](https://github.com/sonic240612/hand-in-hand)

### iF — AI 캐릭터 채팅과 인터랙티브 스토리텔링

사용자가 서사의 주체가 되는 AI 캐릭터 채팅 플랫폼입니다. 대화에 따라 캐릭터의 관계와 말투가 달라집니다.

- 4차원 감정 벡터를 갱신하는 FSM 엔진으로 캐릭터의 반응을 조절합니다.
- RAG 기반 장기기억으로 이전 대화를 반영합니다.

[GitHub](https://github.com/sonic240612/iF) · [Live Demo](https://if-chat-plum.vercel.app)

### HueWorld — 실시간 글로벌 무드 맵

사람들이 느끼는 감정을 색으로 기록하고 세계 지도에서 함께 볼 수 있는 서비스입니다.

- Supabase Realtime으로 새 무드를 지도에 즉시 반영합니다.
- 위치 좌표에 지터를 적용하고, 지역별 분포와 국가별 순위를 시각화합니다.

[GitHub](https://github.com/sonic240612/HueWorld) · [Live Demo](https://hueworld.vercel.app)

## 📦 전체 프로젝트

[Projects Portal](https://projects-portal-beta.vercel.app)에서 Playground · Tools · Lab · Life 카테고리의 모든 프로젝트를 볼 수 있습니다. [포털 소스 코드](https://github.com/sonic240612/projects-portal)도 공개되어 있습니다.

## 🛠️ 사용한 기술

프로젝트에서 사용한 기술입니다.

| 구분 | 기술 |
|------|------|
| Frontend · Desktop | TypeScript, React, JavaScript, Tauri |
| Backend | Node.js (Express · Fastify), Python (FastAPI) |
| AI | LLM 연동, RAG, llama-server, OpenRouter |
| Data · Realtime | PostgreSQL (+ PostGIS), Supabase Realtime, Socket.IO |
| Infra | Docker, Vercel |
