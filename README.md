
## 项目介绍

[vue-admin-webapp]是一个后台管理 spa 页面，它基于 [vue]和 [element-ui] 采用了最新的前端技术栈，实现了登录权限验证，动态路由生成，并使用 [easy-mock] 来模拟请求数据，实现了典型的业务模型案例，它可以帮你快速搭建后台管理系统模板，并根据实际的业务需求添加路由来实现企业级管理页面，相信本项目一定能帮助到你。

**目前版本基于  `webpack 4.0+` 和 `vue-cli 3.x ` 版本构建，需要 [Node.js](https://nodejs.org/) 8.9或更高版本（推荐8.11.0+），相关知识可以自行进官网进行了解**

## 快速开始 

需要安装 node 和 webpack 及 git。 本项目涉及的技术栈主要有 [ES6] [vue] 、[vuex]、[vue-router] 、[vue-cli] [axios]、[webpack]、[element-ui] 、[easyMock] 

### 安装

```
# 进入项目目录
cd vue-admin-webapp

# 安装依赖
npm install

# 启动服务
npm run serve
```

### 部署

`deploy`分支执行 deploy.sh 文件脚本执行 npm run build 并上传至 gh-pages 分支更新 github pages 页面

### 功能

```
- 登录 / 注销
  - 登录仿GeeTest-极验安全策略
  
- 页面
  - 初次进入引导用户
  - sideBar收缩和展开
  - 全屏控制
  
- 侧边栏
  - 根据不同用户权限展示相应的动态左侧菜单
  
- 权限验证
  - 管理员页面
  - 权限设置
  
- 表格操作
  - 涉及平常业务遇到的相关表格操作（参考）
- Excel
 - Excel导出
 - Excel导入
 - 多级表头导出
 
- Echarts
 - 滑动显示更多数据
 - 动态切换charts
 - map地图使用
 
- Icons
 - element-icon
 - 阿里iconfont
