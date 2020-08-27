- mysql 创建用户和授权
  CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';  
  GRANT ALL PRIVILEGES ON * . * TO 'newuser'@'localhost';  
  FLUSH PRIVILEGES;  
  查看用户权限  
  SHOW GRANTS username;  
  删除 user:  
  DROP USER ‘username’@‘localhost’;  

- 修改ubuntu 20.04 apt source
deb http://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse  
deb-src http://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse  

deb http://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse  
deb-src http://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse  

deb http://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse  
deb-src http://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse  

deb http://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse  
deb-src http://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse  

deb http://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse  
deb-src http://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse  
