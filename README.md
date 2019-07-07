# Git Basic
poo
## config
```
git config --global user.name ”(your name)"
git config --global user.email "(your email)"
git config --global color.ui true
git config -l (git config —list)
git config --help
git help config
```

## Getting Started
```
$ touch README.md
$ git init　（初期化する）
$ git add README.md　（ステージングディレクトリに登録）
$ git commit -m "first commit"　（ローカルリポジトリにコミット）
$ git remote add origin https://github.com/kiyo0123/gae-python.git （リモートリポジトリを登録する）
$ git push -u origin master （リモートリポジトリにプッシュする） 
```
ファイルを作成して登録するには
```
$ git add <filename>
 git add . ディレクトリ配下をすべて対象とする
$ git commit -m "comment"
$ git push -u origin master 
```
をすればOK

変更履歴を確認する
```
git log --oneline
git log -p
git log --stat
```
