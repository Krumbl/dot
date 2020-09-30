## Requirements
- Clone recursively for plugins
```git clone --recursive https://github.com/username/reponame.git```


## Setup
```ln -sf dot/vim/ ~/.vim```
```ln -sf dot/vim/vimrc ~/.vimrc```
```vim```
```:helptags ALL```

## Documentation
- Plugins
  -https://github.com/vim/vim/blob/03c3bd9fd094c1aede2e8fe3ad8fd25b9f033053/runtime/doc/repeat.txt#L515

## Managing Plugins
[Documentation](https://github.com/vim/vim/blob/03c3bd9fd094c1aede2e8fe3ad8fd25b9f033053/runtime/doc/repeat.txt#L515)
- https://gist.github.com/manasthakur/d4dc9a610884c60d944a4dd97f0b3560#installing-plugins

### Add Plugin
```git submodule add https://github.com/pluginname pack/mypackages/start/pluginname```
### Update Plugin
```git submodule update --remote --merge```

### Remove Plugin
```git submodule deinit vim/pack/mypackages/start/nameofplugin```
```git rm vim/pack/mypackages/start/nameofplugin```
```rm -Rf .git/modules/vim/pack/mypackages/start/nameofplugin```

