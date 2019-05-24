# Vue.js研究会(第一回目)

## Vue.jsとは
  - JavaScriptフレームワークの一つ
  - MVVMフレームワークで出来ている
  - View特化

## Reactとの違い
  - Reactは大規模開発に向いている
  - Vue.jshは小規模開発に向いている

## Vue-cliとは
  - 初期からBabelとwebpackが入っている
  - GUIがある
  - SPA、PWAの実装が楽

## Babelとwebpackについて
### Babelとは
  - JavaScriptの新しい書き方から古い書き方に変換してくれる
    - IEのために(IEはES5しか使えない)

### webpack
  - 複数のファイルを1つにまとめてくれる
    - エンドユーザー側の表示時間を短縮

## vue-cliを入れてみよう
### Mac版
  - [Homebrewをインストール](https://brew.sh/index_ja)
  ```
  // nodebrewのインストール
  $ brew install nodebrew

  // PATHを通す
  $ echo 'export PATH=$HOME/.nodebrew/current/bin:$PATH' >> ~/.bash_profile

  // .bash_proofileを読み込み
  $ source ~/.bash_profile){}

  // 入っているか確認
  $ nodebrew -v

  // Node.jsのインストール
  $ nodebrew install-binary latest

  // Node.jsのバージョン確認
  $ nodebrew list

  // Node.jsのバージョンを有効化
  & nodebrew use "バージョン番号"

  // 入っているか確認
  $ node -v

  // vue-cliのインストール
  $ npm install -g @vue/cli
  ```

### Windows版
  - [インストーラーをダンロード](https://nodejs.org/en/download/)
  ```
  // 入っているか確認
  > node --version
  ```

  - [gitをダウンロード](https://git-scm.com/)
  ```
  // vue-cliのインストール
  $ npm install -g @vue/cli
  ```
