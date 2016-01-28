# HTML-Live

- HTMLとCSSのスケルトンを生成

- ファイルの更新を監視し、更新があれば自動的にブラウザをリロードする

- 必要なライブラリを自動的にダウンロードする

### Warning
This software is still ALPHA quality.

### 準備(Mac OS X)
node.jsとnpmパッケージをインストールする

```
$ brew install node

$ npm install -g gulp browser-sync gulp-jade gulp-stylus gulp-autoprefixer gulp-plumber

```

### 使い方

```
$ ./html-live

$ gulp
```
".jade"と".styl"の状態を監視し、更新があればhtml、cssファイルを生成する


Ctrl+Cでgulpを停止する


see also
- gulp https://github.com/gulpjs/gulp
- stylus https://github.com/stylus/stylus/
- jade https://github.com/pugjs/jade
