# firstOrganizationRepo 

## このリポジトリの目的 
バージョン管理システムの1つである Git を Github や SourceTree を通して慣れてもらう為。  
また、個人ではなくグループとして操作していくことに慣れてもらう為。

## 主に使ったコマンド 
コマンドの意味などより詳細な事は Dropbox 内の手順を参照する事。

### インストール直後
```
$ git --version
$ git config --global user.email "you@example.com"
$ git config --global user.name "Your Name"
```

### 一人でお試し（初回）
```
$ cd /c/workspace_git/userName/repositoryName/
$ git init
$ touch README.md
$ vi README.md
$ git add .
$ git commit -m "here memo!"
$ git remote add origin https://github.com/userName/repositoryName.git
$ git push -u origin master
```

### 一人でお試し（2回目以降）
```
$ cd /c/workspace_git/userName/repositoryName/
$ git add .
$ git commit -m "here memo!"
$ git push
```

### みんなでお試し（初回）
```
$ cd /c/workspace_git/organizationName/repositoryName/
$ git init
$ git add .
$ git commit -m "here memo!"
$ git remote add origin https://github.com/organizationName/repositoryName.git
$ git push -u origin master
```

### みんなでお試し（2回目以降）
必ず **pull** を行ってから作業を行う。  
```
$ cd /c/workspace_git/organizationName/repositoryName/
$ git pull -u origin master
$ git add ./changeFileName
$ git commit -m "here memo!"
$ git push -u origin master
```

## このリポジトリでの指令 
Git / Github / SourceTree(Terminal) に慣れてもらい下記を行う
+ リモートリポジトリ に 自身のファイルを **push** する
+ ローカルリポジトリ に グループメンバーのファイルを **pull** する
+ 自身の PC 上 Git ワークスペースに、 **リモートリポジトリと同様のファイル群** が揃う事


以上です。
