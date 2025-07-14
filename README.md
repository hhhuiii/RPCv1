# RPCv1
RPC realize with muduo\protobuf\zookeeper
1. 解决TCP粘包/拆包问题，通过自定义消息格式，编解码器实现数据完整传输
2. 使用Protobuf实现数据的高效序列化和反序列化
3. 使用Zookeeper作为服务注册中心和配置中心，实现服务注册与发现功能
4. 集成Glog日志库，实现高性能、线程安全的日志功能，提供多种日志等级
5. 基于Muduo Reactor网络模型实现网络层，完成网络IO与RPC方法调用的解耦设计
