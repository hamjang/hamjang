<div align="center">

# 👋 안녕하세요, 함승훈입니다

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=70A5FD&center=true&vCenter=true&width=480&lines=AI+Engineer+%26+Data+Scientist;GraphRAG+%7C+Knowledge+Graph+%7C+Ontology;From+Technology+to+Real+Value)](https://git.io/typing-svg)

[![GitHub followers](https://img.shields.io/github/followers/hamjang?logo=github&style=for-the-badge&color=0891b2&labelColor=1c1917)](https://github.com/hamjang)
[![GitHub User's stars](https://img.shields.io/github/stars/hamjang?style=for-the-badge&logo=github&color=0891b2&labelColor=1c1917)](https://github.com/hamjang)
[![Profile Views](https://komarev.com/ghpvc/?username=hamjang&style=for-the-badge&color=blueviolet)](https://github.com/hamjang)

> "AI Engineer는 단순히 모델을 만드는 것을 넘어, 기술의 가능성을 현실의 가치로 변환하는 역할이라 생각합니다."

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/sql-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![GraphRAG](https://img.shields.io/badge/GraphRAG-FF4B4B?style=for-the-badge)
![Claude](https://img.shields.io/badge/Claude-d97706?style=for-the-badge&logo=anthropic&logoColor=white)

*새로운 기술을 탐구하고, 동료와 소통하며 프로젝트의 완성도를 높입니다* 📈✨

</div>

---

## 🚀 Key Projects

### 🧠 [OntoGraphRAG-CoT](https://github.com/hamjang/OntoGraphRAG-CoT)
**반도체 SCM 온톨로지 기반의 GraphRAG 추론 모델**

*   **설명**: 반도체 산업 특화 SCM 온톨로지 설계 및 지식 그래프 구축 활동 수행.
*   **핵심 기술**: Chain-of-Thought(CoT) 프롬프팅 기술을 GraphRAG에 결합하여 복잡한 다단계 추론 성능 극대화.
*   **성과**: 기존 VectorRAG 대비 성능 **171% 향상**, **EM(Exact Match) 점수 0.780** 기록.

### 📑 [TriLens: PDF Table-to-Triplet Extractor](https://github.com/hamjang/OCR-Triplet-Extractor)
**비정형 PDF 문서에서 온톨로지 기반 지식 그래프 자동 구축**

*   **설명**: PDF 문서 내 표(Table) 데이터를 정밀하게 인식하고, 온톨로지 규칙을 준수하는 **트리플렛(Subject-Predicate-Object)**을 자동 추출하여 지식 그래프 구축을 지원하는 파이프라인.
*   **핵심 기술**: 
    *   **구조 보존형 OCR**: PyMuPDF를 활용하여 PDF 표를 LLM 친화적인 Markdown 형식으로 변환
    *   **온톨로지 기반 필터링**: GPT-4o-mini를 통한 2단계 데이터 분류(Triage)로 추출 효율성 극대화
    *   **정밀 트리플렛 추출**: 반도체 SCM 온톨로지(6개 노드 타입, 4개 관계 타입)를 엄격히 준수하는 GPT-4o 기반 지식 추출
*   **성과**: 636개 트리플렛 추출, **온톨로지 준수율 90.3%** 달성. 기업-제품(`provide`), 기업-국가(`locationIn`) 등 핵심 관계에서 90% 이상의 정확도 기록.

### 📉 [간헐적 수요 제품을 위한 수요 예측 모델 비교 분석](https://github.com/hamjang/Intermittent-Demand-Optimiation)
**유통 산업의 불규칙한 수요 패턴 예측 및 모델 최적화 연구**

*   **설명**: 통계적 기법(SBA), 머신러닝(XGBoost, LightGBM), 딥러닝(LSTM)을 활용하여 간헐적 수요 제품의 패턴을 분석하고 최적의 예측 모델을 식별하는 연구.
*   **핵심 기술**: **ADI(평균 수요 간격)** 및 **CV²(변동계수)** 지표를 활용한 수요 패턴 분류와 Lag/Rolling 피처 엔지니어링을 통한 시계열 예측 성능 극대화.
*   **성과**: 제품별 수요 특성에 기반한 모델 선정 기준을 수립하여, 단일 모델 적용 대비 재고 관리 효율성을 높일 수 있는 실증적 근거 제시.

### 👥 [산업 맞춤형 RFM 가중치 모델](https://github.com/hamjang/Industry-Specific-RFM-Weighting)
**도메인 특성을 반영한 전략적 고객 세분화(Customer Segmentation)**

*   **설명**: **AHP(Analytic Hierarchy Process)**를 기반으로 산업별 특성을 반영한 RFM 가중치를 산출하여 고객 분류의 정확도 제고.
*   **핵심 기술**: 도메인 데이터 분석을 통해 Recency, Frequency, Monetary의 최적 가중치를 도출하여 마케팅 효율 최적화.
*   **성과**: 기존 RFM 가중치 모델 대비 군집 품질(실루엣 계수) 약 **5% 향상** 및 군집 간 변별력 개선 (**0.535 → 0.562**)

---

## 📝 학술 및 대외 활동

*   **HICSS-59 발표** (Maui, Hawaii) _(2026.01)_
    *   주제: 도메인 온톨로지 기반 지식 그래프 및 QA 모델 연구 성과 발표

---

## 📈 Contribution Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=hamjang&theme=tokyo-night&hide_border=true&area=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🐍 Contribution Snake

<div align="center">

![Snake animation](https://raw.githubusercontent.com/hamjang/hamjang/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 📫 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hamjang)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seunghun5321@gmail.com)

</div>

---

## 🎯 Current Focus

```text
🧠 Research      GraphRAG, Knowledge Graph, Ontology
🔭 Side project  archcraft (Multi-Agent Model Research Pipeline)
💬 Ask me about  RAG, LLM, Data Science
⚡ Fun fact      HICSS-59 발표 (Maui, Hawaii)
```

---

<div align="center">

### 💡 Random Dev Quote

[![Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)](https://github.com/piyushsuthar/github-readme-quotes)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling"/>

**기술의 가능성을 현실의 가치로.**

</div>
