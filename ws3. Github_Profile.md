# 실습 3. Github Profile README

## 내용

* 로컬에 github username - ex) brenda 로 폴더를 만든다. 

* 안에 README.md 파일을 만든다. 

  * 내용으로 자기소개를 작성한다

  ```ba
  $ touch README.md
  ```

* 커밋을 한다

  ```bash
  $ git init
  $ git status
  $ git add README.mda
  $ git commit -m 'Add README'
  ```

* Github에 github username 으로 원격저장소를 만든다. 

  ```bash
  #만들고 나서 복사
  $ git remote origin http://github.com/brendayoung2/brendayoung2.git
  ```

  

* push를 한다. 

  ```bash
  $ git push origin master 
  ```

  햣 

## 실습 3-1. 업데이트 하기

- 업데이트를 한다? 추가 버전을 만들어야...

- 프로필 수정하고, 커밋

  ```
  $ git status # 수정 사항이 WD
  $ git add .
  $ git status
  $ git commit -m 'Update README - goal'
  ```

- push

  ```
  $ git push origin master
  ```

"07_Branch \354\230\210\354\213\234.md"
