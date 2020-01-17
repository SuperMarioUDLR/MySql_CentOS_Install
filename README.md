## MySql_CentOS_Install

#### MySql_CentOS_Install是一个在CentOS系统上快速安装Mysql 8.x的脚本


### 使用环境 CentOS 7.5 
####（如果其他版本有异常请提交issue）



### 使用方式 
#### (如果没有wget 请先安装wget: $yum -y install wget)
```
wget http://tworookie.com/download/mysql.sh
chmod +x ./mysql.sh
./mysql.sh
```


### 注意事项
#### 1.mysql的安装路径为/usr/local/mysql, 初始密码为123456，建议修改密码
#### 2.如果此前有通过yum或者rpm安装，请完全卸载之后再执行脚本，否则可能会出现异常
