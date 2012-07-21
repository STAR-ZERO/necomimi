git cheat-sheet by necomimi group
======


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

* ブランチを表示する: 'git branch'
* ブランチを作成する: 'git branch <branch>'
* ブランチを削除する: 'git branch -d <branch>'

usage: git branch [options] [-r | -a] [--merged | --no-merged]
   or: git branch [options] [-l] [-f] <branchname> [<start-point>]
   or: git branch [options] [-r] (-d | -D) <branchname>...
   or: git branch [options] (-m | -M) [<oldbranch>] <newbranch>
