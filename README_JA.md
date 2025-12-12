# 職務経歴

[English](./README.md) / Japanese

### 坂井 賢世 (SAKAI, Kensei)

Github: https://github.com/kensei18

LinkedIn: https://www.linkedin.com/in/kensei-sakai/

言語: 日本語(ネイティブ) / 英語(B2)

## スキルセット

##### 言語/フレームワーク

Go / TypeScript(Express.js, React, Vue.js) / Ruby(Ruby on Rails) / Python(FastAPI) / HTML / CSS

##### データベース

MySQL / MongoDB / PostgreSQL / DynamoDB

##### インターフェース

gRPC (Protocol Buffers) / GraphQL / REST

##### 仮想化技術

Docker / lima

##### クラウド

AWS (EC2, S3, DocumentDB, CloudFront, ECR, ECS, Athena, SQS, SES, Lambda, DynamoDB, Route53, CloudFormation, CloudWatchLogs, API Gateway, StepFunctions) / GCP (Firebase, Cloud Run, Cloud Build, CloudSQL, Cloud Storage, Cloud PubSub, Cloud Logging, Big Query)

##### バージョン管理

Github / Gitlab

##### CI/CD

Github Actions / CircleCI / Gitlab CI

##### その他

Terraform / Algolia / Datadog / Ory (Kratos, Hydra, Oathkeeper)

## 職務経歴

### 株式会社ティアフォー (TIER IV, Inc.) (2023/12 - 現在) - ソフトウェアエンジニア

株式会社ティアフォーは、「自動運転の民主化」を目指す日本発のディープテックスタートアップである。オープンソースの自動運転ソフトウェア「Autoware」を開発・公開し、自動運転システムの開発・構築を加速させる「Web.Auto」を提供している。

Authチームのメンバーとして、Web.Auto全体で使用される基盤系のマイクロサービスの開発に従事。具体的には、認証・認可の基盤に加え、契約・利用量計測・通知の基盤の開発と運用を担当。

#### Web.Autoの認可基盤のパフォーマンス改善

##### 概要

Web.Auto が将来的に大規模にスケールしても耐えうる認可機構の実現のために、トークン払い出しの仕組みの見直しとパフォーマンス改善を実施

##### 使用技術

Go, Python, TypeScript, k6, Datadog

##### 担当業務

- 要件定義
- ボトルネックの特定
- パフォーマンス改善案の検討・実施
- パフォーマンス改善の効果測定

#### Web.Autoアプリケーションの利用量計測マイクロサービスの新規開発

##### 概要

ティアフォーの自動運転支援システム「Web.Auto」で提供される各アプリケーションの顧客の利用量を計測するマイクロサービスの新規開発

##### 使用技術

Go, Python, TypeScript, AWS (Lambda, DynamoDB, ECS, Route53, SQS, SES, CloudFormation, CloudWatchLogs, API Gateway), Datadog, Slack API

##### 担当業務

- ドメイン設計
- マイクロサービスの実装
- 開発チームのリード
- マイクロサービスを利用する他チームとのコミュニケーションのリード

#### Web.Autoアプリケーションの通知マイクロサービスの新規開発

##### 概要

Web.Autoで提供される各アプリケーションがさまざまなチャネルを通じて顧客に通知を送信できる通知マイクロサービスの新規開発

##### 使用技術

Go, AWS (Lambda, DynamoDB, Route53, SQS, CloudFormation, CloudWatchLogs, API Gateway, StepFunctions), Datadog

##### 担当業務

- 非機能要件定義
- システム設計
- ドメイン設計
- マイクロサービスの実装
- 開発チームのリード
- マイクロサービスを利用する他チームとのコミュニケーションのリード
- リリース
- 保守運用

#### Web.Autoの認証基盤・認可基盤・契約基盤の各マイクロサービスの運用

##### 概要

Web.Autoで利用される認証基盤・認可基盤・契約基盤の各マイクロサービスの運用

##### 使用技術

Go, PostgreSQL, AWS (Lambda, DynamoDB, ECS, Route53, SQS, CloudFormation, CloudWatchLogs, API Gateway), Ory (Kratos, Hydra, Oathkeeper)

##### 担当業務

- モニタリング、オンコール対応
- 他チームからの認証・認可・契約に関する問い合わせ・相談の対応
- 機能追加、パフォーマンス改善

### 株式会社マネーフォワード (2021/09 - 2023/11) - ソフトウェアエンジニア

#### Apollo Server + Next.js のファクタリングサービスの社内ユーザー用アプリケーションの開発

##### 概要

二社間ファクタリング事業を行う子会社の株式会社 BizForward で、社内ユーザーが案件や支払いを管理するための社内向けアプリケーションの開発

##### 使用技術

TypeScript(Node.js, Next.js), Go, GCP(Cloud Run, Firebase, CloudSQL, Cloud Storage, Cloud PubSub, Cloud Logging, Big Query), GraphQL(Apollo), Terraform, Docker, Sentry

##### 担当業務

- 新機能の要件定義・全体設計・テーブル設計・実装・リリース・インフラ構成・保守運用
- 既存機能のリファクタリング及びテスト追加
- サーバーのログ整備

#### Ruby on Rails の会計アプリケーションのマイクロサービス開発

##### 概要

Ruby on Rails アプリケーション『マネーフォワード クラウド会計』のマイクロサービス化プロジェクトにおいて、データ量の大きい仕訳情報に関するマイクロサービスプロジェクトでの開発

##### 使用技術

Ruby on Rails, Go, MySQL, Docker, gRPC

##### 担当業務

- Ruby on Rails のマイクロサービスクライアントの開発
- 専用のリグレッションテストツールの開発
- マイクロサービスに切り替えるためのテスト設計・検証・実施
- Go を基盤としたマイクロサービスの開発
- Intel Mac/M1 Mac 用の Docker on lima on Mac の開発環境基盤の開発・運用

### 株式会社スペースリー (2020/06 - 2021/09) - ソフトウェアエンジニア

#### VR 空間での家具配置機能の開発

##### 概要

360° パノラマ VR 空間の中で、自動またはユーザーの手動により実際に販売されている家具や家電製品などを配置し、部屋のコーディネートを自由に行うことができる『AI 空間設計』の新規開発

##### 使用技術

Python, FastAPI, A-Frame, Vue.js, Ruby on Rails, MongoDB, MySQL, AWS(EC2, S3, DocumentDB, CloudFront, ECR, ECS, SQS), Github Actions, Docker, Algolia

##### 担当業務

- A-Frame + Vue.js での VR 空間/家具配置機能の設計・開発・運用
- FastAPI + MongoDB の家具情報アプリケーションの設計・開発・運用
- S3 に配置した 3D ファイルのアクセス制限の設計・実装
- SQS を用いた画像処理アプリケーションとの非同期通信の実装・運用
- FastAPI アプリケーションのパフォーマンス調査・対応
- FastAPI + MongoDB アプリケーションの Algolia への機能・データの移管

#### VR を用いた不動産物件管理サービスの設計・開発・保守・改修

##### 概要

Ruby on Rails / Vue.js / React で構成された VR 不動産物件管理アプリケーションの保守・改修・機能開発

##### 使用技術

Ruby on Rails, JavaScript, Vue.js, jQuery, MySQL, AWS(EC2, S3)

##### 担当業務

- Ruby on Rails アプリケーションのリファクタリング及びテスト追加
- SPA 画面の React から Vue.js へのリプレイス開発
- Ruby on Rails アプリケーションのパフォーマンス改善
- 会社 HP の改修

### ソニー株式会社 (2018/04 - 2019/12) - 管理会計/財務会計

#### 経営管理 - 放送機器事業

##### 概要

放送機器事業の事業管理として、4 つのカテゴリーの管理会計・サプライチェーン管理を担当。事業単位で短期・中長期での会計情報を関係者・マネジメントに報告すると同時に、管理会計の視点から事業の方向性を決めるサポート業務

##### 担当業務

- 月次実績・フォーキャスト PL 作成
- プロダクトの生涯利益予測作成
- プロダクトの生産販売管理
- 中期計画・年間バジェット作成
- 各生産拠点・販売会社との取引価格調整

#### 経理 - スマートフォン事業

##### 概要

モバイル事業の経理として、債権債務の処理・管理

##### 担当業務

- 月次決算処理
- 海外自社工場のインボイス電子化

## 学歴

- 東京大学 教育学部 総合教育科学科 身体教育学コース（理科一類）
  - 2012/04 - 2018/03

## その他の活動

- 外科医療教育支援アプリケーションの開発
  - Go, TypeScript, React, PostgreSQL, GraphQL, Docker, GCP(Firebase / Cloud Run / Cloud SQL / Cloud Build)
  - 会社設立
  - 国際特許取得済
- ソフトウェアエンジニアリングの基礎学習
  - 2020/01 - 2020/06
