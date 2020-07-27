# TP5.1Single-Sign-On
TP jasny/sso扩展，单点登录

#原理
session存储登录数据，当另外一个应用登录的时候获取这个session，然后直接登录

#安装
conposer安装tp5.1框架
conposer安装 "composer require jasny/sso=0.2.3"

#相关文件夹和文件
application/h5
application/pc
application/sso
application/common.php

#缓存配置
config/cache.php

#路由配置
配置sso模块到127.0.0.60
配置pc模块到127.0.0.61
配置h5模块到127.0.0.62
route/route.php

#测试，如果有端口号需要加端口号
127.0.0.61:9999
访问pc或者h5随便一个登录 登录成功后另一个也默认登录
账号jackie 密码jackie123
账号john 密码john123
