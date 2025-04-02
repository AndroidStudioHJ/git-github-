## 250402 git 복습
### 브렌치 이동 방법은? 
```
git switch <브랜치 이름>
```

### 로컬 브랜치를 삭제하려면 어떤 명령어를 사용해야 할까요 
```
git branch -d <브랜치 이름>
```

### git 의 3가지 영역은? 
- working directory
- staging area(state)
- local repository

### working directory 에서 stage 로 올리는 방법은? 
```
git add .
```

### 스테이지에서 로컬저장소로 올리는 방법은? 
```
git commit -m <커밋 메세지>
```

### 로컬 저장소에서 원격 저장소로 올리는 방법은? 
```
git push -u origin main
```

### git remote add origin <본인 레파지토리 링크> 의 의미는? 
>원격 저장소의 위치를 설정 <br>
>본인 레파지토리 링크> 부분을 origin 으로 잡겠다는 의미

### git push --se3t-upstream origin main 의 의미는? 
>로컬 브랜치와 원격저장소 브랜치를 추적관계로 설정후 <br>
>로컬브랜치에 있는 변경사항을 원격저장소로 보낸다

### git push -u origin develop 의 의미는? 
>로컬브랜치 main를 원격저장소origin에 업로드 하면서 <br>
>업스트림 브랜치까지 설정해주는 명령어

### 각각 초기의 default branch 이름은? 
```
git: master
github: main
```

### master 브랜치 이름을 main 이라는 이름으로 바꾸려면? 
```
git branch -m master main 
-m 은 move 라는 의미 
```

### main 브렌치에 new_branch 를 합치려면? 
```
git merge  <브랜치 이름>
```

### A의 원격저장소에서 B의 원격저장소로 복제하는 용어는? 
`Fork`











