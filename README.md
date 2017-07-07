個人プロジェクト制作物デモ大会・プログラム
========

* 日時: 2017年7月13日(木) 16:50-18:20 (9-10限)，14日(金) 16:50-18:20 (9-10限)
* 場所: 専攻講義室 (大岡山西8号館E棟10F)
* デモ: 1件7分 (発表・デモ5分，質疑1分，交代時間1分)

## 7月13日(木) 16:50-18:20

### イントロダクション

### MeatSommelier (石井 康嗣)
カメラで撮影した肉の写真に点数をつけてくれるアプリです。Google Cloud Vision APIにより画像内の肉を識別し、A3RT Image Influence APIにより点数付けを行います。

### TitechApp (大村 雅一)
東工大生専用のポータルアプリです。東工大での生活を便利にする以下のような機能があります。
* 東工大ポータルへの自動ログイン
* 授業カレンダー(OCWiカレンダー)の自動取得と表示
* TokyoTech Wifiへの自動ログイン
* 取得している授業情報に基づいたPDF保存&ビュアー

### 曲線描画補助ツール (長田 晃太朗)
ベジェ曲線などの図形をカメラによって得られた画像の上に表示する。図形は画面上で自由に動かすことができる。紙などをカメラで写した上に図形を置き、それをペンなどでなぞることで、きれいな図形を描くことができる。紙などと端末の位置がずれると図形もずれてしまうことが予想されるが、今回の実装では端末を台などに置いて固定して使用することを想定し、マーカーなどを用いた補正は今後の課題とする。

### RSSリーダー（仮） (賀来 智博)
特定サイトのフィードを取得して表示を行なうアプリ

### 洗濯お天気アプリ (北脇 知春)
一人暮らしの大学生は洗濯物をある程度まとめて洗濯するが，天気予報を見ながらちょうど良い洗濯日間隔となるように調整するのが面倒である．特に，洗濯出来る日が限られる梅雨の時期は問題の制約が厳しい．そこで，位置情報からその場所の天気を取得し，最後に洗濯した日や最大の洗濯日間隔を参照して，いつ洗濯をすれば良いのかをサジェストしてくれるアプリケーションを開発した．

### かくれんぼ支援アプリ (鈴木 蕗由)
かくれんぼで鬼からの逃走を支援するandroidアプリです。Bluetoothを利用して、あらかじめ鬼のもつBluetooth機器とペアリングを行っておきます。かくれんぼ中、鬼が検出可能な距離まで近づくと、逃げ手のもつandroidの画面に警告が表示されます。鬼が近くにいることを知らせてくれます。

### Twitterクライアント (高桑 健太郎)
Twitterを利用するためクライアントです。タイムラインの閲覧、ユーザーのフォロー、投稿やその他アクション等といった基本的な機能を備えています。

### コレヤス? (中村 晃大)
実際の販売店の商品をカメラで撮影し、その商品のネットで取引されている価格などの情報を表示するアプリ。Google Cloud Vision APIによる画像認識、及びAmazon Product Advertising APIを用いて実現する。

### 図書情報取得アプリ (林 孝紀)
本についているバーコードを読み取り、APIを通じてその本に関するデータを取得するアプリ

### QuickTODO (Lyu Kaixie)
毎日の行動と発想をTODOの形で管理するアプリです。複数のリストにより管理するTODOアプリはわかりづらい上、TODO作成するときは日時やカタログなど一々入力しなければならず、とってもめんどくさいです。QuickTODOは、タイトルだけのTODOも作成できるし、日時や詳しい内容を含めのTODOも作成できます。さらに、Google Calendarとの連携ができます。タスク管理がもっと便利になるアプリだと思います。

### Habit Timer (高橋 勇人)
習慣の時間管理をする時、どうしていますか？ スマホのタイマーでは、毎回分刻みのタイマーを一回一回設定する必要があって、毎日する習慣のタイマーには使えないですよね。このアプリケーションを使えば、習慣化された作業一つ一つに時間管理タイマーを作ることができるから、例えばスポーツなら10分間ストレッチして20分間基礎練、30分間試合をして10分間整理ストレッチ、といった流れをタイマーで管理できます！


## 7月14日(金) 16:50-18:20

### ランニング音楽 (下條 拓未)
ランニングをしている際に最適な曲を提案するアプリケーション。最初にその日の気分を選択し、走るペースに合わせてBPMを割り出し、気分とそのBPMから音楽を検索し、再生する。

### TrackballEmulator (小貫 直之)
カメラをトラックボールに見立てて、カメラの前で指を動かすと画面をスクロールさせます。アプリ内のウェブブラウザでのみ動作。

### 待ち合わせアプリ (木下 崇央)
GPSを用いて同じグループのメンバーの現在位置を知ることができるアプリ。メンバーの現在位置を知ることで、混み合った場所やわかりにくい場所で待ち合わせをする時にも簡単に集合できるようにする。既に存在するグループに参加したり、新しいグループを作ったりすることもできる。

### あいまい距離検索 (實成 優馬)
ユーザーの感覚に対応した飲食店検索を実装したアプリです.まず, 現在地から｢今の気温, 体力など様々な状況を考慮した場合, あの地点までなら歩ける｣という基準地点をユーザー側に指定してもらいます.するとアプリ側がその基準地点までの直線距離を算出し, その距離内にある飲食店を提案するというシステムです.

### GPS Mountain View (高木 豪)
自分のまわりの山に興味を持ってもらうためのアプリ。GPSを用いて取得した位置データを元に向いてる方向の山の稜線(外形)をグラフ出力します。山登りをした時にやまびこを飛ばす山の詳細も取ることで山知識を増やしていけます。

### 水人用経路提案アプリ (福田 彗佑)
世の中には目的地に移動ためには泳ぐこともいとわないという人がいるかもしれない。そこで、本アプリでは泳ぎも考慮した経路案内を行う。

### シンプルお絵かきチャット (舟木 亮介)
複数人が同じキャンバスに同時に絵を描くことができるお絵かきチャットです。描いた線がリアルタイムに他の端末の画面に同期されます。シンプルで直感的に使えるようなUIを目指します。言葉だけでは伝わりづらいような場面でも、このアプリを使えばどこでも手軽に絵で伝えることができます。

### その日のお天気通知アプリ (松崎 大輝)
朝，天気予報などを見ずに家を出て，帰宅の際に雨が降っていて困った経験が誰しもあると思います．傘が必要になりそうな場合は，このアプリが自動的に通知してくれるので，天気予報を見れなくても安心です．

### SimpleMultiModalMemo (SM3) (Dong Hyun Hwang)
このアプリケーションは、文字列だけでなく、写真、手がき絵、ビデオ、音声を同時にサポートするマルチモーダルメモアプリケーションである。既存のものとしてOneNote、Keepのようなマルチモーダルメモアプリは存在したが、様々な機能を提供するためにアプリケーションが重くなり、UIの直観性が低下する問題があった。このアプリケーションは、UIを簡素化して、ユーザーがメモアプリケーションを使用する主な目的である操作が簡単で、メモを早めに多様なマルチメディアを介して行うことができるよう支援する。

### クロージング・ピザパーティー
