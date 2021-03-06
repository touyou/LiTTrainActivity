# TechFile進捗
## 目次
- [iPhone](#iPhone)  
- [AndroidをKotlinで実装](#Android)  
- [WebDesign](#WebDesign)  
- [WebProgramming](#WebProgramming)  
- [MediaArt](#MediaArt)  
- [Unity](#Unity) 
- GameCreator2D  
- MINECRAFT  
- Movie  
- Anime 
- DTM  
- Miku  
- Designer  
- LINEStamp  

## <a name="iPhone">iPhone
[時計](https://github.com/touyou/ClockLiT)  
[カウント](https://github.com/touyou/CountLiT)  
[電卓](https://github.com/touyou/CalculatorLiT)  
[クイズアプリ](https://github.com/touyou/QuizLiT)  
[なべあつ](https://github.com/touyou/NabeatsuLiT)  
[ガチャアプリ](https://github.com/touyou/GachaTechLiT)  
[クラップ](https://github.com/touyou/ClapLiT)  
[単語帳アプリ](https://github.com/touyou/WordListLiT)  
[バラバラゲーム](https://github.com/touyou/BarabaraGameLiT)  
[フォトマスター](https://github.com/touyou/PhotoMasterLiT)  
[迷路ゲーム](https://github.com/touyou/MazeLiT)  
[テクモン](https://github.com/touyou/TechMonsterLiT)  

## <a name="Android">AndroidをKotlinで実装
※ただしコード素材の無いものに限る  
[カウント](https://github.com/touyou/CountKotlin)  
[タップナンバー](https://github.com/touyou/TapNumberKotlin)  
[電卓](https://github.com/touyou/CalculatorKotlin)  
[じゃんけん](https://github.com/touyou/JankenKotlin)  
[クラップ](https://github.com/touyou/ClapBeatKotlin)  
[まるばつゲーム](https://github.com/touyou/TicTacToeKotlin)  
[もぐらたたき](https://github.com/touyou/TapAMoleKotlin)  
[プレゼントキャッチ](https://github.com/touyou/PresentCatchKotlin)  
[Canvasを試す](https://github.com/touyou/CanvasKotlin)  
[お絵かきアプリ](https://github.com/touyou/FingerPaintKotlin)※MediaScannerConnectionClientがどうしてもエラー出てしまう  
[メモ帳アプリ](https://github.com/touyou/TechMemoKotlin)ActiveAndroidのエラー?  

### 飛ばしたもの
- 時計
- クイズ
- 脱出ゲーム
- テクドラ
- スタンプ

## <a name="WebDesign">WebDesign
（終わったものには左に★をつける）  
★はじめてのWebデザイン  
★ボタンを作ろう  
★コンテンツを作ろう  
★メニューを作ろう  
★全体のレイアウトを作ろう  
★自己紹介サイトを作ろう  
★初級Tips  
★自由なレイアウト  
★サッカーWeb  
★パティスリーWeb  
★アニメWeb  
★illustrator  
★CSSアニメ  
★jQuery  
Photoshop  
  
これらを総合してモックアップから作成し自分の[ホームページ](http://touyou.github.io/)のデザインのリニューアルを行った。

## <a name="WebProgramming">WebProgramming
[カウントアプリ](https://c9.io/touyou/countlit)→[Web上に公開](https://immense-beach-36337.herokuapp.com/count)  
[ブックマークアプリ](https://c9.io/touyou/bookmarklit)  
[家計簿アプリ](https://c9.io/touyou/account_booklit)  
[掲示板アプリ](https://c9.io/touyou/bbslit)→[Herokuに公開](https://hidden-chamber-51142.herokuapp.com/)  
[単語帳アプリ](https://c9.io/touyou/wordboxlit)  
[俳句アプリ](https://c9.io/touyou/haikulit)  
[フォトアルバムアプリ](https://c9.io/touyou/photoalbumlit)  
[アンケートフォーム](https://c9.io/touyou/formlit)  
[JSON+API](https://c9.io/touyou/jsonlit)  

## <a name="MediaArt">MediaArt
Done: A01, A02, A03, A04, A05, B01, B02a, B02b, B02d, B04  
C01〜C05はツールが無いので飛ばす
### メモ
#### RGB -> HSB
```
H = (if maxRGB == minRGB { 0 } else {
      switch(maxRGB){
      case R: (((60 * (G - B)) / (max - min)) + 360) % 360
      case G: ((60 * (B - R)) / (max - min)) + 120
      case B: ((60 * (R - G)) / (max - min)) + 240
      }
      }
S = (max - min) / max * 255
B = max
```
#### HSB -> RGB
```
max = B
min = max - ((255 / S) * max)
Hの値60刻みに変わる
```
#### Perfumeについて
B02bのプログラムが途中でメモリ解放エラーみたいなんで止まる...?

## <a name="Unity">Unity
[PitagoraGame](https://github.com/touyou/UnityTraining/tree/master/PitagoraGame)  
[StopGame](https://github.com/touyou/UnityTraining/tree/master/StopGame)  
[UnityRun](https://github.com/touyou/UnityTraining/tree/master/UnityRun)  
[UnityBall](https://github.com/touyou/UnityTraining/tree/master/UnityBall)  
[SuperUnityMaker](https://github.com/touyou/UnityTraining/tree/master/SuperUnityMaker)  
[FPS](https://github.com/touyou/UnityTraining/tree/master/FPS)  
[FlappyBird](https://github.com/touyou/UnityTraining/tree/master/FlappyBird)  
[TerrainTest](https://github.com/touyou/UnityTraining/tree/master/TerrainTest)  
[TechCraft](https://github.com/touyou/UnityTraining/tree/master/TechCraft)  
