## html５exp-element

### 使い方

* ソースコードをcloneしてください。
polymer-allはsubmodule構成なので全て取り込みを行ってください。

* htmlを作成します。
サンプルは以下の通りです。

```html
<!DOCTYPE html>

<html>
<head>
    <meta charset="UTF-8">
    <script src="./polymer-all/polymer/polymer.js"></script>
    <link rel="import" href="./html5exp-element.html">
</head>
<body>
<html5exp scale=50% bgcolor=#ffffff fontcolor=#000000 fontsize=1.5em>日本に、もっとエキスパートを！</html5exp>
</body>
</html>
```
* <html5exp>タグの使い方

```html
<html5exp scale bgcolor fontcolor fontsize>文字列</html5exp>
```
  * 文字列 : ロゴの下部に表示させたい文字列
  * scale : 表示されるロゴのサイズ / 1%〜100% / 省略時は100%
  * bgcolor : 背景色 / 省略時は透過
  * fontcolor : 文字カラー / 省略時は黒
  * fontsize : 文字サイズ / 省略時は1.5em