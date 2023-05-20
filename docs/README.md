# **shiwasu  師走**

---
### 目次
[1.プロフィール](#プロフィール)<br>[__**2.作品(ポートフォリオ？)**__](#作品(ポートフォリオ？？？))<br>[3.目を通した書籍たち](#目を通した書籍たち)<br>[4.趣味とかの話](#趣味とかの話)<br>[5.デバイス紹介](#デバイス紹介)

---

## **プロフィール**

初めまして。<span style="color: green; ">***shiwasu*****師走**</span>です。<br>ラズパイ等のハードウェアいじってます。<br>生まれつき鼻が効くこと(生理学的に)が唯一のとりえです。<br>昔っからGoogleGlassが好きでウェアラブルとかに興味があります。<br>りすぺくと James Hobson ([Hacksmith](https://www.youtube.com/@theHacksmith))<br><br>~~御覧の通りMarkdownです。友達にデザインこだわれと言われましたが、情報が伝わればいいのです！！！~~<br>→ちゃんとHTML,CSS,JS学びます...
### **所属**
[名工大](https://www.nitech.ac.jp/)-機械工学科-B2 (26卒)<br>[c0de](https://twitter.com/c0demattari) (大学プログラミング部)<br>[niC](https://twitter.com/nitechCreate) (大学プログラミングコミュニティ)<br>

### **触ったもの**
- Windows
- Linux
- Raspberry-pi
- Arduino互換マイコン
    - ESPとか
    - M5Stack製品(これもESP32ではある)
- C
    - 最低限、ポインタやファイル操作は知っています...
- Python
    - OpenCV

### **大学の履修**(※名工大機械)
[履修に関して](major.md)


### **アカウントリンク**

Twitter [@shiwasu_tech](https://twitter.com/shiwasu_tech)<br>GitHub [@shiwasu-tech](https://github.com/shiwasu-tech)

---

## **作品**(ポートフォリオ？？？)
作品とは言い過ぎで、ただただ最低限の動作をするモノ達。

### 1. 出迎えBOT (2023/01)
> OpenCVで顔認識 -> 動画再生<br>[__動画__](https://twitter.com/shiwasu_tech/status/1646877675628396544)<br>*Raspberry-pi&WebCamで作成*

### 2. GPIOとDiscordの連携 (2023/03)
> Raspberry-piのGPIOのHIGH/LOWでメッセージを送信<br>[__動画__](https://twitter.com/shiwasu_tech/status/1640382350239633408)<br>*DiscordBOTの勉強を兼ねて作った。<br>次はリードスイッチとNFCリーダを繋いで[部室](https://twitter.com/c0demattari)の入退室ロガーを作ろうとしている。*


### NULL. LineのメッセージををDiscord内でやりとりするBOT (2023/03 ※断念)
> ~~チャンネル分け等機能性の面でDiscordのほうが使いやすい！ -> LineをDiscord内で使おう！<br>[__(作成中)__]()<br>*LineAPIとDiscord.pyを使ってやろうとしている。が、LineAPIはBOTが全世界に公開されてしまうので誰でも友達追加できてしまう。(フィルター分けはする予定。)<br>まずは個人チャット、次にグループに入れることを考慮して機能を足していきたい。*~~<br><br>2023/06~ Line APIメッセージ送信機能が無料分が月200通となってしまったため、さすがに作っても無に帰すと思い断念。

### 3. 顔の上下で動画の再生停止
> 顔を上げている間は動画再生、下げている間は動画停止<br>[__動画未撮影:RasPi__]()<br>[__動画未撮影:chrome拡張__]()<br>*第一回名工大ハッカソンにて製作。<br>動画のシークバーに停止時のログを残すなどの機能を付加できるという点でOpenCV.jsなど用いてchrome拡張機能として作成することになったが私がJSを書けず、chrome拡張を理解してすらいないがチームメンバーの[Koさん](https://twitter.com/KoCSience)と[みなりんさん](https://twitter.com/minarin0179)と製作中。非力な私は1での製作の経験を活かしRasPiで作成。無論、シークバーにログは残せない。*

### 4. Body Interface
> モーキャプを使わずにデバイスをジェスチャー操作する<br>[__動画__](https://youtu.be/sZ5BhmNm95A)<br>*3での製作から発想を得て、体全体でデバイスを操作できないかと思い始めたプロジェクト。*<br>詳しくは[__**こちらへ**__](body_interface.md)

### 5. HMD Task manager
> Trello APIを使って、タスクをHMDに表示し、タスクの**確認**と***済*属性付与**をできるようにする。<br>[(作成中)]()<br>HMDはマイコンとLCD or OLEDを繋ぎ、反射板を用いて距離を稼ぎつつ表示する。
## 次作る予定のもの
### 99. 実現可能性-**高**
> - ダイヤル式10キーパッド
> - 腕マウスのデータをTensorFlow等にかける
> - mocopi使って何か

### 999. 実現可能性-...
> - 自発的に刺さりに行くコネクタ
> - HoloLensアプリ開発(本体はもちろん持ってないよ！)
---
## **目を通した書籍たち**

(整備中)

### 言語
> **c言語入門　(とある企業の新人教育用書籍)**
> <br>基礎の基礎を学んだ(2022/12)

### Linux
> **新しいLinuxの教科書**
> <br>これはbashの本
### アーキテクチャ
> **Raspberry-piで学ぶコンピュータアーキテクチャ**
> <br>フェライトコアメモリなど古い物から解説してくれる。まだ読み切れてないが、PCの仕組みがわかる。<br>*おすすめ*

### AI
> **AIの教科書**
> <br>もうちょっと古いかもしれない
> B.G.(Bfore-GPT) と A.G.では訳が違う...

### TeX
> **LaTeX美文書作成入門**
> <br>いま現在勉強中

---


## **趣味とかの話**
[趣味とか日記とかいろいろ(整備中)](hobby.md)

---

## **デバイス紹介**
[使用デバイス](devices.md)

---
![](images/shiwasu_icon.png)
