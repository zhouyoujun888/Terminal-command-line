# 终端命令行基本操作-Terminal-command-line
### 文件-文件夹-切换-/根目录-～家目录的操作
 pwd 查看当前完整路径。
 ls 查看当前目录下文件（不包括隐藏文件）      
 ls -a 查看当前目录下文件（包括隐藏文件）   
 ls -al 查看当前目录下文件（包括隐藏文件）的详细信息   
 cd ./学习目录 切换到当前目录下的学习目录文件  
 cd .. 切换上一级目录  
 cd ~ 切换到家路径  
 cd / 切换到根路径     
 touch readme.md 创建文件  
 rm readme.md 删除文件（注意：只能删除当前目录下的文件，如果需要删除别的目录下的文件就要cd切换到别的目录下去rm删除或者rm ./文件路径/readme.md）   
 mkdir 文件夹名字 创建文件夹 
 rm -r 文件夹名  删除文件夹（注意：rm -r只能删除空文件夹）  
 rm -rf 文件夹名 强制删除文件夹（注意：这是强制删除，不管要删除的文件夹里面是不是有文件都会在没有提示的情况下强制删除） 
 mv readme.md README.md  重命名文件（注意：readme.md是要被修改的文件）  
 ### 命令行编辑器 vim    （vim就是vi的升级版）
 vim readme.md 初始进入编辑器命令模式   
 i  进入编辑模式  
 esc 进入命令行模式  
 :wq 保存退出  
 :q! 不保存，强制退出  
 cat readme.md （用cat命令查看vim里面的编辑信息）   
 ### 安装服务器
 npm install -g http-server    用npm安装http-server包
 http-server （安装好后，在要打开的文件目录下输入http-server命令，就可以开启一个静态服务器） 
 ### 登录开发机
 ssh jirengu16@47.91.156.35 登录开发机
 ### 如何让代码在线上浏览
 1.用jsBin
 2.用github
 
 
 
 
