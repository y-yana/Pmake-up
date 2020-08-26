# Pmake-up

## 概要
画像認識を用いて入力画像からあなたの顔の輪郭、パーソナルカラーを診断。診断結果からあなたに合うメイクを提案します！

## 制作メンバー
- Leon Kunishi
- Ryunosuke Ikeda
- Yuuna Yanagida

## 使用技術
- フロント　　　HTML,CSS,jquery,javascript
- サーバー　　　python,Flask
- AI(深層学習)　Tensorfrow+keras

## アプリURL
https://pmup.herokuapp.com/

## サンプル動画URL
https://1drv.ms/v/s!Am9ZA7hA1tK4sHiqtvt21g2YfXF4?e=hhtBe9



## 説明
サマーハッカソンで初めて組んだメンバーでつくった初めてのアウトプットを同メンバーで改良しました！
現在、既存のパーソナルカラー診断等は選択肢で自分の目の色や肌の色を入力して診断を行っていますが、その診断部分を画像認識AIを用いて診断。画像を入力するだけで簡単に診断ができるようになりました。また同時に顔の輪郭まで
診断することができ、パーソナルカラーと顔の輪郭2つの診断結果からあなたに合うあなただけの、メイクや髪形を提案します！

その他の工夫点：診断結果をグラフ表示にし、より直感的に診断結果がわかるようにしました！
また、配色、UIも前回(サマーハッカソン)と比べてかなりこだわりました！

苦労した点：サーバー側とフロント側のデータ（特に画像など）のやり取りが大変でした、またデプロイ時のjsonやjsのpathの指定に苦労しましたが、何とか実装することができました！

技術的にこだわった点：AIの学習部分では人の手で画像取集には限界があるため、簡単な画像処理で水増し等を行い、少ないデータ数を補った。

