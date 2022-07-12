# GitをダウンロードしてGitHubを使ってみファイル管理をしてみよう01

## Windows
1. まず,[Gitをインストール](https://git-scm.com/download/win)する 
-   ![](fig/dl_link.drawio.svg)
2. 64ビットをインストールしてください
3. ダウンロードした,installerを実行してください
4. next → next → ここでとまる
- ![](fig/bash.drawio.svg)
5. 一番下の`(NEW!)Add a git Bash Profile to Windows Terminal`のチェックボックスにチェックを入れてください
6. 以降は全部`next`を押して、`install`を押してください

### Git bash profile
1. Windowsメニューから`Git`のフォルダをクッリク,その中の`Git Bash`をクリック
-  ![](fig/git_bash.drawio.svg)
2. `Git Bash`を開くと`Terminal`が開きます
3. 開いたら,`profile設定`共通部分をしてください


## Mac
- `Mac`ではコマンドで`Git`をインストールします
1. `Git`が入っているかどうか`Terminal`から確認します コマンド → `git --version`
2. 入っていない場合は,`Homebrew`からGitをインストールします,入っている場合は`profile設定`に飛んでください
3. `brew install git`を入力しインストール,インストール後確認`git --version`


## profile 設定 Mac $ Windows 共通 (WindowsはBash ,MacはTerminal)
1. ユーザー名(`user.name`)とメールアドレス(`user.email`)を登録します
2. `git config --global user.name "自分だとわかる名前を入れてください"`を打って`Git`にユーザー名を登録します
`Git`にユーザー名を登録しておくことで、コミット時の名前を表示できます
- *例* `git config --global user.name "Yoshiki"`
3. `git config --global user.email "自分のメールアドレス入力してください"`を打って`Git`にメールアドレスを登録します
- *例* `git config --global user.email "wtfWasThat@gmail.com"`
4. 登録確認のために`git config --global --list`を打って確認してください,登録した内容が表示されればOKです


### `Git Hubでファイルを管理してみよう`に続きます