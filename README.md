# fnos

## fnos远程访问的方式

### 1.FN Connect

注册fnos账号:zhanminjie，fnos系统远程访问这一栏开启FN Connect，使用fnos手机APP远程登陆，但流量限制会存在限流。


### 2.域名+IPV6

获取fnos系统IPV6公网地址，阿里云购买域名 martinzhan.top，域名解析控制台将域名绑定fnos系统IPV6公网地址进行解析。使用fnos手机APP/浏览器远程登陆,此方式远程登陆存在链接不安全告警。


### 3.域名+IPV6+lucky方向代理

lucky软件添加WEB访问规则，路由器添加端口映射规则，使用二级域名远程登陆，此方式远程登陆不存在链接不安全告警,无法使用fnos手机APP登陆。

#### 1.fnos远程登陆

外网访问地址[[https://fn.martinzhan.top:4680](https://fn.martinzhan.top:4680)]()
