**手写模拟dubbo**
Provider模块：提供api、实现api、暴露（启动tomcat、nettyServer）、服务本地注册、服务注册中心注册

Consumer模块：拿接口名从注册中心获取服务地址、调用服务

Registry模块：保存服务配置信息、（服务名：List<URL>）

RpcProtocol模块：基于Tomcat的HttpProtocol、基于Netty的DubboProtocol

Framework模块：框架实现

原理图
https://www.processon.com/diagraming/5f1900ba5653bb7fd24b7d5f