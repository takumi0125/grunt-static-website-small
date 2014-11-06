grunt-static-website-small
===============================

静的サイト (小規模) 制作用の汎用gruntタスクテンプレートです。

## インストール
```bash
npm install -g bower grunt-cli
```
grunt-cli, bower がインストールされていなければインストール。
```bash
mkdir yourProject
cd yourProject
git clone --recursive https://github.com/takumi0125/grunt-static-website-small.git .
cd grunt
npm install
```

基本的には  
<a href="https://github.com/takumi0125/grunt-static-website" target="_blank">takumi0125/grunt-static-website</a>  
と同じ使用方法です。

基本構造は
<a href="https://github.com/takumi0125/static-website-basic-small-src" target="_blank">takumi0125/static-website-basic-small-src</a>  
を `src`  以下でサブモジュールとして使用しています。


bowerでインストールされる JS ライブラリは、 `js/lib/` に配置されます。
