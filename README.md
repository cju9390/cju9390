<div align="center">

# 최주용 | Juyong Choi

**생명과학에서 의료 AI로, 도메인을 아는 개발자**

[![GitHub](https://img.shields.io/badge/GitHub-cju9390-181717?style=flat-square&logo=github)](https://github.com/cju9390)
[![Email](https://img.shields.io/badge/Email-cju9390@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cju9390@naver.com)
[![Location](https://img.shields.io/badge/Location-대전광역시-0078D4?style=flat-square)](https://maps.google.com)
[![Blog](https://img.shields.io/badge/Blog-taeddy--note-FF5722?style=flat-square&logo=tistory&logoColor=white)](https://taeddy-note.tistory.com)

</div>

---

## About Me

KRIBB 대사조절연구센터에서 4년 6개월간 간 대사 메커니즘을 연구한 생명과학자 출신입니다.

현재 미래융합교육원에서 AI·데이터 과정을 수강하며 의료 AI 개발자로 전환 중입니다.

**희망 직무:** 의료 AI 개발 / 헬스케어 데이터 분석

---

## Skills

**ML / AI** — XGBoost, SHAP, Scikit-learn, PyTorch, DINO (ViT), ABMIL, phikon-v2, Hibou-L, BioBERT  
**Data** — Python, SQL, Pandas, NumPy, Matplotlib, Seaborn  
**Database** — PostgreSQL, MySQL, SQLite  
**Backend** — FastAPI, Flask  
**Frontend** — HTML5, CSS3, JavaScript, React, TypeScript, Chart.js, Streamlit  
**기타** — Git, GitHub, Docker, WebSocket, PWA, UMAP  
**Bio Domain** — Western blot, qRT-PCR, 세포배양, 마우스 조직 처리, MIMIC-IV, WSI 병리 분석

---

## Projects

### WSI 신장 병리 자동 분석 시스템
`PyTorch` `ABMIL` `phikon-v2` `Hibou-L` `DINOv2` `DINO` `FastAPI` `React` · 개인 프로젝트 · 완료

공개 KPMP 데이터셋(H&E·MT 염색 슬라이드)에서 병리 특화 Foundation Model로 WSI를 인코딩하고,  
ABMIL 모델로 섬유화·염증·세뇨관 위축·사구체 경화 등 5개 병리 지표를 자동 정량화하는 시스템을 구현했습니다.  
인코더 5종(phikon-v2, Hibou-L, DINOv2-L, 자체 DINO ep90·ep200) 비교 실험, 5-fold GroupKFold CV,  
Masked MSE 손실 함수 설계, UMAP + K-Means(k=9) 클러스터링 분석 포함.  
H&E 섬유화 Pearson r **0.82** 달성. FastAPI 추론 API + React/TypeScript 뷰어 연동.

---

### AKI CDSS — 급성 신손상 임상 의사결정 지원 시스템
`Python` `XGBoost` `SHAP` `FastAPI` `PostgreSQL` `Streamlit` · 팀 프로젝트 (CHYM, 4인) · 팀장

MIMIC-IV 기반으로 ICU 환자의 48시간 내 AKI 발생을 예측하는 ML 모델과 CDSS 대시보드를 구축했습니다.  
**AUROC 0.9753** 달성. 처방·혈압·신독성 약물·NLP 텍스트 등 7개 영역 멀티트랙 SQL 피처 파이프라인 설계,  
데이터 누수 문제 해결, 사망 경쟁 이벤트 코호트 정의, BioBERT 기반 NLP Track 구현을 주도했습니다.

---

### MBTI × RPG 판타지 직업 예측 웹앱
`Flask` `XGBoost` `SQLite3` `Chart.js` · 개인 프로젝트 · 완료

60문항 MBTI 설문 → XGBoost 모델로 유형 예측 → 판타지 RPG 직업(16종) 매핑 + 6가지 스탯 레이더 차트.  
보완형 파티 추천, 퀘스트 유형별 파티 조합 기능 포함. 문항 방향성 버그(ISTJ 편향) 디버깅 경험.

---

### 로컬 파일 서버
`FastAPI` `WebSocket` `PWA` `Cloudflare Tunnel` · 개인 프로젝트 · 완료

FastAPI + WebSocket 기반 팀 공유 파일 서버. Cloudflare Tunnel로 외부 공개, 운영 비용 0원.  
최대 2GB 파일 전송(SHA-256 무결성 검증), 병리 WSI 딥줌 뷰어(OpenSeadragon), 실시간 채팅,  
휴지통 복원, Jupyter Notebook 렌더링, 다크모드, PWA 설치 지원.

---

## Experience

**한국생명공학연구원 대사제어연구센터** · 학생연구원 · 2021.02 – 2025.11 (4년 6개월)  
고지방식이 마우스 모델 대사 이상 실험 설계, 간 조직 처리, Western blot·qRT-PCR 유전자 발현 분석.

---

## Education

**과학기술연합대학원대학교 (UST)** 박사 수료 · 생명과학/기능유전체학 · 2021.09 – 2023.08  
**아주대학교 의과대학대학원** 석사 · 의생명과학과 · 2017.03 – 2019.08  
**배재대학교** 학사 · 생물의약학과 · 2011.03 – 2017.02

---

## Certificates & Awards

**SQLD** (2026.03) · **TOEIC 760** (2019.11) · 1종 보통 운전면허 (2012.09)  
**우수상** — 미래융합교육원 프로젝트·평가·출석 종합 우수 (2026.05)

---

## Publications

- *Cellular heterogeneity and plasticity during NAFLD progression* — **주저자**, 2023
- *Ufd1 phosphorylation at serine 229 negatively regulates ER-associated degradation* — 공저자, 2019
- *Histone deacetylase 6 inhibitor tubastatin A attenuates angiotensin II-induced hypertension* — 공저자, 2019
- *NEDD4-induced degradative ubiquitination of PIP5Kα and breast cancer cell proliferation* — 공저자, 2018
- *PIP5Kα contributes to Toll-like receptor 2-mediated immune responses in microglial cells* — 공저자, 2017

---

<div align="center">

cju9390@naver.com · 📍 대전광역시 · [github.com/cju9390](https://github.com/cju9390)

</div>
