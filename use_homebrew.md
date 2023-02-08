# use_homebrew

## 1.下载homebrew

**苹果电脑 常规安装脚本（推荐 完全体 几分钟安装完成）：**

```bash
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

**苹果电脑 极速安装脚本（精简版 几秒钟安装完成）：**

```bash
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)" speed
```

-> [Mac电脑如何打开终端：command+空格 在聚焦搜索中输入terminal回车](https://link.zhihu.com/?target=https%3A//support.apple.com/zh-cn/guide/terminal/apd5265185d-f365-44cb-8b09-71a064a42125/mac)*。*

**苹果电脑 卸载脚本：**

```bash
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh)" 
```

**常见错误**去下方[地址](https://link.zhihu.com/?target=https%3A//gitee.com/cunkai/HomebrewCN/blob/master/error.md)查看

```http
https://gitee.com/cunkai/HomebrewCN/blob/master/error.md
```


**Linux电脑** 安装脚本：

```bash
rm Homebrew.sh ; wget https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh ; bash Homebrew.sh
```

**Linux电脑** 卸载脚本：

```bash
rm HomebrewUninstall.sh ; wget https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh ; bash HomebrewUninstall.sh
```

## 2.homebrew命令

```shell
$ brew –help					  #查看brew的帮助
$ brew search [软件名]   #搜索要下载的软件
$ brew install [软件名]  #下载软件
$ brew uninstall [软件名]#卸载软件
$ brew list							#显示已经安装软件列表									
$ brew upgrade [软件名] 	#更新某具体软件
```

