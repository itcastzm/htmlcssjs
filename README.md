# htmlcssjs
html   csss  js



https://www.jianshu.com/p/a1908f55bef8

1、执行git config --list，查看git的配置信息

执行vim .git-credentials，查看credential中缓存的账户

四、 重复输入用户名密码
清除缓存之后我们每次提交代码的时候都需要输入用户名和密码
git config --global credential.helper store

git help -a | grep credential命令查看自己系统支持的crendential, cache 代表内存中的缓存，store 代表磁盘。
git config credential.helper命令可以看到 cache、store、osxkeychain(钥匙串)中是否还有git的配置信息。由图中我们可以得出git config还存储在store中



