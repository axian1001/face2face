# face2face
基于netty的实时聊天(IM)服务器。服务器分模块拆分，并且设计为可水平扩展的集群。
auth服务：负责登录认证。
gate服务：作为服务器与客户端通信的桥梁。
logic服务器：处理各种业务逻辑。
