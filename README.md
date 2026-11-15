# 김동준

다양한 분야를 직접 경험하며 배우는 것을 좋아해, 백엔드부터 멀티모달 AI, 시계열 연구, 클라우드 보안까지 참여해 왔습니다.
스포츠 중계 분석 서비스에서 백엔드 인턴으로 일했고, 지금은 AI Systems Lab에서 시계열 모델을 연구하며 화이트햇스쿨에서 클라우드 보안을 배우고 있습니다.

- 세종대학교 소프트웨어학과, 2027년 9월 졸업 예정
- 세종대학교 AI Systems Lab 학부연구생, 수소연료전지 진단용 시계열 Foundation 모델 연구
- 화이트햇스쿨 4기 클라우드 보안 과정, 2026년 6월 ~ 12월

## 경력

**세븐미닛, 백엔드 개발 인턴** (2026.06 ~ 2026.10)
AI로 스포츠 생중계를 분석해 하이라이트를 만드는 서비스에서 API 서버, 영상 분석 파이프라인, 운영 콘솔을 맡았습니다.

- **LLM 질의 해석 개선**: 프롬프트에는 정의를, 코드에는 사실 계산과 검사를 맡겨 "최근 대회" 해석 48/48 정답, 운영 질문 803종 재판정 회귀 0건
- **자연어 질의 라우팅**: 정답지와 채점기부터 만들고 모델을 비교해 133문장 분류 정확도 100%
- **API 응답 지연 개선**: 단계별 계측으로 원인을 찾아 요청 시간 중간값 10.17초 → 4.69초
- **중계 화면 자막 판독**: 견본 매칭과 OCR 기준값을 115개 런 전체로 재서 한 대회 샷 판독률 64.6% → 100%
- **4화질 스트리밍**: NVENC로 1080p~360p HLS 구현, GPU 인코더 실패 시 CPU 전환 후 자동 복귀

## 프로젝트

| 프로젝트 | 내용 | 기술 |
|---|---|---|
| [Days of Survival](https://github.com/onegood07/days-of-survival)<br>2025.10 ~ 12, 팀 | 좀비 생존 2D 게임. 좀비 추적과 충돌 처리, 인벤토리와 퀵슬롯, 플레이어 조작 구현 | Unity, C# |
| [Ensight](https://github.com/sychoi0129/ensight)<br>2026.04 ~ 06, 팀 | 전력 수요 예측과 LLM 설명 리포트, 리포트 수치 정합성 검사 | FastAPI, PostgreSQL, Chronos-2 |
| AI 뉴스 요약 서비스<br>2026.05 ~ 06, 팀장 | BigKinds 뉴스를 수집해 Gemini로 요약하고 키워드 통계를 보여 주는 서비스 (레포 비공개) | FastAPI, PostgreSQL, Gemini, Vue |
| [AI 인테리어 설계](https://github.com/djkim0704/interior)<br>2026.06 ~, 팀 | 방 사진 한 장으로 2D 평면도와 3D 공간 생성, 가구 추천. 특허 출원 준비 중 | Flask, Gemini, CLIP, GitHub Actions |
| 클라우드 침해 대응 자동화<br>2026.08 ~ 10, WHS 4기 팀 | 위험 등급에 따라 자동 대응(HOTL)과 사람 승인(HITL)을 나누는 대응 계층 담당 | Step Functions, Lambda, ELK |
| LoL 중계 번역 실험<br>2026.11, 개인 | 화면 OCR과 영상 프레임이 고유명사 번역을 얼마나 돕는지 조건별 비교.<br>[analyzer](https://github.com/Esports-local/esports-analyzer), [api](https://github.com/Esports-local/esports-api), [ui](https://github.com/Esports-local/esports-ui) | faster-whisper, Gemini, FastAPI, DRF |

## 기술

- **언어, 백엔드**: Python, C, C++, Java, Django, DRF, FastAPI, MySQL, PostgreSQL, SQLite, pytest
- **LLM, ML**: Gemini, OpenAI API, scikit-learn, Chronos-2, LoRA
- **음성, 영상**: ASR(faster-whisper), 장면 전환 검출(TransNet), OCR, 견본 매칭, VLM, ffmpeg, HLS, NVENC
- **인프라, 협업**: AWS, GCS, Docker, GitHub Actions, Jira
