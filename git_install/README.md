# GitをダウンロードしてGitHubを使ってみよう

## Windows
1. まず,[Gitをインストール](https://git-scm.com/download/win)する 
2.  ![](fig/dl_link.drawio.svg)
3. 64ビットをインストールしてください
4. installer.exeを実行してください
5. next → next → ここでとまる
6. ![](fig/bash.drawio.svg)
7. 一番下の`(NEW!)Add a git Bash Profile to Windows Terminal`のチェックボックスにチェックを入れてください
8. 以降は全部`next`を押して、`install`を押してください

### Git bash profile
1. Windowsメニューから`Git Bash`を開きます
2. ![](fig/git_bash.drawio.svg)
3. `Git Bash`を開くと`Terminal`が開きます
4. `user.name`と`user.email`を登録します
5. `git config --global user.name "Your Name"`を打って`Git`にユーザー名を登録します
`Git`にユーザー名を入力することで、コミット時の名前を表示できます
6. `git config --global user.email "Your Email"`を打って`Git`にメールアドレスを登録します
7. 登録確認のために`git config --global --list`を打って確認してください,登録して内容が表示されればOKです

## Mac
1. `Git`が入っているかどうか`Terminal`から確認しましょう {`Git --version`}
2. 入っていない場合は,`Homebrew`からGitをインストールします,入っている場合は4に飛んでください
3. `brew install git`を入力しインストール,インストール後確認{`Git --version`}
4. `user.name`と`user.email`を登録します
5. `git config --global user.name "Your Name"`を打って`Git`にユーザー名を登録します
`Git`にユーザー名を入力することで、コミット時の名前を表示できます
6. `git config --global user.email "Your Email"`を打って`Git`にメールアドレスを登録します
7. 登録確認のために`git config --global --list`を打って確認してください,登録して内容が表示されればOKです


### GitHub 登録/ログイン
1. [GitHub](https://github.co.jp/)のサイトで、アカウントを作成または、ログインしてください
* `注意[` 就職なので`GitHub`のアカウントを見せる場合があるので、Idは自由ですが、変な名前は避けた方がい以下とおもいます。 `]`
