## 静的サイトの作成方法

### 環境構築
```shell
yarn create vite projectFolder
cd projectFolder
yarn
#ルーティングのためのライブラリ
yarn add react-router-dom
#bootstrapのインストール
yarn add react-bootstrap bootstrap
```

### 開発サーバーの起動
```shell
yarn dev
```
リロードは、rを押す。 (一応ホットリロード)
終了時は、qを押す。

### gitへのpush (Viteの場合)
```shell
git init
git remote add origin  "URL"
git branch -M main
git add .
git commit -m "commit msg"
git push -u origin main 
```