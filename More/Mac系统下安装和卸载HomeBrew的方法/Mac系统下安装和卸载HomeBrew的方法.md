安装方法：
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"   
```


卸载方法
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"  
```

错误提示：
Warning: /usr/local/bin is not in your PATH.

一直未能安装成功,后在
http://stackoverflow.com/questions/14288682/error-installing-homebrew-brew-command-not-found 找到问题所在

终端输入命令 export PATH=/usr/local/bin:$PATH 即可解决此问题

