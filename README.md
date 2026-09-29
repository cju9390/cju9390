<div align="center">

# 최주용 | Juyong Choi

**원인을 끝까지 확인하는, 생명과학에서 온 의료 AI 개발자**

[![GitHub](https://img.shields.io/badge/GitHub-cju9390-181717?style=flat-square&logo=github)](https://github.com/cju9390)
[![Email](https://img.shields.io/badge/Email-cju9390@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cju9390@naver.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion)](https://www.notion.so/Portfolio-AI-356a28e78b6f818f96d1c1e040fbdc38)
[![Blog](https://img.shields.io/badge/Blog-taeddy--note-FF5722?style=flat-square&logo=tistory&logoColor=white)](https://taeddy-note.tistory.com)
![Location](https://img.shields.io/badge/Location-대전광역시-0078D4?style=flat-square)

</div>

---

## About Me

한국생명공학연구원(KRIBB) 대사제어연구센터에서 4년 6개월간 간 대사·섬유화 기전을 연구했습니다.
건양대병원 미래융합교육원 「바이오메디컬 인공지능」 과정을 거쳐 의료 AI 개발자로 전환 중입니다.

**희망 직무:** 의료 AI 개발 / 헬스케어 데이터 분석

---

## Projects

| 프로젝트 | 한 줄 요약 | 핵심 결과 | 코드 |
|---|---|---|---|
| **한영 의료용어 매핑 RAG** | 한글 질의를 표준 영문 의학용어로 매핑해 PubMed·질병관리청 문서를 검색·응답 | Recall@3 33.3% → **100%** (검색 단계) | [medical-term-rag-ko-en](https://github.com/cju9390/medical-term-rag-ko-en) |
| **WSI 신장 병리 정량예측 CDSS** | 신장 생검 WSI에서 병리 지표를 ABMIL로 정량예측, PACS 연동 병리과 뷰어 | 세뇨관 위축 Spearman ρ **0.74** | [wsi-kidney-pathology](https://github.com/cju9390/wsi-kidney-pathology) |
| **AKI 48시간 조기예측 CDSS** | MIMIC-IV 41,576건으로 ICU 환자 AKI 발생 예측 (4인 팀, 팀장) | AUROC **0.9753** / AUPRC **0.9611** | [kidn_proj](https://github.com/cju9390/kidn_proj) · [팀 레포](https://github.com/leechaehui/chym_aki) |
| **MBTI × RPG 직업 예측 웹앱** | 60문항 설문 → XGBoost로 MBTI 예측 → RPG 직업·스탯·파티 추천 | 문항 방향성 버그(ISTJ 편향) 해결 | [project_mbti_job_game.io](https://github.com/cju9390/project_mbti_job_game.io) |
| **팀 파일 서버** | FastAPI + WebSocket 팀 공유 파일 서버, Cloudflare Tunnel로 무료 외부 공개 | 2GB 전송·SHA-256 검증·WSI 뷰어 | [team-file-server](https://github.com/cju9390/team-file-server) |

### 한영 의료용어 매핑 RAG
`Python` `Ollama(gemma2:9b)` `Chroma` `sentence-transformers` `NCBI E-utilities` · 개인 프로젝트 · 진행 중

상병마스터·KOSTOM·AI Hub 용어사전을 출처 신뢰도 순으로 병합(95,673건)하고, 사전 매핑을 힌트로 로컬 LLM이 검색어를 번역·보완하는 하이브리드 구조를 설계했습니다.
사전만 쓸 때 Recall@3 33.3%에 그쳤던 원인(해부학·약물·최신 약물명 미등재)을 평가셋으로 추적해 100%로 개선했습니다.

### WSI 신장 병리 정량예측 CDSS
`PyTorch` `ABMIL` `phikon-v2` `Hibou-L` `OpenSlide` `FastAPI` `React/TypeScript` · 팀 프로젝트 (CHYM, 4인) · 완료

KPMP 공개 WSI(H&E 166장, MT 174장)에서 범용 모델(DINOv2)이 MT 염색에 예측력을 보이지 못하는 것을 확인하고 병리 특화 인코더(phikon-v2·Hibou-L)로 교체했습니다.
병리 정량예측 파트와 PACS 연동 백엔드(SVS→DICOM 변환·업로드, DeepZoom 타일 서버), ABMIL 추론 API, Attention 히트맵 뷰어를 담당했습니다.

### AKI 48시간 조기예측 CDSS
`PostgreSQL` `XGBoost` `Optuna` `SHAP` `FastAPI` · 팀 프로젝트 (CHYM, 4인) · 팀장

MIMIC-IV 기반 멀티트랙 SQL 피처 파이프라인, 환자 단위 Stratified Group K-Fold, SHAP 설명가능성을 적용했습니다.
약물·신독성 피처 엔지니어링, XGBoost 모델링, FastAPI 백엔드를 담당했습니다.

---

## Skills

**ML / AI** — XGBoost, SHAP, scikit-learn, PyTorch, ABMIL, phikon-v2, Hibou-L, DINOv2, BioBERT  
**LLM / RAG** — Ollama, Chroma, sentence-transformers  
**Data / DB** — Python, SQL, Pandas, PostgreSQL, SQLite  
**Backend** — FastAPI, Flask, WebSocket  
**Frontend** — React, TypeScript, Vite, OpenSeadragon, Chart.js  
**Medical Imaging** — OpenSlide, DeepZoom, wsidicomizer (SVS→DICOM)  
**Tools** — Git, Docker, Claude Code  
**Bio Domain** — 간특이적 유전자결손 마우스 모델, 조직염색·IHC, 1차 세포 분리배양, RNA-seq(DEG) 분석

---

## Experience

**한국생명공학연구원 대사제어연구센터** · 총 4년 6개월  
- 학생연구원 · 2021.09 – 2024.03, 2024.09 – 2025.11  
- 인턴 · 2021.02 – 2021.09  

간특이적 유전자결손 마우스 기반 대사이상지방간염·간섬유화 모델 설계·수행, 세포유형별 기능 검증(rescue 실험), mRNA-seq DEG 분석.

---

## Education

**과학기술연합대학원대학교 (UST)** 박사 수료 · 생명과학/기능유전체학 · 2021.09 – 2023.08  
**아주대학교 대학원** 석사 · 의생명과학과 · 2017.03 – 2019.08  
**배재대학교** 학사 · 생물의약학과 · 2011.03 – 2017.02  
**건양대병원 미래융합교육원** 바이오메디컬 인공지능 4기 · 2025.12 – 2026.07

---

## Certificates & Awards

**SQLD** (2026.03) · **TOEIC 760** (2019.11)  
**우수상** — 미래융합교육원 프로젝트·평가·출석 종합 우수 (2026.05)

---

## Publications

- *Cellular heterogeneity and plasticity during NAFLD progression* — Front Mol Biosci, 2023 · **공동1저자**
- *Ufd1 phosphorylation at serine 229 negatively regulates ER-associated degradation* — Biochem J, 2019 · 공저자
- *Histone deacetylase 6 inhibitor tubastatin A attenuates angiotensin II-induced hypertension* — Pharmacol Res, 2019 · 공저자
- *NEDD4-induced degradative ubiquitination of PIP5Kα and breast cancer cell proliferation* — J Cell Mol Med, 2018 · 공저자
- *PIP5Kα contributes to Toll-like receptor 2-mediated immune responses in microglial cells* — Cell Signal, 2017 · 공저자
