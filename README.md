### 基于Spring MVC开发测试用rest服务。用于测试API gateway
比如访问服务: http://10.19.15.28:19111/spring-rest/user/getUser/{userId}
如：http://10.19.15.28:19111/spring-rest/user/getUser/123
得到的响应
{"userName":"zhangsan123","sex":"male"}

### 测试程序暂时部署
主机 10.19.15.28  端口 22022
tomcat用户密码  aseusr01/Linuxusr_0908

启动与停止脚本
aseusr01@h-xc2to88z:/aifs01/users/aseusr01/bin> ls
Start-s1.sh  Stop-s1.sh