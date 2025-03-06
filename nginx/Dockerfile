FROM nginx:latest

# 复制自定义的 nginx 配置文件
COPY nginx.conf /etc/nginx/nginx.conf
COPY sites-available/default.conf /etc/nginx/conf.d/default.conf

# 暴露端口
EXPOSE 80