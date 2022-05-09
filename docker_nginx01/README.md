# docker nginx01 - Dockerfileをトラブルシューティングしてみよう

## 問題01

```sh
docker build -t nginx .
docker run --name nginx -it -p 8080:80 nginx

$ /usr/sbin/nginx
```

1. 上記コマンドを実行しブラウザで`http://localhost:8080/`と検索し `hello, nginx` が表示されるようにしなさい。

```sh
$ exit

docker rm nginx
docker rmi nginx
```

2. 問題01を解いたあとは上記コマンドで消しておく

## 問題02

```sh
docker build -t nginx .
docker run --name nginx -d -p 8080:80 nginx
```

1. 上記コマンドだけでブラウザで`http://localhost:8080/`と検索し `hello, nginx` が表示されるようにしなさい。

```sh
docker stop nginx
docker rm nginx
docker rmi nginx
```

2. 問題02を解いたあとは上記コマンドで消しておく