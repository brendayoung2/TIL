# Github 명령어 정리

1.  프로젝트시작(한번만 설정)
   git init

2. 작업하고 나서
   git add . 
   git commit -m '커밋메시지는 잘 작성하기'

3. 원격저장소 설정(한번만 설정)
   git remote add origin __url__ <= 저장소 처음 만들면 복사 가능

4. 원격저장소 올리기
   git push orgin master

## 기타 명령어

* git status 깃아, 상태를 확인해줘
  git log 깃아, 

* 원격저장소 관련
  git remote -v 
  git remote rm origin  

* git 초기설정
  git config --global user.name <이름>
  git config --global user.email <github등록된 이메일>

### 수정시 필요 명령어

수정시 업데이트를 하고 

추가버전을 만든 프로필 수정을 하고

```bash 
$ git status
$ git add .
$ git status
$ git commit -m 'Update README -goal'
```

