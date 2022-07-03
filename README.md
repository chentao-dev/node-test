## 启动应用
```
node server.js 8888
```

## 后台启动应用
```
touch log                             //先创建log文件
node server.js 8888 > log 2>&1 &      //后台启动, 得到进程pid
kill -9 pid                           //关闭进程
```

## 添加路由
1.编辑server.js文件,  添加if else

2.重新启动







