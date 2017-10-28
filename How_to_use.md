目前只支持windows环境 并且 需要python和jdk(注意不是jre)支持

python和jdk安装和环境搭建不解释

服务端使用方法:
1.打开config
2.编辑config
port <23333>#使用的端口(客户端里第三方服务器端口号)
allow_multiuser <false>#是否允许多用户同时打补丁 (人太多可能会把主机拖垮 慎重考虑)
3.点击start.bat开启服务
4.客户端尝试连接
5.没了