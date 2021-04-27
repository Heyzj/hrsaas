# vue-admin-template

English | [简体中文](./README-zh.md)



## Build Setup

```bash
# clone the project
git clone https://github.com/Heyzj/hrsaas.git

# enter the project directory
cd hrsaas

# install dependency
npm install

# develop
npm run dev
```

This will automatically open http://localhost:8080

## Build || 打包

```bash
# build for test environment
npm run build:stage

# build for production environment（用于生成环境）
npm run build:prod
```

## Advanced || 检查项目体积

```bash
# preview the release environment effect
npm run preview

# preview the release environment effect + static resource analysis(已经抽离element-ui和xlsx大体积文件)
npm run preview -- --report
```
## production disposition || 线下打包部署
#### 可以通过Koa.js、express.js或者egg.js 进行模拟线下部署
```bash
#参考地址:
```
Koa：https://koa.bootcss.com/
express: https://www.expressjs.com.cn/
egg: https://eggjs.org/zh-cn/
