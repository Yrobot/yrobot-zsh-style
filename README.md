yrobot个性化oh-my-zsh的主题文件  
基于`schminitz`修改  
### 效果：
![](https://tva1.sinaimg.cn/large/006tNbRwly1gan03cxtaxj30dj04maae.jpg)

### 安装方式：
1. 将theme文件clone到`$ZSH_CUSTOM/themes/`下
```
```
2. 修改`.zshrc`文件
```
ZSH_THEME="yrobot-zsh-style"
#展示在输入行最前面，用来标记
#比如在服务器上赋值为cloud，用来区分服务器和本地shell
export ZSHTAG="my-mac" 
```
3. 在命令行生效配置文件
```
source ~/.zshrc
```