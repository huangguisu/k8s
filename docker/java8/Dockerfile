
# Pull base image.  
FROM centos  
  
# 设置jdk 的环境变量。
ENV JAVA_HOME /usr/java8
  
# 复制/usr/java文件到镜像中(jdk1.8.0_66 目录和Dockerfile在同一目录)
COPY ./jdk1.8.0_66 /usr/java8
  
# Define default command.  
CMD ["bash"] 

