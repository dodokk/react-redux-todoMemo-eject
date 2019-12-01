## 概要

reduxを使えるようになりたかったので作り始めたが、webpack.config.jsやtsconfig.jsonといった詳細な設定ファイルがあることから、普段使用している`create-react-app`を用いたピュアな環境でないことが伺える。

具体的には、上記の環境で`yarn eject`コマンドを用いたときの、より詳細な環境を展開した状態になっていると思われる。

よって、ピュアな`create-react-app`環境を用いた別の記事を参考に、新しいリポジトリを作ろうと思う。

## 元記事
https://qiita.com/pullphone/items/fdb0f36d8b4e5c0ae893

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.
