git cheat-sheet by necomimi group

# commit
インデックス(ステージ)上のコンテンツをユーザーのメッセージと共にリポジトリに保存します。

    git commit [<options>]

# fetch
リモート側で変更をコミットして、そしてその変更を取得します。

    git fetch [<options>] [<repository> [<refspec>...]]


# add
新しいファイルや修正したファイルをインデックスに追加する

    git add <filepattern...>


# diff
ファイルに加えられた変更点を表示する

    git diff

# push
作業内容をリポジトリに送信する

    git push <repository> <your branch>:<sendTo branch>


# status
変更が加えられたファイルを表示する

    git status

# branch
ブランチを表示する。現在のブランチの先頭には米印がつく。

    git branch

指定した名前でブランチを作成する。

    git branch <branch>

指定した名前のブランチを削除する。

    git branch -d <branch>

# clone
既存のリポジトリをコピーする

    git clone <repository>

# pull
ほかのリポジトリの変更点をローカルリポジトリにマージする

    git pull