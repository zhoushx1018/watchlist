
# Watchlist

《[Flask入门](https://helloflask.com/tutorial/)》 

Demo: http://watchlist.helloflask.com

![Screenshot](http://helloflask.com/screenshots/watchlist.png)


## 安装

git clone源码
```
$ git clone https://github.com/greyli/Watchlist.git
$ cd Watchlist
```

安装依赖
```

$ pip3 install -r requirements.txt
```


预先在DB生成数据
```
$ flask forge

```

启动http服务

```
## Running on http://0.0.0.0:8080/
$ flask run -h 0.0.0.0  -p 8080 
```

在本地尝试访问服务

```
$ curl http://localhost:8080/hello
```

通过浏览器访问服务

```
http://IP:8080/hello/
```
