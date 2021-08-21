# Light Level Checker

Minecraftで敵が湧く明るさを確認できるデータパックです。

![](https://user-images.githubusercontent.com/59264002/130331624-d1301069-97eb-4630-89b2-ea7bbbe97958.png)

## 対応バージョン

Minecraft Java Edition 1.17.x  

## 使い方

[Releaseページ](https://github.com/yurkth/light-level-checker/releases)からダウンロードできるzipを`.minecraft/saves/<world-name>/datapacks/`に配置することで使えるようになります。

本データパックはオフハンド(左手)に松明を持っている間のみ動作します。  
データパックの動作中は、プレイヤーの周囲11x5x11の範囲にある、明るさが7以下の座標に赤いパーティクルが表示されるようになります。

1.17では明るさが7以下の座標に敵Mob(一部除く)が湧くため、パーティクルが出ないように光源を配置することで湧き潰しができます。

## FAQ

- 松明を置いていないのにパーティクルが出ません。
  - データパックで取得できる明るさは、日光と光源による明るさの大きい方のみになります。  
  そのため、日に当たっている場所ではうまく動作しません。夜や洞窟内などの日光が当たらない場所で使ってください。

## 開発者向け

気が向いたらブログに詳しい動作について書くかもしれません。

## ライセンス

本データパックはMITライセンスで提供しています。詳しくは[LICENSE](https://github.com/yurkth/light-level-checker/blob/master/LICENSE)を見てください。