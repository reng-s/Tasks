#基本概念  
**仓库Repository**  
仓管用来存放项目代码，每个项目对应一个仓库，多个开源项目则有多个仓库  
**收藏Star**  
仓库主页star按钮，意思为收藏项目的人群，方便下次查看  
**复制克隆项目Fork**  
fork项目时独立存在  
![fork示意图](C:\Users\ASUS\Desktop\64311f6d-fa32-4de8-8a90-833b944acfff.png)  
![fork](C:\Users\ASUS\Desktop\8a13f402-fc79-4722-b7da-ac015ab6b5e1.png)  

**关注（Watch）**  
关注项目，当项目更新可以接收到通知  
**事务卡片（Issue）**  
发现代码bug，但是目前没有成型代码，需要讨论时用，或者使用开源项目出现问题时使用  
**开源项目流程**  
1.新建Issue  
提交使用问题或者建议或者想法  
2.Pull Request  
步骤：  
1、fork 项目  
2、修改自己仓库的项目代码  
3、新建pull request  
4、等待作者操作审核  
**Git的使用**  
目的：通过git管理GitHub托管项目代码  
**git工作区域**  
git repository（git 仓库）  
最终确认的文件保存到仓库，成为一个新的版本，并且对他人可见  
暂存区  
暂存已经修改的文件最后统一提交到git仓库中  
工作区（Work Directory）  
添加、编辑、修改文件等动作  
**git基础设置**  
设置用户名  
git config --global user.name "Your Name"
  
设置用户邮箱名  
git config --global user.email "email@example.com"  
查看设置  
git conflg--list
**远程上传git文件至github**  
1、fork远端仓库  
2、git add+文件名  
3、git commit -m'文件描述'  
4、git push  
同时可以通过git status来查看进程（文件状态） 
**git和GitHub的区别**  
git相当于一个版本管理工具，用于管理你本地文件的版本，传统的版本控制都是新建一个文件夹，而git可以不联网（优点）将你的每次迭代版本放在一个类似于服务端的地方，如果你需要哪个版本则直接用git的指令获取，从而达到版本控制。  
github类似于一个百度云，或者阿里云之类的云服务器，用户可以将其文件存放在其中，但是其又可以像一个交流网站，将你分享的内容共享（开源），例如百度等公司在上面也有开源的代码，可用于程序员交流。简言之：其就是一个“托管所”，将你的代码放在上面就不用管，而且其可以实现版本控制，也就是说你可以提交一个文件夹多次，保留你提交的所有记录  
1.git无需联网，github需要联网  
2.git是一个本地管理工具，而github是一个网站，可以用来存放源码，且开源
  
