setting
  git config --global user.name "Myessh"
  git config --global user.email "myessh@kakao.com"
  git config --global alias.co checkout 
  git config --global alias.br branch 
  git config --global alias.ci commit 
  git config --global alias.st status 
  git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"


코드올리기
  git init, echo "readme" >> README.md, git add README.md, git commit -m "first commit", git remote add origin ~.git, git push -u origin master?main?
  
코드받기
  git clone https://github.com/~/~.git

branch
  갱신: git remote update, 보기: git branch -a, -r(--remote)
  url보기: git remote -v
  브랜치선택: git checkout branch
  브랜치생성/이동: git checkout -b branch, 브랜치생성(원격): git push origin branch
  로컬/원격브랜치삭제: git push origin :branch
  가져오기: git checkout -t origin/branch
  
