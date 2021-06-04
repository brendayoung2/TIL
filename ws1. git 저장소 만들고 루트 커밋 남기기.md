## 실습1. git 저장소 만들고 루트 커밋 남기기

* practice1 이라는 폴더를 바탕화면에 만들고
* README.md라는 파일을 만든 이후 
* 첫번째 커밋을 남겨보자 !
  * 확인 => git log 

git init

touch a.txt <파일만들기

git init 

git add . 

git commit -m 'Add 파일명' 

git status

git log

> new repository - Repository name - Create repository - ...or create a new repository on the command line 에서

```bash
git remote add origin https://github.com/brendayoung2/test1.git
git push -u origin main
```

git-bash에 복사 붙여넣기 

git remote add origin https://github.com/brendayoung2/practice1.git (깃허브URL)

git push origin master

