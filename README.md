<div align="center">

<a href="https://github.com/abhinavharbola">
  <img src="https://readme-typing-svg.demolab.com?font=Roboto+Mono&weight=600&size=22&pause=1200&color=3FB950&center=true&vCenter=true&width=900&lines=AI+%2F+ML+Engineer;Applied+ML+%7C+MLOps+%7C+RAG+%7C+Causal+Inference" alt="Typing SVG" />
</a>

<p>
AI/ML Engineer focused on systems that hold up in production: evaluation before modeling, fail-closed guardrails, and monitoring for drift and degradation over time.
</p>

<p><b>Open to AI / ML / Data Science Engineer roles, remote-friendly.</b></p>

<p>
  <a href="mailto:abhinavdaharbola@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" /></a>
  <a href="https://linkedin.com/in/abhinavharbola"><img src="https://skillicons.dev/icons?i=linkedin" /></a>
  <a href="https://github.com/abhinavharbola"><img src="https://skillicons.dev/icons?i=github" /></a>
</p>

</div>

---

### Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-2A6E3F?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-9146FF?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B5AE4?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

</div>

---

### Engineering principles

Each claim below is backed by a specific repo, not asserted in the abstract.

- **Evaluation precedes modeling.** [`causal-inference-lab`](https://github.com/abhinavharbola/causal-inference-lab) builds and unit-tests its minimum-detectable-effect and power-analysis harness before any CATE model exists; [`recsys-bench`](https://github.com/abhinavharbola/recsys-bench) builds and unit-tests its Recall/NDCG/MAP harness before any of its five recommenders are trained. Every approach downstream is scored under identical conditions.
- **Guardrails fail closed by default.** [`kubernetes-gated-rag`](https://github.com/abhinavharbola/kubernetes-gated-rag)'s safety and topic classifiers block the request on any classifier error, with the one deliberate exception (a reranking fallback, not a safety check) documented in the repo rather than left implicit.
- **Promotion and rollback decisions are statistically gated, not point-estimate driven.** [`credit-risk-autopilot`](https://github.com/abhinavharbola/credit-risk-autopilot) requires a challenger to clear tolerance, dominance, and significance gates before promotion, and requires a bootstrap-CI-confirmed drop, not a raw point estimate, before rolling one back.
- **Known failure modes are documented directly in each project, not left implicit.** [`competitive-intelligence-agent`](https://github.com/abhinavharbola/competitive-intelligence-agent) states exactly when its free-tier quota gets exhausted and how the system degrades; [`retailcast`](https://github.com/abhinavharbola/retailcast) states that its LLM-output grounding check is regex-based and can miss paraphrased claims.

Full project list with descriptions: pinned repos below.

---

<div align="center">

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=abhinavharbola&theme=github_dark&hide_border=true&layout=compact" height="165" />
<img src="https://streak-stats.demolab.com/?user=abhinavharbola&theme=github-dark&hide_border=true" height="165" />

</div>
