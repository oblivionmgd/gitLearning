---
theme : "night"
transition: "slide"
highlightTheme: "monokai"
slideNumber: false
title: "VSCode Reveal intro"
---

## Githubとは
D5 渡部丈留

---

## そもそもGitって何

---

## Gitとは
- 超便利バージョン管理ツール
- 一人はもちろん、複数人での開発に対応
- 変更を記録して、戻すこともできる
- ちょっと試しにいじってみて、だめだったら戻すってことも可能


---

## Githubとは
- GitのリポジトリをWeb上に置くことができる
- 複数人で作業をスムーズにできる
- もちろん一人でも利用すると便利！

---


### こんなことをしなくても良い!

```
-rwxrwxrwx  1 tabe  staff       0  6  3 11:07 main.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:08 main_tmp_test.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:07 main_v1.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:07 main_v2.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:07 main_v3a.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:07 main_v3b.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:08 main_v5_last.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:08 main_v9_last_last.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:08 main_importantBackup.py
-rwxrwxrwx  1 tabe  staff       0  6  3 11:08 main_NOT_ERASE_BAK.py
```

---

### gitを実際に使ってみよう！

---

#### 3番までやりましたか？
https://learngitbranching.js.org/?locale=ja

---

### 実際にGithubと連携してみる！

---

### 1. git clone
- プロジェクトを自分の環境にコピーする
- 文字通りclone

---

#### 1. git clone

自分がいるディレクトリにダウンロードされる
```
git clone https://github.com/tabe0000/learningGithub
#git clone リポジトリURL
```

---

### 2. git branch
- 自分専用のブランチを切る
- (branch = 枝)

---

### 2. git branch
ブランチを切る
```
git branch hogehoge
#git branch リポジトリ名
```

---

### 2. git branch
pushする前にファイルを追加してcommit
```bash
git checkout hogehoge
touch tabe0000.py
git add ./
git commit -m 'add myfile'
```

---

### 3. git push
- 自分のブランチにをPushする
```
git push origin hogehoge
```

---

### 4. Pull Requestを送る
1. Github.com に移動
2. PRを作成

---

### 5. 承認してmerge
1. 承認してもらったら完了！

---

### 6. git branch -d でブランチを消す
- 不要になったブランチを消す
- margeされていないリポジトリは -Dで消せる

```
git checkout master
git branch -d hogehoge
```

---


### 7. git pull
- 自分の環境を最新版に更新する

```
git pull
```

---

### 以上！　お疲れさまでした！
