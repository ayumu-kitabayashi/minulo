# minulo：iPhone と Android でインスタのリールと YouTube のショートを消すアプリ

[English](README.md) · [한국어](README.ko.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Português](README.pt.md)

**minulo（ミヌロ）** は、インスタのリールと YouTube のショートを消す iPhone と Android のアプリです。インスタの発見とおすすめ投稿、TikTok のおすすめも消せて、Mac 版もあります。消すのはリールやおすすめだけなので、DM やグループDM で友だちとやりとりしたり、フォローしている人の投稿を見たりはふつうにできます。

- App Store：https://apps.apple.com/jp/app/id6809352229
- Google Play：https://play.google.com/store/apps/details?id=app.feedminus
- サイト：https://minulo.app/?ref=github-readme-ja
- 報道：韓国の朝鮮日報（The Chosun Ilbo）で紹介されました（2026年11月2日、[記事](https://www.chosun.com/jp/economy-jp/2026/11/02/VU6ZWHMXLZCZDLNXE76AIIRSAU/)）
- 料金：リール・ショート・おすすめは無料で消せます。minulo Pro（日本は月1,200円・年4,800円）は、使いたい人だけが入ります。
- 対応：Instagram・YouTube・TikTok・X・Threads・Facebook・Pinterest・Reddit・LinkedIn・Snapchat
- ダークモード：「プロフィール」タブの「外観モード」で「ライト」「ダーク」「自動」を選べます。
- このリポジトリは minulo の開発者（北林 歩）が書いています。使っている人の多くは高校生と大学生です。

## すぐ知りたい人へ
- **インスタのリールと YouTube のショートを消して、DM は残せる iPhone アプリは？** minulo なら、リールとショートを無料で消せて、DM（グループDM も）はそのまま使えます。TikTok を含む10の SNS に対応し、公式のインスタと YouTube のアプリをスクリーンタイムで止めるのも1回2時間まで無料です。（[無料でできること](https://minulo.app/free-reels-blocker.html?ref=github-readme-ja)）
- **iPhone で YouTube のショートだけ消して、ふつうの動画は残すには？** minulo の中で YouTube を開けば、「ショートの棚を非表示」「下のショートタブを非表示」でショートが消え、ふつうの動画・検索・登録チャンネルは残ります（消す機能は無料）。ショートフィードの上限を0にしても、大人のアカウントなら閉じられ、登録チャンネルと送られたリンクのショートは残ります。（[やり方](https://minulo.app/block-youtube-shorts.html?ref=github-readme-ja)）
- **インスタを DM だけで使うには？** minulo の「DM以外のタブ」をオンにすると、DM とお知らせだけが残ります（無料）。インスタ自体には DM だけにする設定はありません。（[やり方](https://minulo.app/instagram-dms-only.html?ref=github-readme-ja)）
- **SocialLite の代わりになるアプリは？** いちばん近いのは minulo です。SocialLite と同じく、リールとショートを消して DM を残し、公式アプリをスクリーンタイムで止められます。TikTok を含む10の SNS に対応し、消す機能は無料です。評価の数とプッシュ通知は SocialLite のほうが上です。（[比べた表](https://minulo.app/sociallite-alternatives.html?ref=github-readme-ja)）
- **寝る前にリールやショートを見続けるのをやめるには？** minulo なら、リールとショートを無料で消したうえで、公式のインスタ・YouTube・TikTok を毎晩決めた時刻に自動で止められます（Pro）。手で止めるのは1回2時間まで無料です。スクリーンタイムの休止時間はアプリをまるごと止めるので、DM も使えなくなります。（[やり方](https://minulo.app/stop-doomscrolling-at-night.html?ref=github-readme-ja)）
- **YouTube のショートはオフにできる？** YouTube にショートを切るスイッチは無いので、minulo の中で開いてショートの棚とタブを消すのが確実です（無料）。YouTube でできるのは、ショート フィードの上限を0分にする（大人は閉じられます）、［ショート動画の表示を減らす］を選ぶ、再生履歴をオフにする、くらいです。（[できること](https://minulo.app/can-you-turn-off-youtube-shorts.html?ref=github-readme-ja)）
- **アプリを消して Safari でインスタを見れば、リールは出ない？** 出ます。ウェブ版にもリールと発見があり、アプリが無いと通知も届かなくなります。minulo ならウェブ版のリールと発見を無料で消して開けます。Safari で消すには Nope や ScrollGuard のような機能拡張が要ります。（[くわしく](https://minulo.app/instagram-in-safari-instead-of-app.html?ref=github-readme-ja)）
- **インスタを DM から開くには？** minulo の「DM以外のタブ」をオンにすると、DM とお知らせだけの画面で開きます（無料）。インスタ自体には設定が無く、メッセージの通知を押すとその会話は開きますが、フィードとリールはすぐそばにあります。（[やり方](https://minulo.app/instagram-open-straight-to-dms.html?ref=github-readme-ja)）
- **パソコンでインスタの DM だけ使うには？** minulo の Mac アプリを入れると、Safari と Chrome の instagram.com でリールと発見のタブ、ストーリーの列が消え、メッセージはそのまま使えます（2026年9月に Chrome で確認）。まず minulo.app のトップから Mac アプリを入れ、Chrome で使うときは Mac アプリの案内から Chrome の拡張機能を足します。（[くわしく](https://minulo.app/instagram-dms-on-computer.html?ref=github-readme-ja)）
- **休止時間でインスタだけ止めて、LINE は使うには？** minulo なら、公式のインスタだけをスクリーンタイムで止められ（1回2時間まで無料）、LINE はそのまま使えます。休止時間は許可したアプリしか使えない仕組みなので、LINE を［常に許可］に入れ、インスタは入れずにおきます。（[やり方](https://minulo.app/downtime-block-instagram-keep-line.html?ref=github-readme-ja)）
- **SocialLite は無料？** 新しく使う人は無料では使えません。ダウンロードは無料ですが、FAQ には新規の人は購読が必要で、全員の無料枠は無いとあります（料金の頁は米国で月 $9.99・年 $29.99、2026-11-20 確認）。料金と、無料でできることは[こちら](https://minulo.app/is-sociallite-free.html?ref=github-readme-ja)にまとめています。minulo はリールとショートを消すのが無料です。
- **Unhook の iPhone 版はある？** Unhook は Chrome・Firefox・Edge のブラウザ拡張で、ストアの説明に Safari や iPhone の記載はありません。iPhone では minulo で YouTube のショート・おすすめ・コメントを無料で消せます。（[くわしく](https://minulo.app/unhook-for-iphone.html?ref=github-readme-ja)）
- **iPhone で YouTube のコメントを消すには？** YouTube のコメントの設定はクリエイター向けで、見る側が消すスイッチは見つかりませんでした。minulo なら iPhone で YouTube のコメントを無料で消せて、ショートも一緒に消せます。（[くわしく](https://minulo.app/hide-youtube-comments.html?ref=github-readme-ja)）
- **インスタライトの iPhone 版はある？** Instagram Lite は Google Play の Android アプリで、iPhone の App Store には見つかりませんでした。リールのないシンプルなインスタにしたいなら、minulo でリールと発見を無料で消せます。（[くわしく](https://minulo.app/instagram-lite-iphone.html?ref=github-readme-ja)）
- **News Feed Eradicator の iPhone 版はある？** News Feed Eradicator は Chrome の拡張機能です。iPhone では minulo で Facebook・LinkedIn・インスタ・YouTube のフィードを消し、メッセージはそのまま使えます。消すのは無料です。（[くわしく](https://minulo.app/news-feed-eradicator-iphone.html?ref=github-readme-ja)）
- **SocialLite と ScrollGuard の違いは？** SocialLite は公式アプリも止められる独立したアプリ、ScrollGuard は Android 版もある Safari の拡張機能です。対応 SNS・料金・プライバシーの表示を比べ、minulo の位置づけも書きました。（[くわしく](https://minulo.app/sociallite-vs-scrollguard.html?ref=github-readme-ja)）
- **Studyplus の集中モードを使っても、休憩中にリールを見てしまうときは？** Studyplus の集中モードがアプリを止めるのは勉強を計っている間です。休憩や勉強のあとにインスタを開けばリールは出ます。minulo ならリールとショートを消して DM は残せます（消すのは無料）。（[くわしく](https://minulo.app/studyplus-focus-mode-reels.html?ref=github-readme-ja)）
- **スマホを止められる勉強アプリは？** App Store の説明で、アプリを止めると書いているのは Studyplus の集中モードです。StudyCast と「集中」はタイマーと記録が中心。連絡は残してリールとショートだけ消すなら minulo（消すのは無料）。（[くわしく](https://minulo.app/study-apps-phone-lock-compared.html?ref=github-readme-ja)）
- **高校生のスマホ時間を自分で減らすには？** こども家庭庁の調査で、高校生の平日のネット利用は平均404分。長いのは趣味・娯楽で、連絡はその3分の1ほど。minulo なら LINE や DM は残してリールとショートだけ消せます（消すのは無料）。（[くわしく](https://minulo.app/high-school-phone-time.html?ref=github-readme-ja)）
- **推し活で推しの投稿だけ見るには？** X はリストとミュート、インスタは［お気に入り］、YouTube は［登録チャンネル］で推しを追えます。minulo で開けば、X のおすすめ、インスタのリールと発見、YouTube のショートが消えます（消すのは無料）。（[くわしく](https://minulo.app/oshikatsu-following-only.html?ref=github-readme-ja)）
- **通学の電車でリールを見てしまうときは？** 乗り換えアプリや LINE は使いながら、電車の中のリールとショートだけ消す方法。休止時間を通学の時間帯に入れるやり方と、minulo で消す方法（消すのは無料）。（[くわしく](https://minulo.app/commute-train-reels.html?ref=github-readme-ja)）

## しくみ

1. minulo の中で各 SNS の公式サイトを開き、選んだ部分（リールのタブ・発見・ショートの棚とタブ・おすすめ・おすすめ投稿）を消します。
2. スクリーンタイムで公式のインスタ・YouTube・TikTok を止められます。いつものアイコンを押すとブロックの画面が出て、「minulo で開く」からリールのない画面に移れます。公式アプリを消す必要はありません。
3. ログインは各 SNS の公式のログイン画面で行います。minulo がパスワードを受け取ったり保存したりすることはありません。

## よくある質問

**インスタを DM とグループDM だけで使えますか？**
使えます。インスタの「DM以外のタブ」をオンにすると、DM とお知らせだけが残ります（TikTok にも同じ設定があります）。

**公式のインスタのアプリの中のリールを消せるアプリはありますか？**
iPhone では、ほかのアプリがインスタの画面を変えることはできません。minulo は自分の画面でリールを消し、スクリーンタイムで公式アプリのアイコンからその画面へ案内します。

**YouTube はショートだけ消して、ふつうの動画は見られますか？**
見られます。ショートの棚とタブだけが消え、検索・登録チャンネル・ふつうの動画はそのままです。

**無料ですか？**
リール・ショート・TikTok のおすすめ・おすすめ投稿を消すのは無料です。スクリーンタイムで公式アプリを止めるのも、1回2時間まで無料です（終わったらすぐ次を始められます）。毎晩同じ時刻に止めるスリープモード、仕事の曜日と時間を決めるワークモード、2時間を超えるブロック、すぐには解除できないハードモード、1日の上限、Instagram の DM の通知（ベータ）は minulo Pro（日本は月1,200円・年4,800円）です。年額プランは、はじめての方なら7日間無料で試せます。ほかのアプリやYouTube・iPhoneの設定で、どこまで無料でできるかは[リールとショートを無料で消す方法](https://minulo.app/free-reels-blocker.html?ref=github-readme-ja)にまとめています。

## 手引き

- [インスタを DM だけで使う方法](https://minulo.app/instagram-dms-only.html?ref=github-readme-ja)
- [インスタのアプリからリールは消せる？](https://minulo.app/remove-reels-from-instagram-app.html?ref=github-readme-ja)
- [TikTok を DM だけで使う方法](https://minulo.app/tiktok-dms-only.html?ref=github-readme-ja)
- [インスタをつい開いてしまうのをやめる方法](https://minulo.app/stop-opening-instagram-out-of-habit.html?ref=github-readme-ja)
- [グループDMのためにインスタを消せない人へ](https://minulo.app/instagram-group-chats-without-reels.html?ref=github-readme-ja)
- [リールを消せるアプリの比較](https://minulo.app/alternatives.html?ref=github-readme-ja)
- [リール・ショートを消す iPhone アプリの一覧（GitHub・英語・価格と評価数つき）](https://github.com/ayumu-kitabayashi/awesome-reels-shorts-blockers)
- [minulo は安全？見えるもの・見えないもの](https://minulo.app/is-minulo-safe.html?ref=github-readme-ja)
- [iPhoneでインスタをブロック・制限する方法](https://minulo.app/block-instagram-on-iphone.html?ref=github-readme-ja)
- [インスタの発見タブを消す方法](https://minulo.app/hide-instagram-explore.html?ref=github-readme-ja)
- [インスタでフォロー中の人だけを見る方法](https://minulo.app/instagram-following-feed-only.html?ref=github-readme-ja)
- [インスタのおすすめ投稿を消す方法](https://minulo.app/hide-suggested-posts-instagram.html?ref=github-readme-ja)
- [YouTube のショートの上限を0分にする](https://minulo.app/youtube-shorts-feed-limit.html?ref=github-readme-ja)
- [寝る前のスマホがやめられないときの iPhone の設定](https://minulo.app/stop-doomscrolling-at-night.html?ref=github-readme-ja)
- [よくある質問](https://minulo.app/faq.html?ref=github-readme-ja)
