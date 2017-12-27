New Media Design II 2017-2018
=============================

Opdracht iRent
--------------

### Installatie kloon

```
PS> c
PS> git clone «repositorynaam» «mapnaam»
PS> c «mapnaam»
PS> git submodule update --init
PS> git submodule foreach 'git checkout v4-dev'
```


```
PS> c «mapnaam»
PS> bundle update
PS> bundle exec jekyll serve
```

### Origineel

Als je aan een eigen project Bootstrap als een **Git Submodule** wil toevoegen.

```
PS> c
PS> mkdir «mapnaam»
PS> c «mapnaam»
PS> git init
PS> git submodule add --branch v4-dev --depth 1 https://github.com/twbs/bootstrap/ _vendor/bootstrap
```

### Mijn GIT webadres

<http://127.0.0.1:40001718-nmd2-code-irent-ThibDhae/>