# docker nginx01 - Dockerfileをトラブルシューティングしてみよう

## 問題01

1. 下記コマンドを実行しブラウザで`http://localhost:8080/`と検索し `hello, nginx` が表示されるようにしなさい。

```sh
docker build -t nginx .
docker run --name nginx -it -p 8080:80 nginx

$ /usr/sbin/nginx
```

2. 問題01を解いたあとは下記コマンドで消しておく

```sh
$ exit

docker rm nginx
docker rmi nginx
```

## 問題02

1. 下記コマンドだけでブラウザで`http://localhost:8080/`と検索し `hello, nginx` が表示されるようにしなさい。

```sh
docker build -t nginx .
docker run --name nginx -d -p 8080:80 nginx
```

2. 問題02を解いたあとは下記コマンドで消しておく

```sh
docker stop nginx
docker rm nginx
docker rmi nginx
```