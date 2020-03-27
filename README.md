# koa-admin-template
 koa-template
 #### 使用: npm install; npm run start;

- npm init 
- npm install koa
- npm install nodemon
- npm i glob 
- npm i jsonwebtoken  
- npm i koa-bodyparser
- npm i koa-bunyan-logger
- npm i koa-qs
- npm i koa-helmet
- npm i koa-jwt
- npm i koa-log4
- npm i koa-router
- npm i koa-static
- npm i koa2-cors
- npm i moment
- npm i mongoose
- npm i mongoose-auto-increment
- npm i uuid
- npm i lodash

### 额外
'node-cron,require-directory,validate,chai,mocha,should,redis...'
"koa-convert",
"koa-json",
"koa-logger",
"koa-onerror"

### 单元测试
> 编写单元测试。
#### 安装：npm install --save-dev mocha chai supertest
#### 使用：npm run test

- mocha 模块是测试框架
- chai 模块是用来进行测试结果断言库，比如一个判断 1 + 1 是否等于 2
- supertest 模块是http请求测试库，用来请求API接口


### 后期添加redis(待实现)
1. redis做上报缓存，如一个界面一天内被同一个人多次点击时，只计算一次热度。
2. redis实现消息队列及进行定时任务处理，后期添加爬虫等程序，爬取热源。