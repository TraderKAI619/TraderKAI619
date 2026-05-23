# LIU CHUNKAI | Analytics Engineer / Data Analyst

Tokyo, Japan 🇯🇵  
Japanese (JLPT N1) · English (TOEIC 875) · Mandarin Native

---
<details>
<summary>🇯🇵 日本語版はこちら</summary>
  # LIU CHUNKAI | アナリティクスエンジニア / データアナリスト

東京都 🇯🇵  
日本語（JLPT N1）・英語（TOEIC 875）・中国語（ネイティブ）

---

## About Me

東京を拠点に、信頼性の高いデータパイプラインとビジネス意思決定をつなぐ、エンドツーエンドの分析基盤を構築しているアナリティクスエンジニア。

金融分野のバックグラウンドを持ち、日本小売分析や dbt + BigQuery モデリングに関する実務レベルのハンズオン経験あり。

技術的な再現性、ビジネス活用性、運用安定性を重視したアナリティクスワークフロー設計に注力。

AWS Certified Cloud Practitioner ・ ITパスポート

---

# Portfolio Architecture

## Project A — Business Decision Intelligence

日本市場におけるゴールデンウィーク需要分析を目的とした、小売向け分析プラットフォーム。

### 主な取り組み
- 地域別売上 uplift 分析
- カテゴリ別貢献度分析
- 消費税影響分析
- エグゼクティブ向けインサイトダッシュボード
- ビジネス推奨レイヤー構築

### ビジネスコンテキスト
- 約14.6万件の合成売上データを使用
- 全国47都道府県における holiday uplift 分析
- 在庫配置および人員配置に関する運用提案を実施

### 使用技術
Python ・ SQL ・ DuckDB ・ Streamlit

🔗 Live Dashboard  
https://project-a-gw.streamlit.app/

📂 GitHub Repository  
https://github.com/TraderKAI619/project-a-jp-retail-pipeline

---

## Project B — Reliable Incremental Data Platform

再現性と運用安定性を重視して設計した、インクリメンタル型アナリティクスパイプライン。

### 主な取り組み
- Incremental processing
- Idempotent pipeline design
- データ品質検証
- Quarantine workflow
- CI/CD 自動化
- Pipeline observability

### 運用シグナル
- データ品質 pass rate 約95%
- Quarantine ratio を5%未満で維持
- 繰り返し daily run における idempotency を検証
- 7日 rolling window による安定した incremental execution

### 使用技術
Python ・ SQL ・ pytest ・ GitHub Actions

📂 GitHub Repository  
https://github.com/TraderKAI619/incremental-sales-pipeline

---

## Project C — Semantic Trust & Governance Layer

dbt + BigQuery を用いて構築した、trusted metrics と semantic consistency を重視したモダン分析基盤。

### 主な取り組み
- dbt modeling
- Snapshot history tracking
- Reconciliation checks
- Anomaly detection
- Data trust scoring
- Analytics lineage

### Engineering Signals
- staging → intermediate → marts → snapshot のフルレイヤー構成
- dbt models 6件
- automated tests 10件 passing
- PASS / FAIL reconciliation automation を実装

### 使用技術
dbt ・ BigQuery ・ SQL ・ GitHub Actions

📂 GitHub Repository  
https://github.com/TraderKAI619/semantic-metrics-data-trust-platform

---

# Core Strengths

- KPIドリブン分析
- ビジネス視点のストーリーテリング
- Incremental analytics engineering
- Data quality & trust
- 再現性を重視した分析ワークフロー設計
- 日本小売市場ドメイン知識

---

# Links

GitHub  
https://github.com/TraderKAI619

Email  
dataliuchunkai@gmail.com
</details>

## About Me

Analytics Engineer based in Tokyo, building end-to-end analytics systems that connect reliable data pipelines to business decisions.

Background in Finance, with hands-on experience in Japanese retail analytics and dbt + BigQuery modeling.

Focused on building analytics workflows that are technically reproducible, business-oriented, and operationally reliable.

AWS Certified Cloud Practitioner · IT Passport

---

# Portfolio Architecture

## Project A — Business Decision Intelligence

Retail analytics platform focused on Golden Week demand analysis across Japan.

### Key Focus
- Regional sales uplift analysis
- Category contribution analysis
- Consumption tax impact analysis
- Executive-ready insight dashboards
- Business recommendation layer

### Business Context
- ~146K synthetic sales rows
- Holiday uplift analysis across 47 prefectures
- Operational recommendations for inventory and staffing decisions

### Tech
Python · SQL · DuckDB · Streamlit

🔗 Live Dashboard  
https://project-a-gw.streamlit.app/

📂 GitHub Repository  
https://github.com/TraderKAI619/project-a-jp-retail-pipeline

---

## Project B — Reliable Incremental Data Platform

Incremental analytics pipeline designed for reproducible and operationally stable data processing.

### Key Focus
- Incremental processing
- Idempotent pipeline design
- Data quality validation
- Quarantine workflows
- CI/CD automation
- Pipeline observability

### Operational Signals
- ≈95% data quality pass rate
- Quarantine ratio maintained below 5%
- Idempotency verified across repeated daily runs
- 7-day rolling processing window with stable incremental execution

### Tech
Python · SQL · pytest · GitHub Actions

📂 GitHub Repository  
https://github.com/TraderKAI619/incremental-sales-pipeline

---

## Project C — Semantic Trust & Governance Layer

Modern analytics architecture using dbt + BigQuery for trusted metrics and semantic consistency.

### Key Focus
- dbt modeling
- Snapshot history tracking
- Reconciliation checks
- Anomaly detection
- Data trust scoring
- Analytics lineage

### Engineering Signals
- staging → intermediate → marts → snapshot full layer
- 6 dbt models
- 10 automated tests passing
- PASS/FAIL reconciliation automation

### Tech
dbt · BigQuery · SQL · GitHub Actions

📂 GitHub Repository  
https://github.com/TraderKAI619/semantic-metrics-data-trust-platform

---

# Core Strengths

- KPI-driven analytics
- Business-oriented storytelling
- Incremental analytics engineering
- Data quality & trust
- Reproducible analytics workflows
- Japanese retail market domain knowledge

---

# Links

GitHub  
https://github.com/TraderKAI619

Email  
dataliuchunkai@gmail.com 
