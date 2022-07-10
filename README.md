## Laravelプロジェクト作成
`composer create-project laravel/laravel app --prefer-dist`

## Dockerデーモンの起動
`sudo service docker start`

## ローカルでコンテナに入る
`UID_GID="$(id -u):$(id -g)" docker-compose up -d --build`