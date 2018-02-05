# 動的デザインガイドのつくり方

## 概要 (100文字程度)

サービスとして一貫したデザインを保ち、継続的にアップデートしていくためには、意図を簡単に実現するシステムが必要不可欠です。
AtomicDesignを念頭に、ReactStoryBook等で実践されている動的にデザインガイドラインを生成する仕組みと、実際にサービスに導入して実践するまで(と説得方法)を、GYAO!のWeb刷新の実例を交えて示します。

<!--
- (以下未定ですが)
- デザインガイドラインを動的生成する
    - デザインシステムとは
    - 画面でなくサービスを創るレゴブロック
    - メリット
- Atomicなコンポーネントの独立のさせかた
    - 単体の動作を保証
        - 受け取るデータをJSON-schemaで定義して分離する
    - 単独で描画させる
    - 利用方法は必ず明示
    - 独立してアップデートしていく仕組み
        - モノレポ
        - Test
- 実例の簡単紹介 Atraskit？Airbnb?BuzzBlock?
- GYAO!で実践してるよ
    - 実践して感じる良さ
    - チームへの布教と各分野説得の傾向と対策
    - 今後の課題と未来
        - ImageRegressionTest？
        - 自動生成？
-->

## 登壇者情報

### お名前 
- Masanari Hamada (@narirou)

### プロフィール画像
![プロフィール画像](https://scontent-nrt1-1.xx.fbcdn.net/v/t1.0-9/1601382_1885218441737667_8092038921767189846_n.jpg?oh=f9b6c3565e8b767a9fa5ec6be528900a&oe=5B1FF7A9)

### 所属、肩書き

- WebTeam at GYAO!
- WebEngineer at Yahoo! JAPAN

### SNSs、ブログ等
- Github [narirou](https://github.com/narirou)
- Qiita [narirou](https://qiita.com/narirou)
- Twitter [@narirow](https://twitter.com/narirow)

## 事前確認

### 当日に使用する機材

- 利用するマシンOS: macOS
- 必要なコネクタ端子: Mini DisplayPort

### ライブ配信、スライド公開などの可否

- [X] ライブ配信
- [X] 上記のアーカイブ公開
- [X] 参加者などによるソーシャル投稿
- [X] 写真の公開（各種イベントレポートなど）
- [X] スライドの公開

※ 可の項目にチェックをつけていただき、他に特筆事項があれば併記ください
