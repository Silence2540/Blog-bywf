# 无法访问Github Pages(github.io)解决方法
## 修改DNS
### 修改为255.5.5.5或223.6.6
## 修改host(不具备普遍性)
### 在host中增加一行
185.199.108.153 xxx.github.io
(xxx为Github的用户名)
### 若无效，需要查找最新IP
1.在IP查询网站找到github域名对应IP（选最快的）
IP查询网站：
www.ipaddress.com
https://tools.ipip.net/dns.php
查找域名：
xxx.github.io(xxx为Github的用户名)
2.修改host:
IP xxx.github.io
## 还有网上流传的其它方法
### 同样也是改host
185.199.110.153 binance-docs.github.io
52.74.223.119 gist.github.com
192.30.255.116 api.github.com
185.199.109.153 assets-cdn.github.com
185.199.110.133 raw.githubusercontent.com
185.199.108.153 rogerdudler.github.io
185.199.108.153 github.io