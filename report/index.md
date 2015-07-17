---
layout: default
title:  Report
---

## 関西Ruby会議06

----

### はじめに

2015年7月11日 に開催された **関西Ruby会議06** の当日の様子をレポートしたものです。

![P1030151]({{ site.baseurl }}/assets/img/report/P1030151.JPG)

### 開催概要

* 開催日
    * 2015年7月11日 (土)
* 開催会場
    * エムオーテックス新大阪ビル エムオーテックスホール
* 参加者数
    * 190名
* ハッシュタグ
    * #kanrk06
* 主催
    * Ruby関西
* テーマ
    * Enjoy Programming
* 公式サイト
    * http://regional.rubykaigi.org/kansai06/
* まとめ
    * [スライドまとめ](http://matome.naver.jp/odai/2143661425669201301)

### オープニング

参加者が230名も登録されていましたが、手慣れたメンバーと当日スタッフの連携でスムーズに受付ができました。
会場は大通りから少し中に入った所なので、当日スタッフが道案内をしてくれたのもよかったです。

![P1030040]({{ site.baseurl }}/assets/img/report/P1030040.JPG)

スタッフは朝の8時30分には集合をしていましたが、参加者も9時頃には集まり始めていました。
Doorkeeperで募集をしていたので、みなさん「アプリでチェックイン」の準備して並んでいます。

![P1030080]({{ site.baseurl }}/assets/img/report/P1030080.JPG)

基調講演、講演、LTを含めると発表者は17名でした。その発表者の司会を務めた３名です。
マイクランーナーも傾斜のある階段を俊敏に駆け回っていました。

![P1030145]({{ site.baseurl }}/assets/img/report/P1030145.JPG)

### Rubyにみるプログラミングスタイルの進化

基調講演: まつもと ゆきひろ さん

タイトルはプログラミングスタイルの進化ですが、**まつもと ゆきひろさん**の進化も拝見することができました。

今では聞く事のない言葉もいくつか紹介されていました。
当時はコンピュータが高価なので、コンパイラの気持ちになってノートに書いて勉強する。（無いコン族）
「私が設計していかんのか？」となり想像の「ぼくの考えた最強の言語」が生まれる。（ペーパープロトタイピング）

![P1030204]({{ site.baseurl }}/assets/img/report/P1030204.JPG)

社内のアプリケーションを作成していたが、会社の方針転換で保守の要員となった。
しかし、そこがプログラミング言語の **Ruby** が生まれるきっかけになったそうです。

![P1030335]({{ site.baseurl }}/assets/img/report/P1030335.JPG)

ウェブアプリケーションの全盛で **Ruby** が広く使われ始めた。（作者としては不本意）
DSL（抽象化を一段上げる）や、メタプロも活用の貢献も大きい。

![P1030387]({{ site.baseurl }}/assets/img/report/P1030387.JPG)

プログラミングスタイルの進化にバージョン管理ツールの進化が影響をあたえた。
（昔々はフロッピーディスクに **tar** でファイルをまとめて世代管理をされていた逸話がありました。）

* RCS（ロック・アンド・モディファイ）... 職場が荒れた。
* CVS（エディット・アンド・マージ）... 職場に平和が戻る。
* svn（アトミック・コミット）... ネットワークが必要。
* git（分散バージョン管理）... ネットワークが不必要。

そして、**GitHub** の登場でオープンソースがしてきた開発の手法を会社の社内の開発でもするようになった。

![P1030349]({{ site.baseurl }}/assets/img/report/P1030349.JPG)

質問タイムでは、「島根は好きです！」と即答していました。（前日の前夜祭でなにかあったらしい？）
また、**まつもと ゆきひろ さん**はC言語のプラグラマーなので、「Ruby会議はアウェー感」の回答に会場が賑わいました。

![P1030476]({{ site.baseurl }}/assets/img/report/P1030476.JPG)

### スポンサーLT

スポンサーの特別枠で5人のLTがありました。
Rubyビジネスフォーラムではスーツ率が高いそうです。

![P1030512]({{ site.baseurl }}/assets/img/report/P1030512.JPG)

こちらは **関西Ruby会議06** の集合写真です。（圧倒的な私服率の高さでした。）

![P1030570]({{ site.baseurl }}/assets/img/report/P1030570.JPG)

![P1030568]({{ site.baseurl }}/assets/img/report/P1030568.JPG)

![P1030571]({{ site.baseurl }}/assets/img/report/P1030571.JPG)

### Railsガイドを支える技術

講演: @yasulab さん

Railsガイドを継続的に更新していく技術をデモンストレーションと交えての紹介です。
プロの翻訳者の八田さんがパワフルに翻訳を進めて行かれるそうです。

![P1030526]({{ site.baseurl }}/assets/img/report/P1030526.JPG)

「Railsガイド電子版を今日に出版するために、前夜祭の参加を諦めました。」
「夜中の３時までコミットしていました。」 ... 会場からの大きな拍手！（88888888）

![P1030540]({{ site.baseurl }}/assets/img/report/P1030540.JPG)

### 200万 Webサイトを支える ロリポップ！と mruby

講演: @harasou5 さん

**mruby** と **mod_mruby** で大量のアクセスに対応することができます。

* リソース制御の3本の矢
    * http-dos-detector
    * http-access-limitter
    * mruby-cgroup

![P1030563]({{ site.baseurl }}/assets/img/report/P1030563.JPG)

**mod_mruby** の紹介で、ヒゲの松本さんの紹介に会場は「???」の空気になりました。
（スライドの**まつもと ゆきひろ さん**と**松本 亮介さん**にはどちらもヒゲがあります。）

![P1030564]({{ site.baseurl }}/assets/img/report/P1030564.JPG)

### スモウルビー1.0：小学３年生から始めるRubyプログラミング

講演: @takaokouji さん

スモウルビーはスクラッチのように子供でも簡単にプログラミングを楽しめます。
野球のリトルリーグのようなプログラミング少年団を目指して活動をされています。

![P1030579]({{ site.baseurl }}/assets/img/report/P1030579.JPG)

スモウルビーで「ねずみとねこの追いかけっこゲーム」のライブコーディングがありました。
限られた時間でゲームを作り、そのゲームもライブでクリアするパフォーマンスで盛り上がりました。

![P1030575]({{ site.baseurl }}/assets/img/report/P1030575.JPG)

### RSpec、Minitest、使うならどっち？

講演: 伊藤 淳一 さん

QiitaでRubyの部、Railsの部、RSpecの部は全て1位のストックを獲得されています。
**xUnit形式 vs Spec形式** や **RSpec vs Minitest** をとても丁寧に解説されていました。

![P1030588]({{ site.baseurl }}/assets/img/report/P1030588.JPG)

**伊藤 淳一 さん**は主観的に選ぶなら **RSpec** だそうです。
「**Minitest** はDIYer気質が強い方に好まれる。」という分析（仮説）

![P1030593]({{ site.baseurl }}/assets/img/report/P1030593.JPG)

### Railsパフォーマンス基本のキ

講演: @joker1007 さん

社内のQiitaでは圧倒的な1位でストックを獲得されています。
パフォーマンスが悪くなる要因を例を見ながらの解説でした。（特に **serialize** は気を付けて使うべし！）

![P1030615]({{ site.baseurl }}/assets/img/report/P1030615.JPG)

検知と計測のためのツールの紹介で Activerecord::Cause のGemは **@joker1007 さん** が作ったそうです。
「最も大事なことは、壊れた窓を放置しない」の言葉は身に突き刺さりました。

![P1030610]({{ site.baseurl }}/assets/img/report/P1030610.JPG)

### API server/client development using JSON Schema

講演: @izumin5210 さん

「Kobe.rb と Asakusa.rb から来ました。」これが一番言いたかったようです。
JSON Schema は YAML で記述できます。（JSON は **{}** と **""** の入力で shift キーが死ぬんじゃないか！？）

![P1030617]({{ site.baseurl }}/assets/img/report/P1030617.JPG)

「テスト支援ツールとしての **JSON Schema** がイケてる使い方です。」
**SOAP** おじさんからの **まさかり** がくるそうですが、きちんと議論をしたいそうです。

![P1030620]({{ site.baseurl }}/assets/img/report/P1030620.JPG)

### LT大会

#### サーバサイドなおじさんがSPAを趣味で初めて作ってみたときにわかった n のこと(仮)

LT: @muryoimpl さん

![P1030645]({{ site.baseurl }}/assets/img/report/P1030645.JPG)

#### 受託開発とRubyGems

LT: @koic さん

![P1030663]({{ site.baseurl }}/assets/img/report/P1030663.JPG)

#### 派遣エンジニアが業務にRubyを取り入れるまで

LT: @hayabusa333 さん

![P1030679]({{ site.baseurl }}/assets/img/report/P1030679.JPG)

#### インフラの人がChefやServerspec(ほか)がRubyだったおかげですこしプログラムをするようになった

LT: @sawanoboly さん

![P1030710]({{ site.baseurl }}/assets/img/report/P1030710.JPG)

#### ActiveAdmin Better Practices

LT: @ShinsukeKuroki さん

![P1030723]({{ site.baseurl }}/assets/img/report/P1030723.JPG)

### キーワードパラメータを支える技術

基調講演: 笹田 耕一 さん

キーワードパラメータは **Ruby 2.2** で早くなりました。
（会場では使っている人は少なかったですが、早くなったのでどんどん使いましょう。）

![P1030792]({{ site.baseurl }}/assets/img/report/P1030792.JPG)

シンボルGCの改善が **Ruby 2.2.2** で対応してると思っていたら、その修正が入っていなかった。
「Ruby **2.2.3** ではなおっているかも？」

![P1030794]({{ site.baseurl }}/assets/img/report/P1030794.JPG)

**Ruby 2.2** からの インクリメンタル GC で大幅に改善がされています。
（グラフのピンと跳ね上がるポイントを押さえる事ができています。）

![P1030800]({{ site.baseurl }}/assets/img/report/P1030800.JPG)

**笹田 耕一 さん**をイベントに招待すると **Ruby** のクオリティーが上がるそうです。（スライドのネタ作りため！）
それと、**笹田 耕一 さん**も C言語のプラグラマーなので、Ruby会議はアウェー感！？

![P1030847]({{ site.baseurl }}/assets/img/report/P1030847.JPG)

参加者は朝からのたくさんの発表を真剣に聞き入っていました。
また、質問タイムには積極的に手を挙げて会場を盛り上げて頂きました。

![P1030633]({{ site.baseurl }}/assets/img/report/P1030633.JPG)

### クロージング

大勢の参加者や発表者、スタッフ・スポンサーのおかげで関西では最大級の **Ruby** のイベントは大成功に終わりました。
アフターパーティーも70名の参加者で賑わいました。（席に座らずあちこちで立ち話で盛り上がるほどでした。）

![P1030886]({{ site.baseurl }}/assets/img/report/P1030886.JPG)

![P1030888]({{ site.baseurl }}/assets/img/report/P1030888.JPG)

![P1030892]({{ site.baseurl }}/assets/img/report/P1030892.JPG)

関西Ruby会議06 のノベルティーです。Tシャツとバックをステッカーの3種です。
（ステッカーは前夜祭と懇親会で配られたレアアイテムです。）

![novelty]({{ site.baseurl }}/assets/img/report/novelty.jpg)

### るびま 担当

レポート: 尾篭 盛 (ogom)
写真提供: 田又 利土 (rito)

![P1030582]({{ site.baseurl }}/assets/img/report/P1030582.JPG)
