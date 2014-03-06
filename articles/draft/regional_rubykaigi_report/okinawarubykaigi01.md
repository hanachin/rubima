##はじめに

沖縄で毎週開催されている Okinawa.rb の発起人である @yasulab さんが中心となって、沖縄初の「沖縄Ruby会議01」が開催されました。

### 開催日

2013年3月1日 13:00-18:00

### 開催場所

琉球大学 工学部１号館 大教室 322 (本会場) & 321 (サテライト会場)


### 主催

![okinawarb-logo](okinawarubykaigi01/okinawarb-logo.png)

![ryudairb-logo](okinawarubykaigi01/ryudairb-logo.png)

![ryukyurb-logo](okinawarubykaigi01/ryukyurb-logo.png)


### 協力

日本Rubyの会、ギークハウス沖縄、株式会社レキサス、特定非営利活動法人軽量Rubyフォーラム、ウェブペイ株式会社

### 公式タグ・Twitter

\#okrk01

* [沖縄Ruby会議のtweetまとめ](http://togetter.com/li/636273)

## Lightning Talks 1 + Sponsored Session (各10分)

## 「Rubyによるバッチ業務のストリーム処理化の設計と実装」@bash0C

* 発表者
    * [@bash0C7](https://twitter.com/bash0C7)
* 資料
    * [Rubyによるバッチ業務のストリーム処理化の設計と実装](https://speakerdeck.com/bash0c7/design-and-implement-batch-stream-processing-application-for-ruby)

ログ収集ツールとして注目される[fluentd](http://fluentd.org)を使いストリームにバッチ業務を処理する手法を紹介して頂きました。通常はログ収集のみにつかわれることが多いfluentdですが、入出力のプラグインを自作することで解析されたwebストリームを受けて進捗確認のツールとして使用することが出来るそうです。プラグインは[RubyGem](https://www.ruby-lang.org/ja/libraries/)の形式で導入することが出来るため、手軽に機能を追加する出来るということをおっしゃていました。

## 沖縄県内のコミュニティ活動の紹介

沖縄のRubyコミュニティだけでなく、県内で活動するコミュニティ紹介のLTも行いました。
ものづくりのコミュニティから、エンジニアの集うシェアハウスまでの計5つのコミュニティの発表を行いました


## ギークハウス沖縄 @kimihito_

* 発表者
    * [@kimihito_](https://twitter.com/kimihito_)
* 資料
    * [ギークハウス沖縄](https://speakerdeck.com/kimihito_/gikuhausuchong-nawa-in-chong-nawa-rubyhui-yi-01)

![geeoki](okinawarubykaigi01/geeoki.jpg)

エンジニアやインターネット好きが集うシェアハウスである[ギークハウス](http://geekhouse.tumblr.com/)の中でも日本最南端である、[ギークハウス沖縄](http://text.geeoki.com/)の活動のお話していただきました。Okinawa.rbの毎週のMeetupの会場になっていたり、Rubyでロボットの操作ができるフレームワークである[Artoo](http://artoo.io/)を使ってRubyでARDroneを飛ばしたりなど、部室のような空気が残るギークハウス沖縄の紹介でした。


## 「rcairoでものづくり」@mgwsuzuki

* 発表者
    * [@mgwsuzuki](https://twitter.com/mgwsuzuki)
* 資料
    * [rcairoでものづくり](http://www.slideshare.net/mgwsuzuki/ruby-kaigi-rcairo)

![rcairo](okinawarubykaigi01/rcairo.jpg)

2Dグラフィックス用のCライブラリである[cairo](http://cairographics.org/)をRubyでバインディングした[rcairo](https://github.com/rcairo/rcairo)を使って、自動設計するプログラムをRubyで作成、1時間20分ほどで完成することができたそうです。今後はGithubに自動設計のプログラム公開し、パラメータをPull Requestすることで簡単にハコを作れるようにしたいということをおっしゃっていました。



