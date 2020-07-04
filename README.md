# git 사용법

`git init`   
- 현재 디렉토리를 git 로컬저장소로 만들기
- 이때 .git 디렉토리가 생성되고 여기에 버전정보가 저장됨   
_ _ _
`git status`   
- 현재 파일들의 추적 상태 출력      

- 파일의 상태는 아래와 같다   
  - untracked : git이 추적하지 않는 상태
  - modified : git이 추적하고 있고, 수정된 상태
  - unmodified : git이 추적하고 있고, 수정되지 않은 상태
  - staged : git이 추적하고 있고, 수정되었으며, `git add` 하여서 commit 될 준비가 되어있는 상태   
_ _ _
`git add <file>`   
- git이 해당 파일을 추적한다
_ _ _
`git config --global user.name "your name"`   
`git config --global user.email "your email"`
_ _ _
`git commit -m "your commit message"`
_ _ _
`git push`
_ _ _
`git pull`
_ _ _
`git remote -v`
- 원격저장소 정보 출력   
_ _ _
`git fetch --all`   
`git reset --hard origin/master`   
- 원격저장소로 로컬저장소 덮어쓰기   

_ _ _
`git log`

_ _ _ 
`git clone <Repository URL>`

_ _ _
`git reset --hard "version ID"`
_ _ _

`git branch <branchname>`
_ _ _
`git branch`
_ _ _
`git checkout <branchname>`
_ _ _
