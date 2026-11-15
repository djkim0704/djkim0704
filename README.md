![header](https://capsule-render.vercel.app/api?type=waving&color=0:3348C9,100:7C8BE0&height=200&section=header&text=Dongjun's%20GitHub&fontSize=70&fontColor=FFFFFF)

# About Me

- 다양한 분야를 직접 경험하며 배우는 것을 좋아해, 백엔드부터 멀티모달 AI, 시계열 연구, 클라우드 보안까지 참여해 왔습니다.
- 스포츠 중계 분석 서비스에서 백엔드 인턴으로 일했습니다.
- 지금은 AI Systems Lab에서 시계열 모델을 연구하며 화이트햇스쿨에서 클라우드 보안을 배우고 있습니다.

# Skills

### Languages, Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

### LLM, ML

![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Chronos-2](https://img.shields.io/badge/Chronos--2-232F3E?style=flat)
![LoRA](https://img.shields.io/badge/LoRA-FFD21E?style=flat&logo=huggingface&logoColor=black)

### Audio, Video

![faster-whisper](https://img.shields.io/badge/ASR-faster--whisper-555555?style=flat)
![TransNet](https://img.shields.io/badge/장면%20전환%20검출-TransNet-555555?style=flat)
![OCR](https://img.shields.io/badge/OCR-555555?style=flat)
![VLM](https://img.shields.io/badge/VLM-555555?style=flat)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat&logo=ffmpeg&logoColor=white)
![HLS](https://img.shields.io/badge/HLS-555555?style=flat)
![NVENC](https://img.shields.io/badge/NVENC-76B900?style=flat&logo=nvidia&logoColor=white)

### Infra, Collaboration

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCS](https://img.shields.io/badge/GCS-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)

# Experiences

| 활동 | 내용 | 기간 |
| --- | --- | --- |
| 세븐미닛 백엔드 개발 인턴 | AI로 스포츠 생중계를 분석해 하이라이트를 만드는 서비스의 API 서버, 영상 분석 파이프라인, 운영 콘솔 | 2026.06 ~ 2026.10 |
| 세종대학교 AI Systems Lab 학부연구생 | 수소연료전지(PEMFC) 진단용 시계열 Foundation 모델 연구 | 2026.01 ~ |
| 화이트햇스쿨 4기 | 클라우드 보안 과정, 클라우드 침해 대응 자동화 팀 프로젝트 | 2026.06 ~ 2026.12 |
| 특허 *(출원 준비 중)* | 입체화 속성을 포함하는 가구 벡터 및 공통 공간 데이터를 이용한 인공지능 기반 인테리어 설계 방법 및 시스템 | 2026 |
| 컴퓨터활용능력 1급 | 대한상공회의소 | 2022.02 |

### 인턴 주요 성과

- **LLM 질의 해석 개선**: 프롬프트에는 정의를, 코드에는 사실 계산과 검사를 맡겨 "최근 대회" 해석 48/48 정답, 운영 질문 803종 재판정 회귀 0건
- **자연어 질의 라우팅**: 정답지와 채점기부터 만들고 모델을 비교해 133문장 분류 정확도 100%
- **API 응답 지연 개선**: 단계별 계측으로 원인을 찾아 요청 시간 중간값 10.17초 → 4.69초
- **중계 화면 자막 판독**: 견본 매칭과 OCR 기준값을 115개 런 전체로 재서 한 대회 샷 판독률 64.6% → 100%
- **4화질 스트리밍**: NVENC로 1080p~360p HLS 구현, GPU 인코더 실패 시 CPU 전환 후 자동 복귀

# Projects

| 프로젝트명 | 기간 | 핵심 기술 | 설명 |
| --- | --- | --- | --- |
| [LoL 중계 번역 실험](https://github.com/Esports-local) *(개인)* | 2026.11 | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/DRF-092E20?style=flat&logo=django&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) | 화면 OCR과 영상 프레임이 고유명사 번역을 얼마나 돕는지 조건별 비교 |
| 클라우드 침해 대응 자동화 *(WHS 4기 팀)* | 2026.08 ~ 10 | ![AWS](https://img.shields.io/badge/Step%20Functions-FF4F8B?style=flat&logo=amazonwebservices&logoColor=white) ![Elastic](https://img.shields.io/badge/ELK-005571?style=flat&logo=elastic&logoColor=white) | 위험 등급에 따라 자동 대응(HOTL)과 사람 승인(HITL)을 나누는 대응 계층 담당 |
| [AI 인테리어 설계](https://github.com/djkim0704/interior) *(팀)* | 2026.06 ~ | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) | 방 사진 한 장으로 2D 평면도와 3D 공간 생성, 가구 추천. 특허 출원 준비 중 |
| [AI 뉴스 요약 서비스](https://github.com/djkim0704/ai-news-summary) *(팀장)* | 2026.05 ~ 06 | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![Vue](https://img.shields.io/badge/Vue-35495E?style=flat&logo=vuedotjs&logoColor=4FC08D) | BigKinds 뉴스를 수집해 Gemini로 요약하고 키워드 통계를 보여 주는 서비스 |
| [Ensight](https://github.com/sychoi0129/ensight) *(팀)* | 2026.04 ~ 06 | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) | 전력 수요 예측과 LLM 설명 리포트, 리포트 수치 정합성 검사 |
| [Days of Survival](https://github.com/onegood07/days-of-survival) *(팀)* | 2025.10 ~ 12 | ![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white) | 좀비 생존 2D 게임 |
