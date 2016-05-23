#zyzx-feedback

## 测试方法
执行如下命令
```
npm install http-server -g
http server
```

打开浏览器查看

## 注意
upload 接口 后端返回的数据的content-type 必须为“text/plain”，否则ie8&ie9跨域将无法获取返回结果。