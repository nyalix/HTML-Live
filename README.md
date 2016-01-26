# HTML-Live

- HTMLとCSSのスケルトンを生成

- ファイルの更新を監視し、更新があれば自動的にブラウザをリロードする

- 必要なライブラリを自動的にダウンロードする

### Warning
This software is still BETA quality.

### 準備(Mac OS X)
node.jsとnpmパッケージをインストールする

```
$brew install node

$npm install -g jade stylus gulp browser-sync gulp-jade gulp-stylus nib
```

### 使い方

```
$./html-live

$gulp
```
Ctrl+Cでgulpを停止する


see also
- gulp https://github.com/gulpjs/gulp
- stylus https://github.com/stylus/stylus/
- jade https://github.com/pugjs/jade
- nib https://github.com/tj/nib
