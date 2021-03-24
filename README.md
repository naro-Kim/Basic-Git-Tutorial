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

//Git Branch의 개요

- Master Branch에서 Develop Branch, Bug Fix Branch등 다른 목적의 브랜치를 가지치기한다.
- 이를 통합 브랜치 / 토픽 브랜치라고 일컫는다.
