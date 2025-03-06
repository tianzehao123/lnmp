FROM mysql:8.0

# 复制自定义的 MySQL 配置文件
COPY my.cnf /etc/mysql/conf.d/my.cnf

# 设置环境变量
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=myapp
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=123456

# 暴露端口
EXPOSE 3306