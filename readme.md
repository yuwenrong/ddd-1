# 1 interfaces 
* 目录下有assemble dto facade
- assemble 是DTO与DO领域对象之间的转换
- dto是前端应用数据传输的载体
- facade 服务接口调用

# 2 application
* event和service
- event做事件发布，领域层订阅事件处理
- service 将多个领域服务或者应用服务进行封装和编排和组合处理，DO转DTO也是这里处理

# 3 domain
* 聚合
- entity 实体
- event 事件
- service 领域服务
- repository 仓储


https://www.cnblogs.com/daoqidelv/p/7492447.html