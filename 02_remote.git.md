# 원격 저장소(remote repository) 기초

## 기본 설정

* 로컬 git 저장소
* Github remote repository 를 생성



## 명령어

### 원격 저장소 설정

```bash
$git remote and origin 저장소 URL
```

* 깃, 원격저장소(remote) 추가해줘(add)origin 이라는 이름으로 저장소 URL을 
  * origin은 원격저장소 이름 !

### 원격 저장소 목록 보기

```ba
$ git remote -v
origin  https://github.com/brendayoung2/practice1.git (fetch)
origin  https://github.com/brendayoung2/practice1.git (push)
```

### 원격 저장소 설정 삭제하기

```bash
$ git remote rm origin
```

* 깃아, 원격저장소 삭제해줘(remove)origin..을

### push

```bash
$ git push origin master
```

* 깃아, push해줘 origin 원격저장소에 master 브랜치 !