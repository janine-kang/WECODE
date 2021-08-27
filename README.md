# GIT 명령어 정리
- git remote add origin <URL 주소>
- git remote -v

=> git remote add를 통해 원격저장소와 자신의 리포지토리를 연결한다. 연결여부는 두번째 명령어인 git remote -v로 확인할 수 있다.


- git add .
- git commit 또는 git commit -m "<message>"
- git push origin <branch name>

=> 자신의 작업 내용을 리포지토리에 업로드하는 명령어 순서이다. add .를 통해 해당 폴더 내 파일을 복사하고 Commit을 통해 원격 저장소에 저장한다. 이후 push 명령어로 원하는 브랜치에 작업 파일을 업로드하는 방식이다. 
