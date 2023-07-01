# 職務経歴書

## 基本情報

| 属性     | 値                                 |
| -------- | ---------------------------------- |
| 名前     | 渡邉 展夢　(Watanabe Hiromu)       |
| 生年月   | 1998/07/29                         |
| 居住地   | 福岡県                             |
| 最終学歴 | 純真学園大学 保健医療部 医療工学科 |

---

## GitHub

<p>
<a href="https://github.com/Hiromu-Watanabe" target="_blank"><img alt="Github" src="https://img.shields.io/badge/Hiromu Watanabe-%2312100E.svg?&style=flat-square&logo=Github&logoColor=white" /></a>
<a href="https://twitter.com/tenten0166" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/@tenten0166-%231DA1F2.svg?&style=flat-square&logo=twitter&logoColor=white" /></a>
</p>

---

## スキル

- JavaScript / TypeScript + Vue.js でのフロントエンド開発
- Spring Boot でのバックエンド開発
- 保守・再利用性を意識したコーディング

---

## 技術スタック

### 言語

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=Java&logoColor=white" />
</p>

### フレームワーク・その他

<p>
<img alt="Vue" src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
  <img alt="GraphQL" src="https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=Vite&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="AWS" src="https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

---

## 職務経歴詳細

### 株式会社 NVC（2021/4〜現在）

受託開発の会社で、新卒未経験で入社し現在 3 年目。<br>
入社してから 4 つのプロジェクトで開発に従事。

<br>

### **【プロジェクト一覧】**

### **プロ野球ホーム球場の VIP 席 Web 予約サイト刷新（2022/08〜現在）**

<br>

**概要**

某プロ野球チームホーム球場における VIP 席の Web 予約サイト刷新プロジェクト<br/>
予約機能（来場人数, 駐車台数, 料理の事前注文などの登録）、請求関連の機能（請求書や会計明細書のダウンロード）、ログイン・ユーザー情報の確認・変更（メールアドレスやパスワードの変更）などの機能がある Web サイト<br/>
2023/11 月のプロ野球シーズンオフにリリース予定

<br>

**プロダクトが属する業界**

- スポーツ業界

**チーム編成**

私は開発者の 1 メンバーとして参画しました。

- PM 1 人
- 開発者 3 人

**役割**

- 設計 / 実装 / テスト
- Web 予約システム全般の開発とデータ連携(ETL ツール)実装を担当

**言語**

  <p>
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  </p>

**フレームワーク・その他**

<p>
  <img alt="Vue" src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=Vue.js&logoColor=white" />
  <img alt="tailwindcss" src="https://img.shields.io/badge/-tailwindcss-black?style=flat-square&logo=tailwindcss&logoColor=#1cbcbc" />
  <img alt="awsamplify" src="https://img.shields.io/badge/-AWS Amplify-FF9900?style=flat-square&logo=awsamplify&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
</p>

**チームの特徴・課題**

- プロジェクトの初期段階でモック開発を担当した別会社からのドキュメントが不十分であり、ソースコードを解析しながらシステムの構成を理解する必要があった

- AWS Amplify の利用経験者がチームにおらず、チュートリアルレベルの情報しかない Web 上の情報を頼りに開発を進める必要があった（公式のドキュメントも更新されていないものが結構あった）

**自身が工夫したこと**

- ドキュメントが不足していたため、情報が不足していると感じた部分はドキュメントを作成しチームに共有することで、チーム全体の業務効率化や生産性向上に貢献した。以下 2 つは具体的な例
  - アイコンとして使用していた Web フォントについて追加・変更方法
  - デプロイ作業の各種手順
- 処理時間の短縮
  - ログイン処理に 約 2 秒かかっていたため、処理を見直し約 1 秒まで短縮した
  - GraqhQL で必要ない項目まで取得していたクエリを必要最小限のクエリに変更し、約 0.5 秒データ取得処理時間が短縮した。
- コメントを丁寧に残す
  - 関数には JSDoc の形式で丁寧にコメントを残すようにした
  - その他にもコードを見ただけでは理解しにくいビジネスロジックや、なぜそのような実装にしたか疑問に思われそうな部分には自分の考えを残すようにしたことで未来の自分も含め保守しやすいコードを意識した

---

### **ゴルフ記録登録・分析アプリ（2022/04〜2022/07）**

<br>

**概要**

プロゴルファー専属キャディを対象とした、ゴルフのラウンド記録・分析を行うモバイルアプリケーションの開発。<br>
ユーザーがゴルフのラウンドを回る時にゴルフ場や天気、各ショットの詳細（何打目、使用クラブ、飛距離など）を登録することで、個々のゴルファーのパターンや傾向を分析し、戦略的なアドバイスを提供する。<br>
データが蓄積されることで、より深く洞察に基づいた助言が可能になる。<br>
別プロジェクトの影響で開発途中だったが約 4 ヶ月で別チームに引き継ぐこととなった。

<br>

**プロダクトが属する業界**

- スポーツ業界

**チーム編成**

- PM 1 人
- 開発者 4 人
- クライアント 1 社

**役割**

- 設計 / 実装
- API Gateway, Lambda(Python) で API の開発を担当
- React Native でモバイルアプリの開発を担当

**言語**

  <p>
    <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  </p>

**フレームワーク・その他**

  <p>
    <img alt="React Native" src="https://img.shields.io/badge/-React Native-45b8d8?style=flat-square&logo=react&logoColor=white" />
    <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
    <img alt="AWS" src="https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  </p>

**課題**

- Python 経験者の不在

  Python について全員が未経験であったため、開発に取り組むにあたって新たな言語を習得しながらの進行となり、その学習コストがプロジェクトの進行速度に影響を及ぼす可能性があった。

- React 経験者の不足

  React の経験者が 1 名しかいなかったため、その開発者が予期せぬ問題に直面した場合、解決までの時間が長引く可能性があった。

<br>

**自身が工夫したこと**

- 開発効率の向上

  具体的な例でいうと、バリデーションライブラリに Cerberus の使用が決まり、私が最初に実装を行なったので、それを横展開し使用方法などを共有することで各々の学習コストを下げ開発効率が上がった。このように、ある API で使用した技術で他の API にも展開できるものであれば、メンバー間で共有し開発効率を高めた。

  <br>

- レスポンス構造の設計

  - **構造の一貫性** : どの API を使用してもレスポンスの基本的な形状が一貫するように API 実装者間での共通認識を作成した。

  - **データをフラットにする** : 必要以上にネストされた構造は避け、可能な限りフラットにした。

<br>

- React Native の実装も一部担当

  プロジェクト成功のためにフロントエンドも実装できた方が良いと考え、API 実装で Python を新規習得しつつ、フロントエンド（React Native）の実装も以下の 2 ページを担当した

  - ラウンド情報の一覧画面（表示だけでなくゴルフ場名や日付での検索機能あり）
  - 各ラウンド情報の詳細画面

---

### **健康管理アプリケーション（2021/06〜2022/03）**

<br>

**概要**

マンションの部屋を購入した入居者向けの健康管理 Web アプリケーションの新規機能開発・保守・運用。<br>このアプリケーションでは、入居者が OMRON など対象メーカーの体重計や血圧計、睡眠計測器で日々計測したデータを、別会社が開発した連携アプリを通じて当アプリに連携。<br>
これにより、管理者権限のユーザー（国立病院の医者）が行うフィードバックや、日々の計測データを入居者はご自宅のテレビを通じて随時見ることができる。

<br>

**プロダクトが属する業界**

- 医療業界

**チーム編成**

- 外部 SIer 1 人
- 開発者 2 人

**役割**

- 設計 / 実装 / テスト

**言語**

  <p>
    <img alt="Java" src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=Java&logoColor=white" />
  </p>

**フレームワーク・その他**

  <p>
    <img alt="Spring Boot" src="https://img.shields.io/badge/-Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
    <img alt="virtualbox" src="https://img.shields.io/badge/-virtualbox-183A61?style=flat-square&logo=virtualbox&logoColor=white" />
    <img alt="CentOS" src="https://img.shields.io/badge/-CentOS-262577?style=flat-square&logo=centos&logoColor=white" />
    <img alt="Jenkins" src="https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
  </p>

<br>

**取り組み**

- 既存の Java コードのリファクタリング

- REST API の設計と実装

- 新規機能開発

<br>

**自身が工夫したこと**

- API の設計において、再利用性と拡張性の確保

---

## 副業

- ホームページ制作

  - 担当：技術スタック選定・要件定義・デザイン(ワイヤーフレーム作成)・実装
  - 使用技術：TypeScript, Next.js, CSS Modules(Sass), AWS（API Gateway, Lambda, SES, S3, CluodFront）, GitHub Actions
  - 友人が起業した会社のホームページを制作。ヒアリングを行い要件定義, デザイン, 実装など全般を行った

  <br>

## 意欲・興味

- 少人数チームで、小さくリリースを行いユーザーフィードバックを受け改善するサイクルを高速で回していく開発スタイルを好みます。
- 現在はフロントエンドに興味がありますが、バックエンドやインフラなど新しい分野・技術への関心も強く学習をしています。
- コミュニケーションを重視し、属人化や暗黙知の共有などを行なっていきたいと思っています。
- サービスによってユーザーの日常的な不便さなどがなくなり、役に立っていると実感できることにとても喜びを感じ、もっとユーザーの生活をより良くしていきたいと感じます。

<br>

## 希望条件

- 地方在住なのでフルリモートワークでの勤務を希望します
- 新しい挑戦（技術的なもの・制度的なもの）に柔軟かつ積極的に取り組める環境が好きです
