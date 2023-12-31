# tzmall-api
商城的后台服务端，前端项目：https://github.com/sjktCode/tzmall-uniapp

## 本地开发启动
依赖服务：
```
// MySql服务
docker compose  --env-file .env.development run -d --service-ports mysql --lower-case-table-names=1
// Redis服务
docker compose  --env-file .env.development run -d --service-ports redis
```

项目启动，首次启动前安装依赖包：
```
pnpm install
```

启动
```
pnpm dev
```
