# 将官方 OpenJDK:8-jdk 运行时用作父镜像
FROM openjdk:11-jdk
# 维护该镜像的用户信息
LABEL maintainer="ruanyu <ruanyu@x3platform.com>"

# 定义环境变量
ENV TZ="Asia/Shanghai"

# 设置常用工具和设置时区为 Asia/Shanghai
RUN sed -i 's/\(deb\|security\).debian.org/mirrors.aliyun.com/g' /etc/apt/sources.list && apt update  