# 架构规范

## 分层设计

1. 展现层：以Rest形式接受Web请求，将请求路由到应用层，并返回视图模型。
2. 应用层：负责获取输入，组装上下文，做输入校验，调用领域层做业务处理。
3. 领域层：核心业务逻辑，包括了领域服务和领域对象。
4. 基础设施层：包含数据访问通道（Tunnel）\应用配置（Config）\通用的工具类（Common）。

## 规范设计

1. 组件规范：至少三个组件，应用层、领域层、基础设施层。
2. 包规范：
    - 应用层：
      - service：负责响应请求。
      - interceptor：负责切面处理。
      - command：负责command请求。
        - query：负责query请求。
      - validator：负责参数校验。
      - convertor：负责不同对象之间的转换。
      - repostitory：调用基础设施。
    - 领域层：
      - entity1：领域实体。
      - entity2：领域实体。
      - entity3：领域实体。
    - 基础设施层：
      - config：配置信息
      - tunnel：数据通道
        - database：数据库通道
        - rpc：rpc数据通道
        - search：搜索数据通道
      - common：通用类
