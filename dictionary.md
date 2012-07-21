about fast-forward
======

2つのコミットAとBとがあるときに、コミットAにいたる歴史がコミットBにいたる歴史にすべて含まれている場合、2つのコミットはファーストフォワードの関係にある、とか、コミットAはコミットBにファーストフォワードする、といいます。


# fast-forwardな関係
![fast-forward](http://cdn-ak.f.st-hatena.com/images/fotolife/s/sinsoku/20111025/20111025074941.png)  
コミットBの歴史に、コミットAの歴史が全て含まれている。

# fast-forwardでない関係
![no-fast-forward](http://cdn-ak.f.st-hatena.com/images/fotolife/s/sinsoku/20111025/20111025074946.png)  
コミットBの歴史に、コミットAの歴史が含まれていない（Aのコミットが含まれていない）


[ 図で分かるgit-mergeの--ff, --no-ff, --squashの違い - アジャイルSEを目指すブログ](http://d.hatena.ne.jp/sinsoku/20111025/1319497900)


about alias
======

Gitで使うコマンドを短く呼び出せるように別名を設定できる

    git config --global alias.st status
    git config --global alias.ci commit

上の設定をすると

    git st
    git ci

で、git status , git commit のコマンドを呼び出すことができる


