# 生鲜商品管理系统 - 后台管理前端

基于 Vue 2 与 Element UI 的后台管理界面，用于管理用户、商家、商品、库存、订单和系统基础数据。

## 技术栈

- Vue 2
- Vue CLI 4
- Vue Router
- Element UI
- Axios
- ECharts
- Sass / node-sass

## 本地运行

建议使用兼容 `node-sass 4.x` 的 Node.js 16 环境。

```powershell
npm install
npm run serve
```

开发服务默认运行在 `8081` 端口。

## 构建

```powershell
npm run build
```

构建结果输出到 `dist`，该目录不会提交到 Git。

## 后端接口

前端请求前缀为 `/springbootcug86`，开发代理已指向后端默认地址：

```text
http://localhost:8890/springbootcug86/
```

## 上传前检查

- 不要提交 `node_modules` 和 `dist`。
- 不要提交 `.env`、账号密码、Token 或生产环境接口地址。
- 安装依赖和构建成功后，再发布 GitHub 仓库。