## Who I am

金融・不動産領域の実務経験をバックグラウンドとして、データエンジニアリング・データ分析に取り組んでいます。
銀行での担保評価、FASでの資産評価レビュー、金融データプロダクトのETL・運用自動化を経験してきました。

評価・分析業務経験を通じて、説明可能な意思決定には、その前提となるデータの収集・構造化・品質管理が不可欠だと感じ、データエンジニアリング領域へ軸足を移しました。

現在は、曖昧な業務仕様や未整備なデータを構造化し、再現可能なデータ処理・分析基盤へ落とし込むことをテーマに個人開発を行っています。

業務課題からデータ処理を設計することと、データや技術から新しい活用可能性を見つけることの両方を重視し、最終的に意思決定や業務価値へ接続することを意識しています。

---

## Featured Project

### Hotel Supply & Demand ETL

**ホテル担保評価の実務課題を題材にした、公的統計の自動更新型データパイプライン**

[Repository](https://github.com/saito-mmn/hotel-supply-demand-etl) · [Github Pages(静的レポート)](https://saito-mmn.github.io/hotel-supply-demand-etl/)・[Tableau Dashboard(動的レポート)](https://public.tableau.com/views/_17880794228750/1?:language=ja-JP&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

#### Why

銀行でホテル担保評価を担当する中で、宿泊需要や客室稼働率などの市場データを継続的に確認する一方、公的統計が複数のExcelに分散し、都度収集・加工する負荷を感じていました。

そこで、**分析のたびにデータを集め直すのではなく、継続的に更新・再利用できる仕組み**として実装しました。

#### What

観光庁・e-Statの宿泊統計を取得・正規化し、全国・都道府県・市区町村の宿泊需要、客室稼働率、外国人比率、施設数などを継続的に確認できるデータ基盤とMarket Reportを生成します。

担保価値を自動判定するものではなく、**評価担当者が市場環境を確認するための一次資料**を提供します。

#### How

```text
Source → ETL → Data Quality → SQLite → Analytics Report(Github Pages/Tableau)
```

公式データの更新・訂正検知、データ来歴管理、品質検証、安全なDB・レポート更新、テスト、GitHub Actionsによる自動更新・デプロイまで実装しています。

#### Tech Stack

`Python` · `SQLite` · `pytest` · `GitHub Actions` · `HTML / CSS / JavaScript` · `GitHub Pages`・`Tableau`



