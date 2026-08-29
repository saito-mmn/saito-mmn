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

[Repository](https://github.com/saito-mmn/hotel-supply-demand-etl) · [Live Demo](https://saito-mmn.github.io/hotel-supply-demand-etl/)

観光庁・e-Statの宿泊統計を取得・正規化し、品質検証、SQLiteへの格納、分析レポート生成までを一貫して自動化しています。

```text
Source
  ↓
ETL
  ↓
Data Quality
  ↓
SQLite
  ↓
Analytics Report
```

さらに、公式データの更新検知から再取得、DB・レポート再生成、GitHub Pagesへの反映まで自動化しています。

#### Tech Stack

| Area          | Technology                   |
| ------------- | ---------------------------- |
| Data Pipeline | Python                       |
| Database      | SQLite                       |
| Data Quality  | Validation / Automated Tests |
| Automation    | GitHub Actions               |
| Reporting     | HTML / CSS / JavaScript      |
| Hosting       | GitHub Pages                 |



