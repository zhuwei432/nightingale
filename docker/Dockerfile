# 使用基础镜像，例如基于Node.js的官方镜像
FROM node:14

# 设置工作目录
WORKDIR /opt

# 复制所有文件到工作目录中
COPY . /opt

# 安装所有依赖
RUN npm install

# 暴露端口
EXPOSE 3000

# 定义启动命令
CMD ["node", "index.js"]