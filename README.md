# larashop


### laravelのバージョン確認
```
$ php artisan --version
```

### コンテナ関連
```
・コンテナ立ち上げ(laradock上で)
$ docker-compose up -d nginx mysql phpmyadmin

・コンテナ内に入る(laradock上で)
$ docker-compose exec workspace bash

・コンテナ停止
$ docker-compose stop

```

### 表示確認
```

http://localhost/

・phpMyadmin
http://localhost:8081/
サーバ：mysql //これは固定
ユーザ名:default
パスワード:secret

```