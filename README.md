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

# push
作業内容をリポジトリに送信する

    git push <repository> <your branch>:<sendTo branch>

# status
変更が加えられたファイルを表示する

    git status

