# 基础镜像：官方nginx，用来托管静态网页
FROM nginx:alpine

# 把当前项目所有文件复制到nginx网页根目录
COPY . /usr/share/nginx/html

# 容器对外暴露80端口（nginx默认端口）
EXPOSE 80

# nginx启动命令（基础镜像自带，写出来更清晰，可不写）
CMD ["nginx", "-g", "daemon off;"]