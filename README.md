# TraderKAI619 — Data Engineer

Analytics Pipelines · Data Quality · AWS Serverless | Tokyo 🇯🇵  
📧 traderkai0619@gmail.com | 🗣️ JP N1 · EN TOEIC 875 · CH Native

---

## 🚀 Currently
Designing an AWS serverless ETL (S3 → Lambda → Glue → Athena + CloudWatch) PoC.

---

## 💼 Featured Projects

### Japan Reference Data Pipeline
- Single source of truth for **JIS regions**, **JP holidays**, and **consumption tax (SCD2)**.
- **Impact (verifiable):** Freshness < 24h (nightly CI) · DQ tests in CI · Key consistency checks.
- **Tech:** Python · DuckDB · CI/CD  
→ [View Project](https://github.com/TraderKAI619/project-a-jp-retail-pipeline)

### Incremental Sales Pipeline
- **Idempotent** daily ETL (natural key upsert) with **8 automated DQ checks** *(expanding to 10)*.
- **Impact (verifiable):** DQ Pass ≈ **95%** *(±1–2pt, **denominator = Silver**)* · Quarantine system · Reproducible builds.
- **Tech:** Python · DuckDB · pytest · CI/CD  
→ [View Project](https://github.com/TraderKAI619/incremental-sales-pipeline)

### AWS Serverless ETL (PoC – planned)
- Event-driven data lake design with **Bronze/Silver/Gold** layers.
- **Status:** PoC planning & repo scaffolding; will prioritize on request. **Target cost < $1/mo**.
→ Building

---

## 🛠️ Tech Stack

**Data Engineering**: Python · SQL · Pandas · DuckDB · ETL/ELT  
**AWS (hands-on PoC)**: S3 · Lambda · Glue · Athena · CloudWatch  
**DevOps**: GitHub Actions · pytest · Makefile · CI/CD  
**Architecture**: Medallion (Bronze/Silver/Gold) · Data Quality · Idempotency

---

## 📚 Background

- Portfolio: **2 open-source pipelines** (+ 1 planned serverless PoC), CI green & reproducible artifacts.
- Career: Finance B.S. → 2y systematic trading → Data Engineering (2025).
- Languages: Japanese N1 · English TOEIC 875 · Mandarin (native).
- Visa: Working Holiday → Engineer/Humanities (ready to switch with an offer).

# データエンジニア | 東京
分析基盤 · データ品質 · AWS サーバーレス  
📧 traderkai0619@gmail.com | 🗣️ 日本語 N1 · 英語 TOEIC 875 · 中国語 Native

---

## 🚀 現在の取り組み
AWS サーバーレス ETL の PoC 設計中（S3 → Lambda → Glue → Athena + CloudWatch）。

---

## 💼 主なプロジェクト

### 日本向け参照データ基盤
- **JIS 地域コード／国民の祝日／消費税率（SCD2）** の単一情報源。
- **成果（検証可能）**：Freshness < 24h（Nightly CI）・CI 上の DQ テスト・キー整合性検証。
- **技術**：Python · DuckDB · CI/CD  
→ [プロジェクトを見る](https://github.com/TraderKAI619/project-a-jp-retail-pipeline)

### 増分セールスパイプライン
- **冪等性** を保証した日次 ETL（自然鍵 upsert）、**自動 DQ 8 本**（**10 本へ拡充予定**）。
- **成果（検証可能）**：DQ Pass ≈ **95%**（±1–2pt、**母数＝Silver**）・隔離（Quarantine）・再現可能なビルド。
- **技術**：Python · DuckDB · pytest · CI/CD  
→ [プロジェクトを見る](https://github.com/TraderKAI619/incremental-sales-pipeline)

### AWS サーバーレス ETL（PoC／計画中）
- **Bronze/Silver/Gold** 層のイベント駆動データレイク設計。
- **状況**：PoC 企画とリポジトリアウトラインを準備。ご要望があれば優先着手。**目標コスト < $1/月**。  
→ 建設中

---

## 🛠️ 技術スタック
**データエンジニアリング**：Python · SQL · Pandas · DuckDB · ETL/ELT  
**AWS（PoC）**：S3 · Lambda · Glue · Athena · CloudWatch  
**DevOps**：GitHub Actions · pytest · Makefile · CI/CD  
**アーキテクチャ**：Medallion（Bronze/Silver/Gold）· データ品質 · 冪等性

---

## 📚 経歴
- ポートフォリオ：**OSS パイプライン 2 件**（+ サーバーレス PoC 計画中）。CI 緑・再現性あり。
- キャリア：金融学士 → システムトレード 2年 → データエンジニアリング（2025）。  
- 言語：日本語 N1 · 英語 TOEIC 875 · 中国語 Native  
- 在留資格：ワーキングホリデー → 技術・人文知識・国際業務（内定後切替準備可）
