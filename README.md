# More than Chat 前端

## 本地开发这个服务

``` shell
npm install
npm run dev
```

## 部署启动这个服务

``` shell
pm2 delete jumper
```

``` shell
npm run build
```

待build完成后，ctrl c取消运行，然后执行：

``` shell
npm run start
```