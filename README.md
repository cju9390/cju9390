<!-- 헤더 -->
<div align="center">

# 최주용 | Juyong Choi

###  생명과학에서 의료 AI로, 도메인을 아는 개발자

*From Bench to Code — Bridging Biology and Medical AI*

[![GitHub](https://img.shields.io/badge/GitHub-cju9390-181717?style=flat-square&logo=github)](https://github.com/cju9390)
[![Blog](https://img.shields.io/badge/Blog-taeddy--note-FF5722?style=flat-square&logo=tistory)](https://taeddy-note.tistory.com)
[![Email](https://img.shields.io/badge/Email-cju9390@naver.com-EA4335?style=flat-square&logo=gmail)](mailto:cju9390@naver.com)

</div>

---

##  About Me

```python
choi_juyong = {
    "background": "생명과학 연구자 (KRIBB 대사제어연구센터, 4년 6개월)",
    "degree"    : ["석사 — 아주대학교 의과대학원 (의생명과학)",
                   "박사 수료 — 과학기술연합대학원대학교 (기능유전체학)"],
    "pivot"     : "의료 AI 개발자",
    "location"  : "대전광역시, 대한민국",
    "strength"  : "임상 데이터의 맥락을 이해하는 개발자",
}
```

> 연구실에서 방대한 실험 데이터를 정리하며 처음 Python을 접했고,
> *"도메인 지식 + IT 기술이 만나면 더 의미 있는 일을 할 수 있다"* 는 확신으로
> 의료 AI 개발자로의 전환을 결심했습니다.

---

##  Featured Projects

###  AKI 조기 예측 CDSS
> **급성 신손상(AKI) 48시간 이내 조기 예측 임상의사결정지원시스템**

| 항목 | 내용 |
|------|------|
| **역할** | 팀장 · 약물 피처 엔지니어링 (트랙 C) · XGBoost 모델링 · FastAPI 백엔드 |
| **데이터** | MIMIC-IV 실제 임상 데이터 — 41,576건 |
| **성능** | **AUROC 0.9753** · AUPRC 0.9611 · F1 0.9093 |
| **스택** | `Python` `XGBoost` `SHAP` `FastAPI` `PostgreSQL` `HTML/CSS/JS` |

**핵심 설계 결정**
- 0~24h 피처 → 48h 이내 AKI 발생 예측 (KDIGO 국제 표준 기반)
- 4-Track 피처 (Lab / 허혈 / 약물 / NLP) → Late Fusion 앙상블
- SHAP TreeExplainer로 "왜 고위험인가" 설명 가능한 AI 구현
- 데이터 누수 방지 — 피처 윈도우 / 레이블 윈도우 완전 분리

---

###  MBTI RPG 직업 예측 웹앱
> **60문항 설문으로 MBTI를 예측하고 판타지 RPG 직업을 추천하는 웹 서비스**

| 항목 | 내용 |
|------|------|
| **역할** | 기획 · 개발 · 배포 전담 |
| **스택** | `Python` `Flask` `XGBoost` `SQLite3` `Chart.js` |

**주요 기능**
- XGBoost 분류기로 MBTI 16유형 예측
- 6가지 RPG 스탯(무력/마력/신성력/민첩성/통솔력/생존력) 변환
- Chart.js 레이더 차트로 스탯 시각화
- 파티 궁합 분석 기능

---

##  Tech Stack

**Language & ML/AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-F7931E?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend & Database**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Frontend & Tools**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

**Bio Domain**

![](https://img.shields.io/badge/Western_blot-6C4F3D?style=flat-square)
![](https://img.shields.io/badge/qRT--PCR-6C4F3D?style=flat-square)
![](https://img.shields.io/badge/Cell_Culture-6C4F3D?style=flat-square)
![](https://img.shields.io/badge/MIMIC--IV-6C4F3D?style=flat-square)

---

##  Certificates & Education

| 자격 / 학력 | 기관 | 연도 |
|------------|------|------|
| **SQL 개발자 (SQLD)** | 한국데이터베이스진흥센터 | 2026 |
| 박사 수료 — 생명과학 / 기능유전체학 | 과학기술연합대학원대학교 | 2021~2023 |
| 석사 — 의생명과학과 | 아주대학교 의과대학원 | 2017~2019 |
| TOEIC 760 | — | 2019 |

---

##  Publications

> 배재대학교 석사 학위 중 공동 저자로 참여한 논문 목록

- Ufd1 phosphorylation at serine 229 negatively regulates ER-associated degradation *(2019)*
- Histone deacetylase 6 inhibitor tubastatin A attenuates angiotensin II-induced hypertension *(2019)*
- NEDD4-induced degradative ubiquitination of PIP5Kα and breast cancer cell proliferation *(2018)*
- PIP5Kα contributes to Toll-like receptor 2-mediated immune responses in microglial cells *(2017)*

---

<div align="center">

*"단순히 코드를 작성하는 개발자가 아니라,*
*임상 데이터가 어떤 맥락에서 생성되고 어떻게 해석되어야 하는지를 아는 개발자"*

</div>
