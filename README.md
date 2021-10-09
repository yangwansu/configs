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

### Alias
Global Config File 
```shell
git config --list --show-origin --show-scope
```

``` properties
[alias]
    s=status
    a=!git add . && git status
    au=!git add -u . && git status
    aa=!git add . && git add -u . && git status
    c=commit
    cm=commit -m
    ca=commit --amend
    ac=!git add . && git commit
    acm=!git add . && git commit -m
    l=log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset'
    ll=log --stat --abbrev-commit
    lg=log --color --graph --pretty=format:'%C(bold white)%h%Creset -%C(bold green)%d%Creset %s %C(bold green)(%cr)%Creset %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative
    llg=log --color --graph --pretty=format:'%C(bold white)%H %d%Creset%n%s%n%+b%C(bold blue)%an <%ae>%Creset %C(bold green)%cr (%ci)' --abbrev-commit
    d=diff
    master=checkout master
    main=checkout main
    develop=checkout main
   
```

```  shell
git config --global pull.rebase true
```

[Git Credential Manager Core](https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git#git-credential-manager-core)




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


## Install Intellij Plugins 

Key Promoter X

## configure idea vm options
idea.vmoptions
```
-Xmx2048m
-Xms2048m
```

## Create Command line launcher



