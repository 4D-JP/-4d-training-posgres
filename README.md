# 4d-training-postgres
4D × PostgreSQL 講習

###講習内容

* 4DからPostgresqlDBへアクセスする方法
* 4DのHTTPクライアントについて

---

MacにPostgreSQLをインストール

http://qiita.com/necojackarc/items/ada0dcbdba633eaa468f

PostgreSQLのTCP API

http://www.postgresql.jp/document/9.5/html/protocol.html

PostgreSQLのHTTP API (draft)

https://wiki.postgresql.org/wiki/HTTP_API

PostgreSQLのRESTクライアント

http://postgrest.com

ソースコード

https://github.com/begriffs/postgrest

ダウンロード

https://github.com/begriffs/postgrest/releases

引数など

http://postgrest.com/install/server/

接続

```sh
postgres://miyako@localhost:5432/postgres \
          --port 3000 \
          --schema public \
          --anonymous miyako \
          --pool 200
```

Advanced REST client

https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo

---

LAUNCH EXTERNAL PROCESS + PSQL

http://www.enterprisedb.com/products-services-training/pgdownload

https://www.postgresql.org/docs/9.0/static/app-psql.html

PostgreSQL Plugin

https://www.pluggers.nl/product/postgresql-plugin/

Simple PostgreSQL Client

https://github.com/miyako/4d-plugin-simple-postgres-client
