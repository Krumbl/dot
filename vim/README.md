http://vimdoc.sourceforge.net/htmldoc/help.html
## Setup
```git clone --recursive https://github.com/username/reponame.git```
```ln -sf reponame ~/.vim```
```ln -sf reponame/vimrc ~/.vimrc```
```vim```
```:helptags ALL```

## Managing Plugins
- https://gist.github.com/manasthakur/d4dc9a610884c60d944a4dd97f0b3560#installing-plugins

### Add Plugin
```git submodule add https://github.com/pluginname pack/mypackages/start/pluginname```
### Update Plugin
```git submodule update --remote --merge```

### Remove Plugin
```git submodule deinit vim/pack/mypackages/start/nameofplugin```
```git rm vim/pack/mypackages/start/nameofplugin```
```rm -Rf .git/modules/vim/pack/mypackages/start/nameofplugin```

