https://medium.com/@awilkinson/slack-s-2-8-billion-dollar-secret-sauce-5c5ec7117908

Slack秘伝のタレ、お値段28億ドル

#### 「小生意気だけど憎めない、みんなのロボット助手」であることを選んだ Slackが、以下にして数十億ドル規模の市場を席巻したか


\

「で、Slack http://www.slack.com はどうしてあんなにうまくいってるの？何かしら特別なこと、したんでしょ？」車載の Bluetooth スピーカーから声が響く。「なんであれ、彼らにしたのと同じことをして欲しいんだ。」電話で話していたのは、見込み顧客である有名 SaaS プロバイダーの CEO。自社製品デザインの見直しをうちに頼もうとしてやりとりを続けてる。上述のような質問を受けたので、これまでに数えきれないほど繰り返してきた説明を彼にもすることにした。

実際のところ、過去一年間、毎日この質問を顧客や投資家、デザイナー仲間から受けてきた。みんな「Slack 大成功の秘密」をなんとか探ろうとしていたわけだ。Slack は今ではすっかり業界を取り込んでしまったかのように思える。評価額は圧巻の28億ドル、何十万ものユーザー数をほこり、常識はずれの速度で成長中だ。

Slack に関する質問がどうして僕のところに来るかというと、それは MetaLab http://www.metalab.co というデザイン事務所を経営しているから。この事務所のことを知っている人はあまりいないかもしれない。表舞台に出ることは少ないからね。けれど、僕達がデザインしたサイトやサービスを誰でも一度は使ったことがあるはず、っていう自信はある。2013年も終わりに近づく頃、Slack から依頼を受けて彼らが作った初期プロトタイプを作りこんで仕上げることになった。ロゴ・マーケティング用のサイト・Web サービス用のサイトとモバイルアプリ、それらすべてをたった6週間で片付けた。その後いくつか変更があったといえ、Slack の大半は変わることなく MetaLab が納品したままの状態で今も運営されている。

会社を立ち上げてから10年になるが、Slack は弊社最大の成功例だ。これまでにいくつもの大企業と仕事をしてきたけれど http://www.metalab.co、それは間違いないと思う。Slack の現時点での評価額は28億ドルで、有料ユーザー数は20万人を超えているし、ありがたいことに使う人はみなデザインを絶賛してくれている。とはいえ、まさかこれほどうまくいくとは思っても見なかったけれど。

* * * * *

2013年7月、Stewart Butterfield からメールをもらった。彼の名前にはすぐにピンときた。僕が愛用している Flickr を生み出したのは彼だし（のちに Yahoo に売却。）、2人ともアメリカ北西部の太平洋沿いに住んでいたからね。メールをくれたのはビッグニュースが2つあったから。1つは Glitch http://en.wikipedia.org/wiki/Glitch_%28video_game%29 を閉鎖するというニュース（Glitch は Butterfield が2009年から開発してきたゲーム。）で、もう1つは彼が新しいプロジェクトに着手した、というニュース。そのメールで Butterfield は、新たに始めたグループチャットアプリのデザインを手伝って欲しい、と言ってきた。

思わずうなったよ。うちは当時 Campfire http://www.campfirenow.com のヘビーユーザーで、Campfire 以降出てきた類似プロダクトも随分試していたんだけど、こういったサービスにはもう改善すべき点がないと感じてた。市場競争が激しい分野だし、他より Butterfield のプロダクトを目立たせるのは至難の業だと思ったわけだ。とはいえ、彼と一緒に仕事ができるのはテンションが上がる話だったから、Campfire に感じてた不満を解消するのもいいかもな、と思うようになった。そんなわけで、彼からのオファーを受け、キックオフの場も設け、「さぁやるぞ！」と腕まくりしたわけだ。

初日、これまで見せてもらえなかった出来たばかりのプロトタイプを見せてもらった。IRC をブラウザーに押し込んだような感じで、飾り気もなくそっけないものだった。我々は、6週間かけてそれを弊社最大の成功例と呼べるサービスに仕立てあげた。ブラウザーに押し込まれた IRC をみんなが大好きなあの Slack にどうやって変身させたか、これから説明していこう。

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*quxuSggwBdYkyCoYlE3OAA.png)

初期のデザイン案あれこれ（2013）

物事がどうしてうまくいったのかをあとから振り返るのは、水の味を説明するのに似ているようにも思う。それはすごく*難しい*。MetaLab では手順を重視していなくて、ただただ手を動かしてデザインしていくことを大事にしている。何度もそれを繰り返して、これだっ！という何かを見つけるんだ。Slack も同じように進めた。特別な手順があったわけじゃない。ただ、いま思えば、Slack をここまでの成功例たらしめたキーポイントはいくつかあるように思う。

Slack を使っている人の話を聞くと、「Slack は楽しい」というのをよく耳にする。使っていても仕事っぽい感じがしないってことだ。さぼってるような気にすらなってくる。Slack を使って仕事を片付けているのに、だ。とはいえ、裏側を見てみると、他のチャットアプリと何ら違いはないことがよくわかる。チャットルームを作って、メンバーを招待し、ファイルを共有したり、グループチャットをしたり相手を選んでメッセージを送ったりと、何も特別なことはない。では、Slack のどこが特別なのか？キーポイントは3つだ。

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*Ryu8xQJ-6KRjP73jZe4HWg.png)

ブランドを煮詰めているところ（2013）

#### 見た目が違う

\

競争が厳しい分野で目立つために、それを実現する方法を探す必要があった。法人用ソフトウェアは、その大半が70年代に流行ったプロム（訳注：高校卒業記念ダンスパーティ）用の安物スーツみたいな見た目だった（当時は誰もが控えめの青かグレーのスーツを着てた）。だから、Slack のロゴをはじめとする見た目はカラフルな紙吹雪をばらまいたような配色にすることにした。青・黄・紫・緑を色鮮やかに散りばめたんだ。まるでテレビゲームのような配色で、とても法人用の協業支援ソフトウェアとは思えないくらいだった。

このスクリーンショットは左が HipChat で右が Slack。

![](https://d262ilb51hltx0.cloudfront.net/max/1200/1*Eyy-KRgOtGcOnaAIJPV28Q.png)

どっちを使ってみたい？できることはまったく同じなんだけど、片方はつまらない感じがして、もう一方はカラフルで遊び心満載だ。何が違いを生んでるかって？鮮やかな色使いに曲線がきれいなゴシック体のフォント、かわいいアイコンにあちこちに表示される絵文字だよ。

#### 使い心地が違う

\

Slack には、思わずニヤッとしてしまうような挙動をこれでもかと詰め込んだ。ロゴが表示されるときのカラフルなアニメーション、画面最上部からススッと降りてくるモーダルダイアログの動き、トランプを切っているかのようなチーム切り替えの動作。このプロダクトではそのすべてが、画面をところ狭しと楽しそうに飛び回っているかのようなのだ。単に画面上で起こっていることをわかりやすくするだけでなく、ユーザーがホッと表情をゆるめてくれるよう、こういった挙動はデザインされている。

まるでテレビゲームのような配色で、とても法人用の協業支援ソフトウェアとは思えないくらいだった。

誰かの家にお邪魔したとき、「なに、この安物っぽさ！？」と思ったことはないかな？建築の専門家なら、何がまずいのかをあれこれ教えてくれるだろう。不揃いの壁材・継ぎ目の目立つ硬木の床材・板張りのドア・安物機器の数々……でも、大抵の人はただただ直感的に反応する。優れた家と同様にすぐれたソフトウェアに不可欠なのは、細やかで満足のいく挙動をいくつもユーザーに返していくことだ。モバイルアプリの画面遷移がしっかりと作りこまれていれば、重厚なオーク材ドアに取り付けられたきちっとしたドアノブを使った時のような心地よさをユーザーに与えてくれる。Slack という家に実際に触れてみることはできないが、それの出来栄えには思わず感嘆の声が漏れてしまう。使っていてほんとうに楽しい。そう、Slack の使い心地はまさに優れた家のそれだ。

#### It Sounds Different {#1eb1 .graf--h4 name="1eb1"}

\
Slack の違いは見た目や使い心地に留まらない。メッセージの1つ1つにも工夫が凝らしてある。Slack に表示されるメッセージを、遊び場だと捉えているからだ。競合サービスなら読み込み中のアニメーションが表示されるであろう箇所には、クスっとくるような一文を表示する。「急いでデザートを作らなきゃいけないって？オレオを床にばらまいたら、動物みたいにそれにむさぼりつけばいいよ。」こんな具合で、ちょっとした楽しさがあちこちに置いてある。そうでもしないと一日退屈でしかたないだろ？Slack は冗談好きなロボット助手のように振る舞う。そうしないと、ありふれた法人向けチャットツールに成り下がってしまうから。後者が2001年宇宙の旅の HAL9000 だとすれば、前者はインターステラーの TARS といっていいだろう。

**Slack:**

> TARS: Everybody good? Plenty of slaves for my robot colony?

**競合サービス:**

HAL9000: たしかにここしばらく、わたしの判断にはいい加減のところがあった。だが正常にもどることは確約していい。この任務には、わたしは絶対の自信を持っているし……それに、きみを助けたいんだ。

Slack の Twitter アカウント https://twitter.com/slackhq も、絵文字にはまってるお笑い芸人といったほうが正確で、とても数十億ドル規模のソフトウェア企業とは思えない。

![](https://d262ilb51hltx0.cloudfront.net/max/800/1*WdSRsXcnlyeo2tZSApwYIQ.png)

We humans have a tendancy to anthropomorphize just about everything, from our pets to inanimate objects. We think cars look like they are smiling, or that a lamp “looks lonely over there”. With Slack, a bubbly, bright UI, delightful interactions, and hilarious copywriting come together to create a personality. A personality which has triggered something powerful in its users: they care about it. They want to share it with others. It feels like a favorite co-worker, not a tool or utility.

> *“Slack acts like your wise-cracking robot sidekick, instead of the\
> boring enterprise chat tool it would otherwise be.”*

* * * * *

As a kid, I used to love this burger chain called [White Spot](http://www.whitespot.ca). It started out as a tiny shack at a baseball stadium and over the past 85 years it has grown into a huge chain with locations all over Canada. The secret to its success? The “Triple-O” secret sauce that they put on all their burgers.

I used to bug my parents to let us go to White Spot instead of having another gross lovingly home-cooked meal. That is, until my Dad dropped a bomb on me. “We should just make burgers at home,” he said “you know that sauce is just mayonnaise, ketchup, and a bit of relish, right?” Sure enough, we made it at home, and confirmed that their so-called secret sauce was a bunch of grocery store condiments mixed together.  Anyone could make it, but few people knew how or bothered. Instead they chalked it up to a some crazy secret recipe.

Slack’s secret sauce is no different. Sure, it’s hard to get the mix of ingredients just right, but it doesn’t have any features that Hipchat and Campfire can’t build. It’s the same enterprise chat client underneath, but it’s playful, fun to use, and all that comes together to make it feel like a character in your life. It’s TARS, not HAL9000.

Over the past couple months, their competitors have caught on. They’ve all started using casual copy and trying to bone up on design, but it’s a little like your uncle trying to do the macarena. It’s too little too late. Everyone has picked their robot sidekick. Slack has stolen the show.

