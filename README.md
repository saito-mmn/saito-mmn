## Who I am

金融・不動産領域の実務経験をバックグラウンドとして、データエンジニアリング・データ分析に取り組んでいます。
銀行での担保評価、FASでの資産評価レビュー、金融データプロダクトのETL・運用自動化を経験してきました。

評価・分析業務経験を通じて、説明可能な意思決定には、その前提となるデータの収集・構造化・品質管理が不可欠だと感じ、データエンジニアリング領域へ軸足を移しました。

現在は、曖昧な業務仕様や未整備なデータを構造化し、再現可能なデータ処理・分析基盤へ落とし込むことをテーマに個人開発を行っています。

業務課題からデータ処理を設計することと、データや技術から新しい活用可能性を見つけることの両方を重視し、最終的に意思決定や業務価値へ接続することを意識しています。

---

## Portfolio

金融・不動産の実務課題を起点に、データ取得・ETL・品質管理・DB設計・分析・運用までを
再現可能な仕組みにすることをテーマに開発しています。

詳細は各プロジェクトのREADMEをご参照ください。

| Project | Output | Why | What | How | Tech Stack |
|---|---|---|---|---|---|
| **Hotel Supply & Demand ETL**<br>宿泊市場データ基盤<br>[Repository](https://github.com/saito-mmn/hotel-supply-demand-etl) | [GitHub Pages](https://saito-mmn.github.io/hotel-supply-demand-etl/) / [Tableau Public](https://public.tableau.com/views/_17880794228750/1?:language=ja-JP&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) | ホテル担保評価で、公的統計の収集・加工を毎回手作業で行う負荷があった | 観光庁・e-Statの統計を継続的に取得・正規化し、市場分析レポートを生成 | Source → ETL → Data Quality → SQLite → Report。更新・訂正検知、来歴管理、品質検証、CI/CDまで自動化 | Python / SQLite / pytest / GitHub Actions / HTML / CSS / JavaScript / Tableau |
| **Investment Monitoring Data Platform** `WIP`<br>投資判断支援データ基盤・Webアプリ<br>Repository: Private | Public Preview 準備中 | 投資判断に必要な市場・財務データと判断根拠が分散し、継続的な観測・検証が難しい | 戦略・テーマ・銘柄・市場データ・財務データを一元管理し、投資判断を再現可能にする | API → ETL → Data Quality → DB → Web。データ来歴、冪等更新、日次処理、バックアップ・復旧を設計 | Python / FastAPI / SQLite / GCS / GitHub Actions / Next.js / TypeScript |



