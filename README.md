git cheat-sheet by necomimi group
Last update: 2012.07.21
=======

# init
まずはここから  
リポジトリを作成する  

    mkdir <directory>
    git init

# commit
インデックス(ステージ)上のコンテンツをユーザーのメッセージと共にリポジトリに保存します。

    git commit [<options>]

# fetch
リモート側で変更をコミットして、そしてその変更を取得します。

    git fetch [<options>] [<repository> [<refspec>...]]

# rebase
ブランチの派生元を変更する

    git rebase [-i | --interactive] [options] [--onto <newbase>]
               [<upstream>] [<branch>]
[mergeとrebase(サルでもわかるGit入門)](http://www.backlog.jp/git-guide/stepup/stepup1_4.html)

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
    
# merge
ローカルブランチのマージを行う

    git merge <repository>

# reset
リポジトリをある状態に戻す。<paths>は'git log'で確認する。
インデックスとワーキングツリーも戻す場合は --hard オプションを指定する。

    git rest [--hard] [<paths>|HEAD]

# checkout
ブランチの切り替え

    git checkout <repository>
