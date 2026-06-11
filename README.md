# AI 서비스 허브 (mysite_2606)

AI 관련 서비스 URL을 카테고리별로 정리한 정적 웹사이트입니다.

**라이브 URL:** https://kjin618-rgb.github.io/mysite_2606/

---

## 화면 구성

| 영역 | 설명 |
|------|------|
| 상단 메뉴 | 대 카테고리 탭 (AI 어시스턴트 / AI 창작 / AI 개발 / AI 플랫폼) |
| 사이드 메뉴 | 선택한 대 카테고리의 소 카테고리 목록 + 전체 보기 |
| 본문 | 서비스 카드 그리드 (아이콘 · 이름 · 설명 · 뱃지 · 바로가기) |
| 헤더 우측 | 방문자 수 카운터 |

---

## 카테고리 및 등록 서비스 (총 53개)

### 💬 AI 어시스턴트
| 소 카테고리 | 서비스 |
|------------|--------|
| 챗봇 | Claude, ChatGPT, Gemini, Grok, Genspark, Copilot, Meta AI, Poe, Character.ai, Kimi, Qwen |
| AI 검색 | Perplexity, You.com, Phind, DeepL |

### 🎨 AI 창작
| 소 카테고리 | 서비스 |
|------------|--------|
| 이미지 생성 | Whisk, Midjourney, DALL·E 3, Adobe Firefly, Leonardo AI, Ideogram, Stable Diffusion, Krea AI, Canva |
| 음악 생성 | SUNO, Udio, ElevenLabs |
| 비디오 생성 | RunwayML, Pika, Kling AI, Sora, Veo 3, HeyGen, Luma AI, Descript |

### 💻 AI 개발
| 소 카테고리 | 서비스 |
|------------|--------|
| 코드 어시스턴트 | Lovable, V0, Cursor, GitHub Copilot, Bolt, Replit, Windsurf |
| 프롬프트 & 자동화 | Dify, LangChain, n8n, Gamma |

### 🏗️ AI 플랫폼
| 소 카테고리 | 서비스 |
|------------|--------|
| 모델 & 데이터 | Hugging Face, Replicate, Ollama, Together AI, Civitai |
| API & 클라우드 | Anthropic API, OpenAI API, Google AI Studio, Groq, fal.ai |
| 개발 & 협업 | GitHub, Kaggle, Papers with Code, Weights & Biases |

---

## 방문자 카운터

- **API:** [counterapi.dev](https://counterapi.dev) (무료, CORS 지원)
- **표시:** 헤더 우측 `👁 방문자 N` 형태
- **집계:** GitHub Pages URL 기준 누적 방문 수

---

## 작업 이력

| 일자 | 내용 |
|------|------|
| 2026-06-11 | 초기 사이트 생성 (37개 서비스, 4대 카테고리 구조) |
| 2026-06-11 | AI 서비스 10개 추가 (Gamma, Poe, Character.ai, HeyGen, Luma AI, Krea AI, DeepL, Descript, fal.ai, Civitai) |
| 2026-06-11 | Canva, Kimi, Qwen, AI Studio 추가 요청 (AI Studio는 기존 등록 확인) |
| 2026-06-11 | 방문자 카운터 추가 — countapi.xyz(서비스 종료) → counterapi.dev 교체 |
| 2026-06-11 | 방문자 배지 이미지 방식 시도 — hits.seeyoufarm.com(404), visitor-badge.laobi.icu 순 교체 |
| 2026-06-11 | 방문자 카운터 HTML+CSS 방식으로 최종 교체 (한글 자간 문제 해결) |
| 2026-06-11 | JS 중복 코드 정리 (renderSidebar · selectCat 이중 정의, updateSideAll · renderSidebar2 제거) |

---

## 기술 스택

- **HTML / CSS / Vanilla JS** — 단일 파일, 외부 라이브러리 없음
- **GitHub Pages** — 정적 호스팅
- **counterapi.dev** — 방문자 카운터 API
