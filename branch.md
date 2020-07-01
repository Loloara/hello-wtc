- Branch
여러 개발자들이 동시에 다양한 작업을 할 수 있게 만들어 주는 기능
각자 독립적인 작업 영역(저장소) 안에서 마음대로 소스코드를 변경 가능
필요에 의해 만들어지는 각각의 브랜치는 다른 브랜치의 영향을 받지 않는다

- Branch 만드는 명령어
$ git branch <브랜치이름>

- Branch 만들고 이동하는 명령어
$ git branch -b <브랜치이름>

- Branch 확인방법
$ git branch

- Branch 전환방법
$ git checkout <branch>

- Branch merge 방법
$ git merge <commit>


### Pull Request

원본 저장소에서 fork, clone을 통해 작업한 내용을 원본 저장소에 반영해달라고 요청하는 것

작업 순서
1. fork 를 통해 원본 repository를 내 repository로 복사한다.
2. clone을 하여 내 로컬 repository로 가져온다.
3. 로컬에서 작업후 commit, push를 하여 작업내용을 업로드한다.
4. pull request를 원본 repository에 보낸다.
