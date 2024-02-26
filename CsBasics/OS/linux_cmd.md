# linux基础

## 特殊符号

### {}



## vim

### 编辑模式下



### 命令模式下

**编辑键：**

i 当前位置编辑

o 下一行编辑 O 上一行开始编辑

a 行尾编辑



**上下左右移动建：**

h向左，l向右，j向下，k向上



**移动单词：**

w移动到下一个单词，b移动到上一个单词



**行移动：**

0移动到行首，$移动到行尾

行号 + G ： 跳转到该行



**文章移动：**

gg移动到文首，GG移动到文尾



**查找**

向下查找：/要查找的内容 ， n找到下一个

向上查找：？要查找的内容，n下一个



**复制粘贴删除**

yy复制光标所在行，4yy就是复制四行

p 粘贴

dd删除当前行

D删除当前光标后所有的内容到行为，C除了D的作用还立即进入编辑模式

x 向后删除

X 向前删除

u 撤销之前的操作



**快速退出**

ZZ



**可视块**

crtl + v 进入可视块

上下移动选中可视块，

d删除

I 进入编辑模式

esc两次完成





### 底线命令模式下

`:set number`添加行号

## 查看ip地址

`ip addr` / `ip a` / `ip address` / `hostname -I`



## grep

查找文件内容

-i 不区分大小写



# pip3

### freeze

查看所有已安装的软件包
