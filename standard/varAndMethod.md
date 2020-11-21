#变量及方法命名规范

## 方法名约定

1. 新增-create
2. 添加-add
3. 删除-remove
4. 修改-update
5. 查询（单个结果）-get
6. 查询（多个结果）-list
7. 分页查询-page
8. 统计-count

## 后置限定词

1. xxxTotal-xxx总和
2. xxxAverage-xxx平均值
3. xxxMax-xxx最大值
4. xxxMin-xxx最小值
5. xxxCount-xxx总数
6. xxxId-xxx序号

## 类名约定

1. xxxCmd.java - 表示一个用户请求
2. xxxCO.java - 客户对象，等同于DTO
3. xxxServiceI.java - API接口类
4. xxxCmdExe.java - 命令模式，每个用户请求对应一个执行器。
5. xxxInterceptor.java - 拦截器
6. xxxExtPt.java - 扩展点
7. xxxExtjava - 扩展点实现
8. xxxValidator.java - 校验器
9. xxxConventor.java - 转换器
10. xxxAssember.java - 组装器，组装外部服务调用参数
11. xxxE.java - Entity，领域实体
12. xxxV.java - value object, 值对象
13. xxxRepository.java - 仓储接口
14. xxxDomainService.java - 领域服务
15. xxxDO.java - 数据对象，用于持久化
16. xxxTunnel.java - 数据通道，DAO是最常见的通道，也可以有其他通道。
17. xxxConstant.java - 常量类
18. xxxConfig.java - 配置类
19. xxxUtil.java - 工具类
