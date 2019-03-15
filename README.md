# by 陈冕
***
#### 项目源码详情描述： 
#### 《基于Springboot+Mybatis+springsecrity完整网站后台管理系统项目源码》
#### spring security 全注解式的权限管理
#### 动态配置权限，角色和资源，权限控制到按钮粒度
#### 采用token进行权限校验，禁用session，未登录返回401，权限不足返回403
#### 采用redis存储token及权限信息
#### 内置功能：
#### 用户管理：用户查询、添加用户、修改用户、给用户分配角色
#### 菜单管理：菜单列表、添加菜单、修改菜单、删除菜单、权限配置、菜单图标设置、菜单排序
#### 角色管理：角色查询、添加角色、修改角色、删除角色
#### 代码生成：根据表名生成bean、controller、dao、Mapper.xml、列表页、搜索、分页、新增页、修改页
#### job集群：创建job、取消job、查询job、下拉搜索spring bean
#### 数据源监控：druid
#### 接口swagger文档
#### 邮件管理：发送邮件、搜索邮件
#### 文件管理：上传文件、文件列表、文件删除
#### 公告管理：公告未读提醒、发布公告、查询公告、公告阅读人列表
#### excel下载：自定义sql导出excel、也可在页面展示sql结果数据
#### 字典管理：一些常量字典的维护
#### 个人信息修改
#### 修改密码
#### 头像修改
#### 其他说明：
#### 日志模块
#### sl4j日志分包：将sql日志、业务日志、异常日志进行了分离，更方便定位问题
#### 日志表：使用aop拦截实现
#### 权限控制：基于token方式，禁用session
#### 对各种不同异常进行了全局统一处理
#### 使用lombok简化java代码，让源码更简洁，可读性高
#### mybatis未进行二次封装，原滋原味，简单sql采用注解，复杂sql采用Mapper.xml配置
#### 使用了layui的弹出层、菜单、文件上传、富文本编辑、日历、选项卡、数据表格等
#### 表单数据采用bootstrapValidator校验，简单快捷方便 jdk8+mysql+redis+IntelliJ IDEA+maven   Springboot+Mybatis+ SpringMvc+springsecrity+Redis+bootstrap+jquery


#### http://localhost:8889/login.html
#### 用户名：admin  密码：admin
