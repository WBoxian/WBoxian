<h1 align="center">Boxian Wen</h1>
<p align="center">Algorithm Engineer focused on Search, Recommendation, Ranking, and Intelligent Backend Systems</p>

<p align="center">
  <a href="https://github.com/WBoxian">
    <img src="https://img.shields.io/badge/GitHub-WBoxian-181717?style=flat-square&logo=github" alt="GitHub" />
  </a>
  <a href="https://wboxian.github.io/">
    <img src="https://img.shields.io/badge/Website-wboxian.github.io-3F4A5A?style=flat-square&logo=googlechrome" alt="Website" />
  </a>
  <a href="mailto:boxian.wen@outlook.com">
    <img src="https://img.shields.io/badge/Email-boxian.wen@outlook.com-B54C2A?style=flat-square&logo=gmail" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/boxian-wen-6b00692b8">
    <img src="https://img.shields.io/badge/LinkedIn-Boxian%20Wen-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  <a href="https://wboxian.github.io/assets/support/wechat.jpg">
    <img src="https://img.shields.io/badge/WeChat-07C160?style=flat-square&logo=wechat&logoColor=white" alt="WeChat" />
  </a>
  <a href="https://wboxian.github.io/assets/support/alipay.jpg">
    <img src="https://img.shields.io/badge/Alipay-1677FF?style=flat-square&logo=alipay&logoColor=white" alt="Alipay" />
  </a>
  <a href="https://wboxian.github.io/assets/support/paypal.png">
    <img src="https://img.shields.io/badge/PayPal-003087?style=flat-square&logo=paypal&logoColor=white" alt="PayPal" />
  </a>
</p>

## 中文

我当前以**算法工程师**为主线，重点聚焦**搜索、推荐、排序、特征工程与智能后端系统**。研究背景主要来自 `UCL` 计算生态学研究型硕士与 `中山大学` 海洋生物学本科训练，并在环境 DNA、转录组、生信分析与 AI 辅助珊瑚评估中积累了分析经验。

- 求职方向：`算法工程师` / `搜索推荐` / `智能后端`
- 并行兴趣：`AI` / `多模态` / `珊瑚保护` / `计算生态学` 全奖博士机会
- 当前代表项目：**Rednote Qilin Search & Recommendation System**

### 技术栈

<p>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /></a>
  <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Vue%203-42B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue 3" /></a>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  <a href="https://redis.io/"><img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" /></a>
  <a href="https://duckdb.org/"><img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" /></a>
</p>
<p>
  <a href="https://faiss.ai/"><img src="https://img.shields.io/badge/Faiss-Vector%20Search-3F4A5A?style=flat-square" alt="Faiss" /></a>
  <a href="https://lightgbm.readthedocs.io/"><img src="https://img.shields.io/badge/LightGBM-LambdaMART-86B817?style=flat-square" alt="LightGBM" /></a>
  <a href="https://xgboost.readthedocs.io/"><img src="https://img.shields.io/badge/XGBoost-LambdaMART-EC6B23?style=flat-square" alt="XGBoost" /></a>
  <a href="https://www.tensorflow.org/recommenders/examples/dcn"><img src="https://img.shields.io/badge/DSSM-Dual%20Tower-425466?style=flat-square" alt="DSSM" /></a>
  <a href="https://arxiv.org/abs/1809.03672"><img src="https://img.shields.io/badge/DIEN-Sequence%20Interest-6B4EFF?style=flat-square" alt="DIEN" /></a>
  <a href="https://www.postgresql.org/docs/current/sql.html"><img src="https://img.shields.io/badge/SQL-Data%20Processing-3F4A5A?style=flat-square" alt="SQL" /></a>
</p>

### 当前重点项目

**Rednote Qilin Search & Recommendation System** · `11/2025 – 05/2026`  
受小红书启发的搜索推荐一体化个人项目，独立完成数据预处理、特征工程、多路召回、粗排、精排、线上部署与在线服务的全流程闭环。

- 技术栈：`Python` `FastAPI` `Vue3` `TypeScript` `Redis` `DuckDB` `Faiss` `LightGBM` `XGBoost` `DSSM` `DIEN`
- 数据规模：约 `200 万` 笔记、`1.5 万` 用户、`10 万` 推荐样本、`5 万` 搜索样本
- 模型架构：`DSSM 双塔 + Faiss`、`Swing`、`UserCF` 多路召回；粗排采用 `LambdaMART (LightGBM / XGBoost)`；精排采用 `DIEN`
- 在线服务：基于 `FastAPI + Redis`，支持实时行为写回与搜推联动，线上延迟稳定在 `~150ms`
- 离线指标：
  - 搜索侧：`HitRate@500 = 0.88`，`Recall@500 = 0.65`，`MRR@100 = 0.11`，`NDCG@10 = 0.69`，`AUC = 0.77`
  - 推荐侧：`HitRate@500 = 0.99`，`Recall@500 = 0.99`，`NDCG@10 = 0.87`，`AUC = 0.84`

[Repository](https://github.com/WBoxian/Rednote-Qilin-Search-Rec-System)

---

## English

I am primarily targeting **algorithm engineering** roles, with a focus on **search, recommendation, ranking, feature engineering, and intelligent backend systems**. My background combines a research master's in Computational Ecology at `UCL` with marine biology training at `Sun Yat-sen University`, along with hands-on work in environmental DNA, transcriptomics, bioinformatics, and AI-assisted coral analysis.

- Main direction: `Algorithm Engineer` / `Search & Recommendation` / `Intelligent Backend`
- Parallel interest: fully funded PhD opportunities in `AI`, `multimodal learning`, `coral conservation`, and `computational ecology`
- Current flagship build: **Rednote Qilin Search & Recommendation System**

### Tech Stack

<p>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" /></a>
  <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Vue%203-42B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue 3" /></a>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  <a href="https://redis.io/"><img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" /></a>
  <a href="https://duckdb.org/"><img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB" /></a>
</p>
<p>
  <a href="https://faiss.ai/"><img src="https://img.shields.io/badge/Faiss-Vector%20Search-3F4A5A?style=flat-square" alt="Faiss" /></a>
  <a href="https://lightgbm.readthedocs.io/"><img src="https://img.shields.io/badge/LightGBM-LambdaMART-86B817?style=flat-square" alt="LightGBM" /></a>
  <a href="https://xgboost.readthedocs.io/"><img src="https://img.shields.io/badge/XGBoost-LambdaMART-EC6B23?style=flat-square" alt="XGBoost" /></a>
  <a href="https://www.tensorflow.org/recommenders/examples/dcn"><img src="https://img.shields.io/badge/DSSM-Dual%20Tower-425466?style=flat-square" alt="DSSM" /></a>
  <a href="https://arxiv.org/abs/1809.03672"><img src="https://img.shields.io/badge/DIEN-Sequence%20Interest-6B4EFF?style=flat-square" alt="DIEN" /></a>
  <a href="https://www.postgresql.org/docs/current/sql.html"><img src="https://img.shields.io/badge/SQL-Data%20Processing-3F4A5A?style=flat-square" alt="SQL" /></a>
</p>

### Featured Project

**Rednote Qilin Search & Recommendation System** · `11/2025 – 05/2026`  
An integrated search-and-recommendation build inspired by Xiaohongshu, covering data preprocessing, feature engineering, multi-channel retrieval, coarse ranking, final ranking, deployment, and online serving.

- Stack: `Python` `FastAPI` `Vue3` `TypeScript` `Redis` `DuckDB` `Faiss` `LightGBM` `XGBoost` `DSSM` `DIEN`
- Data scale: about `2M` notes, `15k` users, `100k` recommendation samples, and `50k` search samples
- Modeling: `DSSM dual tower + Faiss`, `Swing`, and `UserCF` for retrieval; `LambdaMART (LightGBM / XGBoost)` for coarse ranking; `DIEN` for sequence-aware final ranking
- Online serving: `FastAPI + Redis`, with real-time behavior writeback and linked search-recommendation serving, stable latency around `~150ms`
- Offline metrics:
  - Search: `HitRate@500 = 0.88`, `Recall@500 = 0.65`, `MRR@100 = 0.11`, `NDCG@10 = 0.69`, `AUC = 0.77`
  - Recommendation: `HitRate@500 = 0.99`, `Recall@500 = 0.99`, `NDCG@10 = 0.87`, `AUC = 0.84`

[Repository](https://github.com/WBoxian/Rednote-Qilin-Search-Rec-System)
