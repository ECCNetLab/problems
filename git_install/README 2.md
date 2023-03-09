# GitをダウンロードしてGitHubを使ってみファイル管理をしてみよう01

## GItとは
* Gitを使用することで、複数の人々が同じコードやファイルを同時に編集することができ、変更履歴を追跡し、必要なときに変更を元に戻すことができます。
* 学校でのプロジェクトを管理するときなど、ネト研での問題管理もGitHubで行っています
*  GitHubを今回は、GUIを使って管理していきます、ターミナルに慣れることができればそれが`ベスト`です。

## Windows
1. まず,[Gitをインストール](https://git-scm.com/download/win)する 
 ![](fig/dl_link.drawio.svg)
2. 64ビットをインストールしてください
3. ダウンロードした,installerを実行してください
4. 実行後 , next → next → ここでとまる
- ![](fig/bash.drawio.svg)
1. 一番下の`(NEW!)Add a git Bash Profile to Windows Terminal`のチェックボックスにチェックを入れてください(チェックが入っていないと`Git Bash`が使えないので注意してください)
2. 以降は全部`next`を押して、`install`を押してください

### Git bash profile
1. Windowsメニューから`Git`のフォルダをクッリク,その中の`Git Bash`をクリック
-  ![](fig/git_bash.drawio.svg)
2. `Git Bash`を開くと`Terminal`が開きます
3. 開いたら,`profile設定`をしてください


## Mac
- `Mac`ではコマンドで`Git`をインストールします
1. `Git`が入っているかどうか`Terminal`から確認します コマンド → `git --version`
2. 入っていない場合は,`Homebrew`からGitをインストールします,入っている場合は`profile設定`に飛んでください
3. `brew install git`を入力しインストール,インストール後確認`git --version`
4. > git version 2.38.1


## profile 設定 Mac $ Windows 共通 (WindowsはBash ,MacはTerminal)
1. ユーザー名(`user.name`)とメールアドレス(`user.email`)を登録します
2. `git config --global user.name "Your Name"`を打って`Git`にユーザー名を登録します ,"Your Name" には Git で使用するユーザ名を入力して下さい"
`Git`にユーザー名を登録しておくことで、コミット時のユーザ名を自動で登録してくれます
   - *例* `git config --global user.name "Yoshiki"`
   - *確認*`git onfig --global user.name`を叩いて登録したユーザー名が表示されればOKです
1. `git config --global user.email "Your email"`を打って`Git`にメールアドレスを登録します、"Your email"はGitで使用するメールアドレスを入力してください
   - *例* `git config --global user.email "wtfWasThat@gmail.com"`
   - *確認*`git config --global user.email`を叩いて登録したメールアドレスが表示されればOKです
2. 登録確認のために`git config --global --list`を打って確認してください,登録した内容が表示されればOKです


### `Git Hubでファイルを管理してみよう`に続きます