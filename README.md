# 작업환경 세팅 순서
이 작업은 한 인원이 생성한 organization과 repository가 있다고 가정한 이후의 순서입니다.

## 1. 각 로컬에서 git 활성화하기
각 os에 맞는 git 설치 방법을 통해, pc에 git을 설치합니다.
설치가 완료되었으면 ``git -version``을 통해 제대로 설치되었는지 확인하고(되도록 같은 버젼으로 통일하는 것을 권장)

windows는 powershell, mac은 terminal 같은 프로그램으로 내가 git으로 형상 관리를 할 폴더 위치로 이동해서, git init 명령어를 통해 현재 이 폴더를 git으로 관리할 local repository로 활성화하기

## 2. github에 있는 remote repository 가져오기
작업폴더에서 git clone 명령어를 통해 원격에 있는 레포지토리를 클론해옵니다.
클롭해오면 이미 원격 브랜치랑 연결되어있는 최신 소스코드 상태를 확인할 수 있음

``
git clone https://github.com/dongheon-jinju/cat-talk-to-me.git 
``

## 3. 작업 시, 명령어 

git add -> 작업한 내용들 staging zone으로 등록하기
git commit -> 커밋 메세지로 어떤 작업을 했는지 기록 후, 커밋 등록하기
git push -> 연결된 원격 브랜치로 push하기
- git push 명령어만 사용할 경우, git push origin main 명령어와 같이 현재 메인에서 메인으로 업데이트 됩니다.
- 

배가 고프고 졸려요