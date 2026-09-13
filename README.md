## Who I am

金融・不動産領域の実務経験をバックグラウンドに、データエンジニアリングに取り組んでいます。

- **キャリアの背景**: 銀行の担保評価やFASでの資産評価レビューを通じ、「説明可能な意思決定にはデータの収集・構造化・品質管理が不可欠」と痛感し、データエンジニアリングへシフト。

- **現在のテーマ**: 曖昧な業務仕様や未整備データを構造化し、再現可能なデータ処理・分析基盤へ落とし込む個人開発。

---

## Portfolio

実務で感じた課題を起点に、データ取得・ETL・品質管理・DB設計・分析・運用までを一貫して扱うプロジェクトを開発しています。

詳細は各プロジェクトのREADMEをご参照ください。

| Project | Output | Why | What | How | Tech Stack |
|---|---|---|---|---|---|
| **Hotel Supply & Demand ETL**<br>宿泊市場データ基盤<br>[Repository](https://github.com/saito-mmn/hotel-supply-demand-etl) | [GitHub Pages](https://saito-mmn.github.io/hotel-supply-demand-etl/) / [Tableau Public](https://public.tableau.com/views/_17880794228750/1?:language=ja-JP&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) | ホテル担保評価で、公的統計の収集・加工を毎回手作業で行う負荷があった | 観光庁・e-Statの統計を継続的に取得・正規化し、市場分析レポートを生成 | Source → ETL → Data Quality → SQLite → Report。更新・訂正検知、来歴管理、品質検証、CI/CDまで自動化 | Python / SQLite / pytest / GitHub Actions / HTML / CSS / JavaScript / Tableau |
| **Investment Monitoring Data Platform** `WIP`<br>投資判断支援データ基盤・Webアプリ<br>Repository: Private | Public Preview 準備中 | 投資判断に必要な市場・財務データと判断根拠が分散し、継続的な観測・検証が難しい | 戦略・テーマ・銘柄・市場データ・財務データを一元管理し、投資判断を再現可能にする | API → ETL → Data Quality → DB → Web。データ来歴、冪等更新、日次処理、バックアップ・復旧を設計 | Python / FastAPI / SQLite / GCS / GitHub Actions / Next.js / TypeScript |



