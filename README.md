# Sapienza_thesis
test Guacamole+Docker

Steps until now: 
 1. 在CentOS9中安装Guacamole sever；
 2. 在CentOS9中安装tomcat8,并开放8080端口；
 3. 在CentOS9中安装Guacamole client，并将目录中bin/target/guacamole.war移动到tomcat/webapps/；
 4. 在CentOS7中共享文件配置：https://blog.csdn.net/buyueliuying/article/details/78447810?locationNum=2&fps=1


Devices and softwares：
 - Hardware: Macbook Pro 2020(Intel)
 - VM software: Parallels Desktop
 - VM OS: CentOS 9, CentOS 7.4

Problem tips
 1.在Parallels Desktop安装CentOS7前需要手动关闭3D加速，否则CPU会占满；
 2.PD自动下载的OS版本是CentOS9，在Guacamole sever环境配置时会出现很多问题；
 3.首次使用的CentOS7默认网卡关闭，需要手动打开：https://blog.csdn.net/dw1360585641/article/details/124837383；
 4.CentOS7中共享步骤之前需要手动安装Parallels tools；
 5.
 

Referenced links:
 - https://blog.csdn.net/zengxiong9/article/details/127093126
 - https://guacamole.apache.org/releases/1.3.0/
 - https://blog.csdn.net/weixin_44699860/article/details/129217482
