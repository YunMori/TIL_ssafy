# git은 무엇인가?
> 분산 버전 관리 시스템

버전 관리 = 변화를 기록하고 추적하는것

# git의 3가지 영역
1. working directory - 작업영역
2. staging Area - 중간 준비 영역
3. repository - commit이라는 행동을 통해 repository에 버전 기록

버전은 기능별로 기록

# git의 동작

git intit = 워킹 파일을 지금부터 git으로 관리하고 싶어

git status = 지금 git 상태가 어때?

git add (경로)(파일명) = 이 파일들을 staging area에 넣을꺼야
git rm --cached <file> = 너 staging area에 잘못 넣었으면 이거 써서 지워


git config --global user.email "you@example.com"
git config --global user.name "Your Name"        = 그래서 너 누군대?
code ~/.gitconfig = 위에 남긴 이메일, 이름을 변경하거나 지울때

git commit -> 메모장 나옴(버전을 위한 설명(커밋 메세지)) -> i를 누름 -> 메모장 insert mode -> 작성후 esc -> :wq (작성한거 저장하고 나가자) -> commit 완료 = staging area에 있던 파일들을 repository에 저장

git commit -m "(메세지)" = 간단한 메세지만 쓸꺼니까 메모장으로 보내지마ㅋㅋ

""안에 메세지를 쓰는 이유 = 띄워쓰기 때문에 없으면 안써도 되겠지?

git log = author라는 곳에 작성자 일자 메모에 작성한 내용들을 볼 수 있음
git log --oneline = log 한줄 보기
git log --oneline --graph  = 한줄로 보고 싶은데 그래프로 이쁘게 보고 싶네?