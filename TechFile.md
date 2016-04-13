# TechFile進捗(iPhone)
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

# AndroidをKotlinで実装
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
[お絵かきアプリ](https://github.com/touyou/FingerPaintKotlin)  
メモ帳アプリ  

### 飛ばしたもの
- 時計
- クイズ
- 脱出ゲーム
- テクドラ
- スタンプ

# WebDesign
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

# WebProgramming
[カウントアプリ](https://c9.io/touyou/countlit)→[Web上に公開](https://immense-beach-36337.herokuapp.com/count)  
[ブックマークアプリ](https://c9.io/touyou/bookmarklit)  

# MediaArt
Done: A01, A02, A03, A04, A05, B01, B02a
## メモ
### RGB -> HSB
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
### HSB -> RGB
```
max = B
min = max - ((255 / S) * max)
Hの値60刻みに変わる
```
### Perfumeについて
B02bのプログラムが途中でメモリ解放エラーみたいなんで止まる...?
