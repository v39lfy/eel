# Ele 
## 一个VPN服务器, 从OpenVPN、v2ray、clash得到的灵感

## 功能
 - IP包拦截、转发、代理。
 - 基于GEO:IP的的分流规则
 - 自定义IP段的分流规则
 - Nat网络
 - 内置DNS服务器
 - DNS解析分流规则的
 - Outbound插件化。比如v2ray的https、tcp、kcp、quic
 - Inbound插件化。系统默认实现tun或者tap。后期可扩展其它协议, socks, http等