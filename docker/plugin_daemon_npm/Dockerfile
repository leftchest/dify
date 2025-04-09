# 使用指定的基础镜像
FROM docker.m.daocloud.io/langgenius/dify-plugin-daemon:0.0.7-local

# 安装 Node.js 环境（这里选择 Node.js 22 版本）
RUN curl -fsSL https://deb.nodesource.com/setup_22.x | bash -
RUN apt-get install nodejs -y

# 安装 npm 包管理器
RUN curl -qL https://www.npmjs.com/install.sh | sh