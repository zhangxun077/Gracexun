#note
ctrl+t ctrl+b//对齐
w b//前，后单词
<math.h> -lm//数学函数库
snippets//插件
ctrl+x+f//当前目录下到文件名
:h i-Ctrl-<tab>//查看插入模式下到命令 如：ctrl+n
git checkout "commit num" -b "branch name"
git branch
git checkout master或tmp 俩个版本切换
git branch -D tmp 删除branch 在master
find 从硬盘查找 比较慢
locate 很快 有一个匹配到数据库 直接到数据库查找 但数据库不能随时更新
dpkg -S 包名
ctrl+v 可视块
undo u 
redo ctrl + r
看俩个同源文件到差异diff -u a b
vimdiff a b
vnew new 打开一个新窗口 bd 关闭一个新窗口  关闭内存缓存区
:DiffSaved  一个文件未保存前查看diff
zf 创建折叠  zx打开折叠 zc关闭折叠
先生成ctags加文件：
vim main.c hello.c hello.c 然后打，t列出架构 :ls打开了几个buf
vim -t 函数名 直接进入函数
变量跳跃查询gd gD
打开文件 又想打开另一个文件，n
选中 ctrl+c前面加注释
wow
1.
Code:

sudo nano /etc/apt/sources.list

 

2.
Code:

sudo apt-get update && sudo apt-get upgrade

3.
Code:

sudo apt-get install build-essential libssl-dev

4.
Code:

sudo apt-get install linux-headers-`uname -r`

5.
Code:

sudo apt-get install subversion

6.
Code:

sudo -i

7.
Code:

sudo svn checkout http://svn.madwifi-project.org/madwifi/trunk/ madwifi-ng

8.
Code:

cd madwifi-ng

9.
Code:

echo "" >> /etc/modprobe.d/blacklist

10.
Code:

echo "#Remove To Install MadWIFI Drivers" >> /etc/modprobe.d/blacklist

11.
Code:

echo "blacklist ath9k" >> /etc/modprobe.d/blacklist

12.
Code:

echo "blacklist ath5k" >> /etc/modprobe.d/blacklist

13.
Code:

make && make install

14.
Code:

echo ath_pci >> /etc/modules


