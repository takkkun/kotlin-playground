# Kotlin Playground

Kotlinをおためしで書くための環境です。公式の[Kotlin Playground](https://play.kotlinlang.org/)となんら関係ありません。

## 必要なもの

- JDK 11

## 実行方法

### IntelliJ IDEA

このリポジトリをクローンし、IntelliJ IDEAで開きます。

あとはMain.ktファイルを対象に実行ボタンを押すだけで実行できます。

### コマンドライン

このリポジトリをクローンし、リポジトリのディレクトリまで移動します。

あとは下記のコマンドで実行できます。

```
$ ./gradlew jar && java -jar build/libs/kotlin-playground.jar
```

## 遊び方

`src/main/kotlin` ディレクトリ以下であればKotlinのファイルを認識するので、ご自由にファイルを追加し、遊んでみてください。

ただしエントリーポイントはMain.ktファイルのmainメソッドに固定されています。これだけは削除しない方が吉です。
