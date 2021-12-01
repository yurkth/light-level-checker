# Light Level Checker

Minecraftで敵が湧く明るさを確認できるデータパックです。

![](https://user-images.githubusercontent.com/59264002/144288799-4c1273fb-fb79-47b7-b3ee-ec8101079612.png)

## 対応バージョン

Minecraft Java Edition 1.17.x - 1.18.x

## 使い方

[Releaseページ](https://github.com/yurkth/light-level-checker/releases)からダウンロードできるzipを`.minecraft/saves/<world-name>/datapacks/`に配置することで使えるようになります。

本データパックはオフハンド(左手)に松明を持っている間のみ動作します。  
データパックの動作中は、プレイヤーの周囲11x5x11の範囲にある、明るさが0の座標に白く光るパーティクルが表示されるようになります。

[1.18以降ではブロックの明るさが0の座標に敵Mob(一部除く)が湧く](https://twitter.com/_Ulraf_/status/1414985600273428480)ため、パーティクルが出ないように光源を配置することで湧き潰しができます。

## FAQ

- 松明を置いていないのにパーティクルが出ません。
  - データパックで取得できる明るさは、日光(月光)と光源による明るさの大きい方のみになります。  
  そのため、空の下にある場所ではうまく動作しません。洞窟内のような空からの光が入らない場所で使ってください。

## 開発者向け

気が向いたらブログに詳しい動作について書くかもしれません。

## ライセンス

本データパックはMITライセンスで提供しています。詳しくは[LICENSE](https://github.com/yurkth/light-level-checker/blob/master/LICENSE)を見てください。
