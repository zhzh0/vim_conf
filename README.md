# 目标

> Just a Better Vim Config. Keep it Simple.

# 安装步骤

### 1. clone 到本地

### 2. 安装依赖包

### 3. 安装


# 移除安装

```
cd ~ && rm -rf .vim .vimrc .vimrc.bundles && cd -
```

# 常见问题

# 插件

### 选择安装插件集合

编辑vimrc.bundles中

```
" more options: ['json', 'nginx', 'golang', 'ruby', 'less', 'json', ]
let g:bundle_groups=['python', 'javascript', 'markdown', 'html', 'css', 'tmux', 'beta']
```

选定集合后, 使用插件管理工具进行安装/更新

### 插件管理

使用 [vim-plug](https://github.com/junegunn/vim-plug) 管理插件

管理插件的命令

```
:PlugInstall     install                      安装插件
:PlugUpdate      install or update            更新插件
:PlugClean       remove plugin not in list    删除本地无用插件
:PlugUpgrade     Upgrade vim-plug itself      升级本身
:PlugStatus      Check the status of plugins  查看插件状态
```

### 插件列表


### Inspire

1. vimrc文件布局`vimrc+vimrc.bundles`配置方式参考 [maximum-awesome](https://github.com/square/maximum-awesome)

2. install.sh 参考`spf13-vim` 的`bootstrap.sh` [spf13-vim](https://github.com/spf13/spf13-vim)

2. 插件管理使用[Vim-plug](https://github.com/junegunn/vim-plug)

### Donation

