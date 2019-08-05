# compose-sample
Node.js と Redis でアクセス数をカウントするアプリケーションをdocker-comopseで起動するサンプルです。

ローカルにクローンしたら、`docker-compose up`で実行することが出来ます。  
ファイルに変更を加えた場合、`docker-compose build`を実行し、再度`docker-compose up`を実行すると変更がコンテナに適応されます。

`docker-compose down`でコンテナをすべてストップさせることが出来ます。

ファイル構成
```
.
├── app-server
│   ├── Dockerfile
│   └── src
│       └── app.js
└── docker-compose.yml
```
