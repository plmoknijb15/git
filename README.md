# git 사용법

`git init`   
- 현재 디렉토리를 git 로컬저장소로 만들기
- 이때 .git 디렉토리가 생성되고 여기에 버전정보가 저장됨   

`git status`   
- 현재 파일들의 추적 상태 출력      


- 파일의 상태는 아래와 같다   
  - untracked : git이 추적하지 않는 상태
  - modified : git이 추적하고 있고, 수정된 상태
  - unmodified : git이 추적하고 있고, 수정되지 않은 상태
  - staged : git이 추적하고 있고, 수정되었으며, `git add` 하여서 commit 될 준비가 되어있는 상태   

`git remote -v`
- 원격저장소 정보 출력   

`git fetch --all`   
`git rest --hard origin/master`   
- 원격저장소로 로컬저장소 덮어쓰기   



