# Sapienza_thesis
test Guacamole+Docker

Steps until now: 
 1. 在CentOS9中安装Guacamole sever
 2. 在CentOS9中安装tomcat8,并开放8080端口
 3. 在CentOS9中安装Guacamole client，并将目录中bin/target/guacamole.war移动到tomcat/webapps/


Devices and softwares：
 - Hardware: Macbook Pro 2020(Intel)
 - VM software: Parallels Desktop
 - VM OS: CentOS 9, CentOS 7.4

Problem tips
1.在Parallels Desktop安装CentOS7前需要手动关闭3D加速，否则CPU会占满；
2.PD自动下载的OS版本是CentOS9，在Guacamole sever环境配置时会出现很多问题；
