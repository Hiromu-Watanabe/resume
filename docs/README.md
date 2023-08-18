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
<a href="https://twitter.com/tenten_dev" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/@tenten__dev-%231DA1F2.svg?&style=flat-square&logo=twitter&logoColor=white" /></a>
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

受託開発の会社で、新卒で入社し現在 3 年目。<br>
入社してから 3 つのプロジェクトで開発に従事。

<br>

### **【プロジェクト一覧】**

### **プロ野球ホーム球場の VIP 席 Web 予約サイト刷新（2022/08〜現在）**

<br>

**概要**

某プロ野球チームホーム球場における VIP 席の Web 予約サイト刷新プロジェクト。<br/>
web サイトで使用するデータは大元の Salesforce システムから必要なデータを ETL ツールで連携されている。<br>
予約情報(ご利用人数、駐車台数など)や事前料理のオーダー、ユーザー情報の登録編集などの一般的な CRUD 機能と請求関連の機能（請求書や会計明細書のダウンロード）などの機能がある Web サイト。<br/>
2023/11 月のプロ野球シーズンオフに UAT 開始予定。

<br>

**プロダクトが属する業界**

- スポーツ業界

**チーム編成**

- PM 1 人
- 開発者 3 人

私は開発者の 1 メンバーとして参画

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

- モックまでの開発を担当した別会社から引き継いだプロジェクトでドキュメントが不十分であり、ソースコードを読み解きながらシステムの構成を理解する必要があった。

- Vue.js（Composition API）と AWS Amplify の利用経験者がチームにおらず、ネット上の開発に関する情報もあまり多くない中で開発を進める必要があった。また Amplify CLI のアップデートが頻繁に行われており、それに追従する形での対応に追われた。

- 引き継いだ段階では要件定義がしっかりされておらず、仕様についても曖昧な箇所が多かった。そのような状況にもかかわらず、UAT 開始予定まで約 4 ヶ月と短い期間で開発する必要があった。

**自身が工夫したこと**

- ドキュメントが不足していたため、情報が不足していると感じた部分はドキュメントを作成しチームに共有することで、チーム全体の業務効率化や生産性向上に貢献した。以下 3 つは具体的な例
  - Amplify CLI で作成した環境の設定情報
  - Amplify CLI バージョンアップによる影響範囲
  - デプロイ作業の各種手順(Git の管理とは別に Amplify の環境を Amplify CLI により切り替える必要があるなど、複雑であった)
  - アイコンフォントについての情報 (IcoMoon が使用されており、そもそも何が使用されているのか、追加・変更はどう行うのかをドキュメントとして残した)
- パフォーマンス改善
  - 当初ログイン処理に約 2 秒かかっていた。認証は Cognito の API によって行っておりその部分の処理は外部 API のため改善しようがなかった。そのため改善が可能な Vue の処理を見直し修正したことでログイン処理時間が約 1 秒まで短縮した。
  - 自動生成された GraqhQL のクエリは不必要な項目まで取得しており、処理時間の遅延に繋がっていると気づいたため、カスタムクエリを作成し必要最小限の項目に絞ることで約 0.5 秒データ取得処理時間が短縮した。
- UI/UX について
  - ローディング機能の実装 : 処理が重い更新・登録処理などクライアントのネットワーク状態によってはボタンを押下した際に処理が完了するまで画面が固まったとユーザーが感じそうだったため、PM やメンバー、エンドクライアントにローディング機能を提案し実装まで至った。
    CRUD 系の処理を行うボタン押下時や画面遷移時にローディング機能を実装した。
- コード内にドキュメントしてのコメントを残す

  - ドキュメントとしての役割を果たすように関数には JSDoc の形式で丁寧にコメントを残すようにした。
  - その他にもコードを見ただけでは理解しにくいビジネスロジックや、なぜそのような実装にしたか疑問に思われそうな部分には自身の考えを残すようにしたことで未来の自分も含め保守しやすいコードを意識した。<br><br>
    例) 商品価格を求める処理に消費税で 100 分率(%)ではなく千分率(‰)を使用していたコードのコメント例

    ```js
    /**
     * @param {number} - unitPrice: 商品単価
     * @param {number} - taxRate: 消費税率
     * @return {number} 税込の商品価格
     */
    const calcCommodityPrice = (unitPrice: number, taxRate: number) => {
      // 消費税の計算には JavaScript による丸め誤差をなくすため、
      // 消費税率は 100 分率(%)ではなく千分率(‰)を使用して計算
      実際の処理;
    };
    ```

**残課題**

- テストコードの不足

  - 納期などのスケジュールの兼ね合いでテストコードがほとんど書けていない。
  - 複数ファイルから呼び出す共通関数などコアな機能は Vitest によるテストコードをタスクの合間に書いたが、現状として足りていない。
  - 手動テストでは網羅性に限界があるため、テストコードを書くための開発基盤の整備が必要。

- CI 環境の整備

  - 上記のテストコードに付随して、GitHub Actions などで PR ごとにテストが走るような CI 環境の整備によりデグレが発生しない環境の整備が必要。

- コンポーネント分割
  - コンポーネントとして分割した方が良いコードも、初期のスケジュール等の兼ね合いでコンポーネント分割できておらず、負債として残っている。
  - どこかでリファクタリングに充てる時間を十分取れるように交渉する必要がある。

---

### **ゴルフ記録登録・分析アプリ（2022/04〜2022/07）**

<br>

**概要**

プロゴルファー専属キャディを対象とした、ゴルフのラウンド記録・分析するモバイルアプリケーションの開発。<br>
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

  React の経験者が 1 名しかいなかったため、その開発者が予期せぬ問題に直面した場合、解決まで長引く可能性があった。

<br>

**自身が工夫したこと**

- 開発効率の向上

  具体的な例でいうと、バリデーションライブラリに Cerberus の使用が決まり、私が最初に実装を行なったので、それを横展開し使用方法などを共有することで各々の学習コストを下げ開発効率が上がった。このように、ある API で使用した技術で他の API にも展開できるものであれば、メンバー間で共有し開発効率を高めた。

  <br>

- レスポンス構造の設計

  - **構造の一貫性** : どの API を使用してもレスポンスの基本的な形状が一貫するように API 実装者間での共通認識を作成した。

  - **データをフラットにする** : 必要以上ネストされた構造は避け、可能な限りフラットにした。

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
    <img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
    <img alt="DBFlute" src="https://img.shields.io/badge/-DBFlute-FF5A5F?style=flat-square&logo=DBFlute&logoColor=white" />
    <img alt="virtualbox" src="https://img.shields.io/badge/-virtualbox-183A61?style=flat-square&logo=virtualbox&logoColor=white" />
    <img alt="CentOS" src="https://img.shields.io/badge/-CentOS-262577?style=flat-square&logo=centos&logoColor=white" />
    <img alt="Jenkins" src="https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
  </p>

<br>

**取り組み**

- 既存の Java コードのリファクタリング
- 研究用に既存の機能をある程度流用し、新規機能を追加した新規のアプリケーション開発
- 新規機能開発
  - 3 つの新規 API の設計・実装

<br>

**自身が工夫したこと**

- API の設計において、再利用性と拡張性を確保することを重視した

<br><br>

---

## 技術的に最も苦労したプロジェクトについて

### プロジェクト

プロ野球ホーム球場の VIP 席 Web 予約サイト刷新

### 困難だった課題

- AWS Amplify に関する情報量の少なさ

  Amplify はサーバーレスなバックエンドを構築するため比較的簡単にフルスタックアプリケーションを作成することが出来る。<br>
  しかし、細かくカスタマイズしようとする際の実現方法に関する情報が少なかった。<br><br>
  `例) 認証の Cognito の設定でログインに使用する email の「大文字・小文字を区別する」という設定を有効にしようとした際の経験`<br>

  AWS マネジメントコンソールだとチェックボックスにチェックを入れるだけであるが、Amplify でこの設定を入れるには上書き用の設定ファイルを作成する必要があり、更に初回のデプロイ時でなければこの設定を入れることができず、初回以外のデプロイでこの設定を入れようとするとエラーでデプロイが失敗した。

  <br>

- Amplify CLI によるデプロイでエラー発生時の原因の分かりにくさ

  エラーが発生した際に原因によっては、エラー文からでは全く原因が特定できないようなものもあった。

<br>

### 課題に対する対応内容

- 公式ドキュメントをマメに確認する

  情報が少ないかつ、Amplify CLI のアップデートが頻繁に発生していたため公式ドキュメントをよく確認するように癖付け、最新の情報と乖離が無いようにした。

- ひたすら PDCA を回す

  公式ドキュメントに無く他エンジニアが記事にもしていない設定方法は、とにかく PDCA を回した。
  具体的には Amplify のデプロイには裏で CloudFormation が動いているため、Amplify のドキュメントではなく別方向からのアプローチとして CloudFormation について調べ CloudFormation テンプレートに追記した。<br>
  また、単純に Try & error をひたすら繰り返した事でなんとか設定したものもあった（初回デプロイ時しか設定できない Cognito の email 属性を「大文字・小文字を区別する」という設定がこれに当たる）

- OSS のソースコードを読み解く

  Amplify CLI は OSS として公開されているため、デプロイ時に原因特定できないようなエラー文が出力された場合は、Amplify CLI の GitHub リポジトリを fork し、エラーが起こっている該当箇所を洗い出し、原因を特定・解決した。

- 情報の共有・ドキュメント化

  PDCA の過程・結果や、公式ドキュメントでの変更点などは自身の中に暗黙知として留めるのではなく、チームメンバーに共有したり、ドキュメントとして残し後からも見返せるようにした事でチームとしての開発効率上昇に貢献できた。

<br><br>

## 自身の現状の課題

- 経験と教育機会の少なさ

  これまで経験したプロジェクトは、コードレビューなどは全て直属の上司 (現在エンジニア歴 8 年目) とマンツーマンで行ってきた。
  そのため、上司も分からないことに関しては自分自身でなんとか解決してきたことで身についた自走力と独力での課題解決力が強みであると思っている。

  その一方、直属の上司以外のシニアエンジニアのような中堅以上の経験豊富なエンジニアと働いた経験が少なく、豊富な経験をもとにしたレビューなどを受けながらエンジニアとしての基礎を作る時期を経験できていないため、エンジニアとしてまだまだ未熟であることを自覚している。

  貴社に入社した際には自分のやり方に固執せず、新しい環境の中でフィードバックを素直に受けながら事業に貢献・エンジニアとして成長したいと考えている。

<br><br>

## 副業

- ホームページ制作

  - 担当：技術スタック選定・要件定義・デザイン(ワイヤーフレーム作成)・実装
  - 使用技術：TypeScript, Next.js, CSS Modules(Sass), AWS（API Gateway, Lambda, SES, S3, CluodFront）, GitHub Actions
  - 友人が起業した [会社のホームページ](https://io2-official.com/) を制作。ヒアリングを行い要件定義, デザイン, 実装など全般を行った

  <br>

## 意欲・興味

- ユーザーファーストで妥協のない仕事を求める
- 小さくリリースしユーザーフィードバックを受け改善するサイクルを高速で回していく開発スタイルを好む
- 現在はフロントエンドに興味がありますが、バックエンドやインフラなど新しい分野・技術への関心も強く学習を進めている
- コミュニケーションを重視し、属人化や暗黙知の共有などを行なっていきたい
- サービスによってユーザーの日常的な不便がなくなり、役に立っていると実感できることに喜びを感じる
- 新しい挑戦（技術的なもの・制度的なもの）に柔軟かつ積極的に取り組める環境を好む

<br>

## 希望条件

福岡在住のため、フルリモートワークでの勤務を希望いたします
