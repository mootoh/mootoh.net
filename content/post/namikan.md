---
title: 並カンの思い出
tags:
  - event
  - event
  - namikan
  - namikan
id: 2022
categories:
  - default
date: 2010-02-04 02:32:07
---

並列プログラミングカンファレンス、略して [並カン](http://atnd.org/events/2092) を開催しました。はじめてのイベント開催でどうなることかと思いましたが、とてもよい会になりました。

### いまそこにある並列プログラミング

そもそも、なぜ並列プログラミングについて語るのか。この会をひらいた目的はなんだったのか。そのあたりについて話しました。

<div style="width:425px;text-align:left" id="__ss_3055455">[並カン (CM カット版)](http://www.slideshare.net/mootoh/ss-3055455 "並カン (CM カット版)")<object style="margin:0px" width="425" height="355"><param name="movie" value="http://static.slidesharecdn.com/swf/ssplayer2.swf?doc=namikan-keynote-100202113525-phpapp02&stripped_title=ss-3055455" /><param name="allowFullScreen" value="true"/><param name="allowScriptAccess" value="always"/><embed src="http://static.slidesharecdn.com/swf/ssplayer2.swf?doc=namikan-keynote-100202113525-phpapp02&stripped_title=ss-3055455" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="425" height="355"></embed></object><div style="font-size:11px;font-family:tahoma,arial;height:26px;padding-top:2px;">View more [presentations](http://www.slideshare.net/) from [Motohiro Takayama](http://www.slideshare.net/mootoh).</div></div>

みんながふつうにつかっているコンピュータはすでにマルチコアになっていて、速いプログラムを書きたければ並列プログラミングをするしかない。富豪的アプローチもよいですが、ぼくは遅いプログラムがイヤなのです (これは自戒)。

たとえば。病床にいるとしましょう。もうそんなに時間が残されていない。夜になり、痛みで眠れない。唯一の助けは家族とのケータイによるメールだったりするのです。そんなとき、ケータイに載っているソフトウェアの動作が緩慢で、 UI のレイテンシがひどかったりするのは許せない。雷鳴が閃くかのように高速に走るコードを書き、ひとがコミュニケーションするじゃまをしない UI が実現できるよう、力を尽くしたい。

ん、なんだか話が逸れました... ともかく、並列プログラミングをふつうのプログラマも嗜んでないといけなくなりつつある。しかし、これまで並列プログラミングというと、研究者や一部の必要に迫られた人たちの分野だったりしました。並列プログラミングについて、ふつうのプログラマがカジュアルに話す場ってまず見ない。んじゃひとつ、そういう場をこしらえてみよう、というのが今回の並カンをやった目的だったのでした。

まぁ、「並列プログラミングしているひと！」と聞いたときに、半数以上の方が手を挙げてくださったときにはたまげましたが。

### みなさんの発表

ハードウェアから独自言語まで、という幅の広さでした。いずれも浮世離れしたものではなく、現実世界の問題を解決するための話だったのがとてもよかった。

- [並列プログラミングのおさらい](http://www.trickpalace.net/paper/parallel-programing-brief.pptx) ([@wraith13](http://twitter.com/wraith13))
- [FPGA/HDLを活用した ソフトウェア並列処理の構築 (pdf)](http://infog.0ch.biz/download/namikan_1_goyoki.pdf) ([@goyoki](http://twitter.com/goyoki))
- [STM](http://d.hatena.ne.jp/hayamiz/20100201) ([@hayamiz](http://twitter.com/hayamiz))
- [MUDA](http://www.slideshare.net/syoyo/muda) ([@syoyo](http://twitter.com/syoyo))
- [ロックフリー](http://d.hatena.ne.jp/bsdhouse/20100131/1264920091) ([@yamasa](http://twitter.com/yamasa))
- [Haskell](http://page.freett.com/shelarcy/log/2010/diary_01.html#namikan) ([@shelarcy](http://twitter.com/shelarcy))
- 東京 Ruby 会議 03 ([@ayumin](http://twitter.com/ayumin))

終わったあとに、「最近のライトな勉強会のノリじゃなく、ひどくテクニカルなところがよかった」という声をいくつかいただきました。発表に名乗りをあげてくださったみなさんのおかげです。クオリティたかい!

特定分野に偏らず、多様な話をまとめて聴けたのはよかったんじゃないかな。分野のまたがりはゆるく、技術的には深く。ぼくはとても楽しめました。発表の途中に質問をはさむ、という主催者の特権を乱用したりして。会場の雰囲気、 [Twitter のまとめ](http://togetter.com/li/4515) を読む限りでは、なかなか盛り上がっていたようでした。

### 運営、スタッフ、課題

当日に至ってもほとんど計画のないままで、まったくどうなることかと思いました。これはひどい。無事に終えることができたのは、頼りないぼくを見かねて助けを名乗り出てくださったみなさんのおかげです。

- 会場を提供してくださった [@sbg](http://twitter.com/sbg) さん。会場の張り紙準備やプログラム、設営から片付けに至るまですべてやってもらってしまいました。
- 最初の会場設営から懇親会幹事までずっと手伝ってくれた [@cesare](http://twitter.com/cesare) さん。
- Ust のクオリティをあげてくれた [@niw](http://twitter.com/niw) さん。
- 寒い中、休憩時間のたびに門を開けに行ってくれた [@eikom](http://twitter.com/eikom), [@ayumin](http://twitter.com/ayumin) さん。
- 突発的に手伝ってもらった [@sunaot](http://twitter.com/sunaot), [@takkanm](http://twitter.com/takkanm) さん。

みなさんが自ら動くことでイベントが組み上げられているのをみて、まじめに感動しました。レベルたかい!

課題は山ほどある。やってみて初めて気づくことというのがありますね。

- ちゃんとしたプログラムがなかった。終わる時間がのびてしまったのはまずかった。
- ひとつひとつのセッションがちょっと長かったかな。おもしろい話ばかりだったので、短くするのもつらいところ。時間をちゃんと区切っておけばよかったんだろう。
- 当日やることは前日までに洗い出しとかないと。
- atnd はやはりつらい。キャンセル率は、だいたい予想どおりだったのでよいのですが、全員に告知する方法がないのが致命的。 twtvite とかがよさそう。
- Ustream。事前にお伝えしていれば、ちゃんとした方法で中継することができた。マイクは必須ですね。あと、録画しわすれてた。次は Ustream Producer を試そう。
- wave はあまり使われなかった。勉強会といったチーム作業で威力を発揮するだろうと踏んでいたんだけれど、まだまだ市民権を得られていない。

次に何か企画するときには、このあたりを踏まえて精進します。

### 次回

終わってから、「第2回も楽しみにしてます！」といった声をいくつか見ました。むむむ... [アンケートをつくりました](http://polls.tw/f6/p) ので、投票いただければ。

やるとしたら。今回は並列プログラミングの話題を中心にしましたが、 Web の世界のような分散システム、並行プログラミングについての話があればよいな。みんなが実際に手を動かすワークショップもいいですね。あとぼくも例のやつについて続編をしゃべります。

いずれにせよ、おもしろ発表者が幾人か集まれば開催したいとおもいます。

 ----

Happy Parallel Hacking!