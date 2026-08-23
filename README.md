## Who I am

金融・不動産領域の実務経験をバックグラウンドとして、データエンジニアリング・データ分析に取り組んでいます。

銀行での不動産ファイナンス・担保評価、FASでの不動産・動産評価レビュー、金融データプロダクトのETL・運用自動化を経験してきました。

現在は、**業務上の曖昧な仕様や未整備なデータを構造化し、再現可能なデータ処理・分析基盤へ落とし込むこと**をテーマに個人開発を行っています。

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



