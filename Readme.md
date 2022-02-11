*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: empty ident name (for <juchan@장주영.localdomain>) not allowed


git 사용자야 너 이름이랑 이메일을 나중에 남길수있게 미리 셋팅해줘 

git config --global user.email "web7722@gmail.com"
git config --global user.name "ingoo"

> git add [파일명]

> git status

> git add [Readme.md]
> git commit -m "Readme.md 파일을 생성함"

> git remote add origin https://github.com/ingoo-blockchain/helloworld.git

> git remote rm origin
> git remote add origin https://github.com/아이디/helloworld.git
내 로컬 저장소에있는 애들을 원격저장소에 등록할건데. 등록할 이름은 origin이고
원격저장소의 주소는 `https://github.com/ingoo-blockchain/helloworld.git`

내용입력하고 Enter

> git push origin master

> git remote -v
> git push origin master


> git remote set-url origin https://github.com/ingoo-blockchain/helloworld.git