### 개발을 하기 위해
* 코드 수정 관리
* 잔뜩 쌓인 파일 관리
* 개발은 혼자가 아닌 다같이

### 버전 관리 필요

### Git
* Git은 버전 관리 및 협업을 위해 사용하는 오픈소스 소프트웨어

### Git 최초 설정

    git config --global user.name "<깃허브 이름>"
    git config --global user.email "<깃허브 이메일>"


### Git으로 폴더 관리

    git init


### 파일을 스테이지로 이동시키기

    git add <파일이름> 
    git add . # 전체파일 


### 파일 커밋하기

    git commit -m "<메모할 내용>"


### 커밋 상태 확인하기

    git status # 커밋을 기다리고 있는 파일 확인
    git log # 커밋이 완료된 파일 확인


### 로컬 repository에 있는 파일을 깃허브에 보내기

    git push origin main


<https://github.com/skt116/skt116>