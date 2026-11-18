<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Juyong%20Choi&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Medical%20AI%20Engineer&descSize=18&descAlignY=58&animation=fadeIn" width="100%" />

<div align="center">

<a href="https://github.com/cju9390">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=600&size=20&duration=3000&pause=800&color=2C5364&center=true&vCenter=true&width=600&lines=%EC%83%9D%EB%AA%85%EA%B3%BC%ED%95%99%EC%97%90%EC%84%9C+%EC%98%A8+%EC%9D%98%EB%A3%8C+AI+%EA%B0%9C%EB%B0%9C%EC%9E%90" alt="Typing SVG" />
</a>

<br/>

[![Email](https://img.shields.io/badge/Email-cju9390@naver.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cju9390@naver.com)

</div>

<br/>

## About

```yaml
role:       Medical AI Engineer
background:
  - 한국생명공학연구원 대사제어연구센터 4년 6개월 (간 대사·섬유화 연구)
  - 건양대병원 미래융합교육원 바이오메디컬 AI 과정 (2025.12 – 2026.07)
```

<br/>

## Projects

<sub>바이오메디컬 AI 과정 및 개인 학습으로 진행한 프로젝트입니다.</sub>

<table>
<tr>
<td width="33%" valign="top">

### [WSI Kidney Pathology](https://github.com/cju9390/wsi-kidney-pathology)
<sub>교육 과정 · 팀 프로젝트 (4인)</sub>

신장 생검 WSI에서 병리 지표를 ABMIL로 정량예측하고, PACS 연동 병리과 뷰어에 Attention 히트맵 제공

`ABMIL` `phikon-v2` `Hibou-L` `OpenSlide`

**세뇨관 위축 Spearman ρ 0.74**

</td>
<td width="33%" valign="top">

### [AKI Early Prediction](https://github.com/cju9390/kidn_proj)
<sub>교육 과정 · 팀 프로젝트 (4인, 팀장)</sub>

MIMIC-IV 41,576건으로 ICU 환자의 AKI 발생을 48시간 조기예측

`XGBoost` `SHAP` `PostgreSQL` `FastAPI`

**AUROC 0.9753 / AUPRC 0.9611**

</td>
<td width="33%" valign="top">

### [Medical Term RAG (KO→EN)](https://github.com/cju9390/medical-term-rag-ko-en)
<sub>개인 프로젝트</sub>

한글 질의를 표준 영문 의학용어로 매핑해 PubMed·질병관리청 문서를 검색·응답

`Ollama` `Chroma` `sentence-transformers`

**Recall@3 33.3% → 100% (검색 단계)**

</td>
</tr>
</table>

<details>
<summary><b>Side Projects</b></summary>
<br/>

- [**MBTI × RPG Job Predictor**](https://github.com/cju9390/project_mbti_job_game.io) — 60문항 설문 → XGBoost MBTI 예측 → RPG 직업·스탯·파티 추천 웹앱
- [**Team File Server**](https://github.com/cju9390/team-file-server) — FastAPI + WebSocket 팀 공유 파일 서버, Cloudflare Tunnel로 외부 공개

</details>

<br/>

## Tech Stack

<div align="center">

| Area | Stack |
|:--:|:--|
| **Pathology AI** | OpenSlide · ABMIL · phikon-v2 · Hibou-L · DINOv2 |
| **LLM / RAG** | Ollama · Chroma · sentence-transformers · BioBERT |
| **Clinical ML** | XGBoost · SHAP · Optuna · scikit-learn |
| **Serving** | FastAPI · WebSocket · DeepZoom · wsidicomizer (SVS→DICOM) |

</div>

<br/>

## Publications

- **Cellular heterogeneity and plasticity during NAFLD progression** — *Front Mol Biosci*, 2023 · `co-first author`
- 공저 4편 — *Biochem J*, *Pharmacol Res*, *J Cell Mol Med*, *Cell Signal* (2017–2019)

<br/>

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" />
