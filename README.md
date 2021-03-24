"# Basic-Git-Tutorial"

Date : 2021-03-22
References :https://www.youtube.com/playlist?list=PLRx0vPvlEmdD5FLIdwTM4mKBgyjv4no81

//Git의 필요성

- 원격 저장소를 거쳐서 파일을 관리하므로, 여러 개발자가 동시다발적인 개발 작업을 할 수 있다.
- Commit 관리, Branch 관리등으로 신규 기능을 추가하고 버그 픽스를 할 때, 코드가 꼬이지 않도록 할 수 있다.

//Git의 구조

- Local repository : 데스크탑, 서버와 연결되지 않은 저장소
- Remote repository : 원격으로 데이터를 관리하고 모으는 저장소

//Git 명령어

- git config --global user.name [your user name]
- git config --global user.email [your email]
- git commit -m "message contents"
- git commit --amend
- git push
- git push -f
- git pull
- git merge
- git reset
- git branch

등등

//Git Branch의 개요

- Master Branch에서 Develop Branch, Bug Fix Branch등 다른 목적의 브랜치를 가지치기한다.
- 이를 통합 브랜치 / 토픽 브랜치라고 일컫는다.

- git branch [branch name]으로 새로운 branch를 만들 수 있다.
- git checkout [branch name (master / develop)]으로 현재 로컬 저장소의 파일이 가리키는 branch를 이동할 수 있다.
- git merge [Topic branch name]으로, master branch에 위치해있을 때 타 branch의 파일들을 병합할 수 있다.
- git branch -d [branch name] 으로, 기능을 다한 branch를 삭제할 수 있다.

//Git Branch Conflict

- Branch checkout 후 master branch와 develop branch의 소스가 다를 때 git log의 형태도 다르게 되는데, 이 상태에서 master branch에서 병합할 경우 conflict 발생
