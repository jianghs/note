# 错误码规范

## 编号错误码

1. 好处：编码风格固定，给人一种正式感。
2. 缺点：必须要配合文档才能理解错误码代表的意思。
3. 例如Oracle的错误码，ORA-XXX
4. 需要预留足够的位数。

## 显性化错误码

1. 类型 + 场景 + 自定义标识
2. 例如：P-参数异常，B-业务异常，S-系统异常，P_Customer_NameIsNull-客户姓名不能为空，B_Customer_NameAlreadyExist-客户姓名已经存在，S_Unknown_Error
