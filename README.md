# Basic WorkFlow
```sh
$ git add .
$ git status
$ git commit -m '짧고 간결하게 현재형'

# github, bitbucket, gitlab, ... remote repo 생성
$ git remote add orgin <REMOTE REPO URL.git>
$ git push (-u origin master)

# 다른 컴퓨터
$ git clone <REMOTE REPO URL.git> # downloadZIP

# 명령어 줄 줄이기
$ git add . && git commit -m 'SG' && git push
$ git add .  ; git commit -m 'MSG' ; git push
```