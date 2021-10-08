## Downloads

- [ ] [Chrome](https://www.google.co.kr/chrome/?brand=CHBD&brand=FKPE&gclid=CjwKCAjw2P-KBhByEiwADBYWCnVbUEAxfEv65vQVIKmrnSjKbUEePmqR_0V3l4mdsuQ8uVbybwwrURoCVlEQAvD_BwE&gclsrc=aw.ds)
- [ ] [Docker](https://www.docker.com/get-started)
- [ ] [Sublime Text](https://www.sublimetext.com/3)
- [ ] [Iterm](https://iterm2.com/downloads.html)
- [ ] [IntelliJ](https://www.jetbrains.com/ko-kr/idea/download/#section=mac)
- [ ] [Slack](https://slack.com/intl/ko-kr/downloads/mac?geocode=ko-kr)


## Install Brew 
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install Tool With Brew
- [ ] brew install wget
- [ ] brew install httpie
- [ ] brew install git
- [ ] brew install gradle
- [ ] brew install maven
- [ ] brew install vagrant

## Config Git
```
alias.s=status
alias.a=!git add . && git status
alias.au=!git add -u . && git status
alias.aa=!git add . && git add -u . && git status
alias.c=commit
alias.cm=commit -m
alias.ca=commit --amend
alias.ac=!git add . && git commit
alias.acm=!git add . && git commit -m
alias.l=log --graph --all --pretty=format:‘%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset’
alias.ll=log --stat --abbrev-commit
alias.lg=log --color --graph --pretty=format:‘%C(bold white)%h%Creset -%C(bold green)%d%Creset %s %C(bold green)(%cr)%Creset %C(bold blue)<%an>%Creset’ --abbrev-commit --date=relative
alias.llg=log --color --graph --pretty=format:‘%C(bold white)%H %d%Creset%n%s%n%+b%C(bold blue)%an <%ae>%Creset %C(bold green)%cr (%ci)’ --abbrev-commit
alias.d=diff
alias.master=checkout master
alias.spull=svn rebase
alias.spush=svn dcommit
alias.alias=!git config --list | grep ‘alias\.’ | sed ‘s/alias\.\([^=]*\)=\(.*\)/\1\     => \2/’ | sort
```

pull --rebase=true


## Install zsh
https://ohmyz.sh/#install
``` shell
 sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
 ```


## chrome extentions

https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?utm_source=chrome-ntp-icon


## Config Spotlight index 


## Change hostname



## install java 




