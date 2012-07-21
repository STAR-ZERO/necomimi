git cheat-sheet by necomimi group

# commit
インデックス(ステージ)上のコンテンツをユーザーのメッセージと共にリポジトリに保存します。

## 例
`git commit -m "hogehoge"`  hogehogeというコミットメッセージと共にコミットする


# add
新しいファイルや修正したファイルをインデックスに追加する

    git add <filepattern...>

- filepattern
インデックスに追加するファイルを指定します


# diff
読み方：でぃふ
ファイルに加えられた変更点を表示する

$ git diff ＜変更を確認したいファイル＞

例）file1.txtとfile2.txtの差分が表示される
`$ git diff -- file1.txt file2.txt`


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

