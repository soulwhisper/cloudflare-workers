# cloudflare-workers
- sub-converter, deprecated
- url-proxy, deprecated
- docker-proxy, deprecated

## sub-converter
- 反代订阅转换工具，通过随机化服务器地址和节点账号密码，解决用户转换订阅的隐私问题
- 环境变量名：`BACKEND`
- KV或R2变量名：`SUB_BUCKET`
- ref: [bulianglin/psub](https://github.com/bulianglin/psub)
- support SS / SSR / vmess / trojan / vless / hysteria

## url-proxy
- javascript reverse proxy
- ref: [aD4wn/Workers-Proxy](https://github.com/aD4wn/Workers-Proxy)

## docker-proxy
- add A record of xxx.example.com to 192.0.2.1
- add xxx.example.com/* to HTTP routes of workers
- ref: [ciiiii/cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy)
