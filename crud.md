# MAVEN-SSM-CRUD
Maven管理的SSM-CRUD练手

SSM-CRUD ssm:SpringMVC+Spring+MyBatis CRUD：Create（创建） Retrieve（查询） Update（更新） Delete（删除）
功能点
• 1、分页 • 2、数据校验 • jquery前端校验+JSR303后端校验 • 3、ajax • 4、Rest风格的URI；使用HTTP协议请求方式的动词，来表示对资 源的操作（GET（查询），POST（新增），PUT（修改），DELETE （删除））

技术点
• 基础框架-ssm（SpringMVC+Spring+MyBatis） • 数据库-MySQL • 前端框架-bootstrap快速搭建简洁美观的界面 • 项目的依赖管理-Maven • 分页-pagehelper • 逆向工程-MyBatis Generator
基础环境搭建
• 1、创建一个maven工程 • 2、引入项目依赖的jar包 • spring • springmvc • mybatis • 数据库连接池，驱动包 • 其他（jstl，servlet-api，junit） • 3、引入bootstrap前端框架 • 4、编写ssm整合的关键配置文件 • web.xml，spring,springmvc,mybatis，使用mybatis的逆向工程生成对应的bean以 及mapper • 5、测试mapper
