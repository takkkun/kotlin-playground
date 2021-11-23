# Kotlin Playground

Kotlinをおためしで書くための環境です。公式の[Kotlin Playground](https://play.kotlinlang.org/)となんら関係ありません。

## 必要なもの

- JDK 11

## IntelliJ IDEAでの実行方法

このリポジトリをクローンし、IntelliJ IDEAで開きます。

あとはMain.ktファイルを対象に実行ボタンを押すだけで実行できます。

## コマンドラインでの実行方法

このリポジトリをクローンし、リポジトリのディレクトリまで移動します。

あとは下記のコマンドで実行できます。

```
$ ./gradlew jar && java -jar build/libs/kotlin-playground.jar
```