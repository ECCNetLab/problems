# Basic server-lamp01

### #CentOSを使っています
## 問題01


* `curl localhost`をして`welcome to Network-Club`と出るようにしなさい
* 前の問題ができた前提として、`curl localhost` をした時に、`phpinfo`が出るようにしなさい
* MySQLサーバーインストールして、rootでログインしなさい
* MySQL問題ができたことを前提として、MySQLにデータを挿入して、`curl localhost`に接続し、MySQLに挿入したデータを取り出して、表示しなさい

### 以下を調べなさい
- Document rootとは
- /var/www/htmlとは  
- `infophp()`とは
- リポジトリとは


### 説明
LAMP構築
LAMPとは,Linux,Apache,MySQL,PHPの頭もじを合わせて略語で、オープンソースの人気の4つのサービスを合わせたもの
- ![](basic_server.drawio.svg)

- 必須コマンド 　
  - `su` #rootユーザーにログイン
  - `sudo`  #`sudo`を前につけると、rootユーザーで実行
  - `yum install [サービス名]`   でインストールコマンド  
  - `systemctl [status or start or stop or restart ] [サービス名]`  でサービス操作



- 使うであろうコマンド,` vi` ,` cat` ,` cd` ,` mv` ,` cp` 

## 問題2
googleで調べながら設定しなさい

* VirualBoxではなく、自分のブラウザから、ipアドレスを入力して、localhostを見れるようになさい 
* SELinuxをDisableに設定しなさい
* VirtualHostの設定をしなさい

### 以下を調べなさい
- firewallとは、
- SELinuxとは
- ウェルノウンポートとは
- VirtualHostとは
![](https://proengineer.internous.co.jp/topics/wp-content/uploads/2017/08/git23.png)

### 手順

- ヒント : firewall  , httpd.conf  