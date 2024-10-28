# 测试流程 
### [官方文档](https://www.docusaurus.cn/docs)

- 安装Node.js - [Download](https://nodejs.org/zh-cn/download/prebuilt-installer)
  - 下载并安装, 然后
    - 安装结束后弹出一个命令框, 全程同意
    - 最后输入ENTER+回车, 重启电脑
  - 指令`node -v` - 检查node环境
  - 指令`npm -v` - 检查npm环境
  - 指令`npm install -g npm` - 重新安装npm (初始化)
- 创建Docusaurus
  - 指令`npm config set registry https://registry.npmmirror.com` - 设置镜像源
  - 指令`npx create-docusaurus@latest TestProject classic` - 创建工程
    - `TestProject` 为项目名
- 运行Docusaurus
  - 指令`cd TestProject`
  - 指令`npx docusaurus start`
- 打开Docusaurus
  - 地址`http://localhost:3000`


# 其他
- `npm config set registry https://registry.npmjs.org` - 还原初始镜像源
