# Git workflow 실습

1계정으로 파일 생성 후 commit & push
git clone <계정2의 레파지토리 주소>
git remote add pair <계정2의 레파지토리 주소>
git pull pair master 로 1계정의 내용을 가져왔다

github 계정을 두개를 같이 하려니 뭔가 꼬인다 ㅠㅠ

작업 복사본에서 git에 의해 추적되지 않은 파일을 포함하여 모든 로컬 변경 사항을 제거하려면 간단히 숨기십시오.

git stash push --include-untracked
