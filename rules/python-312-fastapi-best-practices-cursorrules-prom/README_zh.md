# Python 3.12 FastAPI 最佳实践 .cursorrules 提示文件

作者: Raphael Mansuy

## 您可以构建什么
任务管理API：使用FastAPI开发用于创建和管理任务的API服务。使用pydantic进行数据验证和序列化，fastapi-users进行用户管理，以及fastapi-jwt-auth进行安全用户身份验证。该服务应处理CRUD操作，实现fastapi-cache缓存，fastapi-limiter速率限制，并使用fastapi-pagination高效列出任务。

电子商务平台后端：使用FastAPI构建电子商务平台后端，利用sqlalchemy进行ORM，pydantic进行数据验证，以及FastAPI-users管理用户账户和身份验证。实现fastapi-mail发送订单确认邮件，使用fastapi-cache缓存产品数据，并使用fastapi-pagination处理批量数据检索。

博客平台：使用FastAPI创建博客平台后端，支持用户创建博客文章。使用fastapi-users进行账户管理，sqlalchemy进行数据库事务，以及fastapi-jwt-auth进行用户身份验证。使用fastapi-mail实现电子邮件通知，使用fastapi-cache缓存常访问的文章。

在线课程平台：使用FastAPI设计在线课程管理后端，处理课程内容和学生注册。利用pydantic进行课程数据验证，fastapi-users进行用户身份验证，以及fastapi-jwt-auth进行令牌管理。实现fastapi-mail发送电子邮件通知，并利用fastapi-pagination管理大量课程和学生注册列表。

招聘板API：使用FastAPI开发招聘板应用程序API，专注于职位列表和候选人申请。使用fastapi-users管理申请人和招聘人账户，fastapi-jwt-auth进行安全身份验证，以及sqlalchemy管理职位条目。实现fastapi-mail发送申请跟进和职位提醒，并使用fastapi-pagination高效列出职位。

订阅服务：使用FastAPI构建订阅服务后端，支持用户订阅各种计划。利用fastapi-users进行用户管理，fastapi-jwt-auth进行安全登录，以及fastapi-mail发送订阅通知和发票。使用fastapi-limiter防止滥用订阅更改，使用fastapi-cache快速检索订阅数据。

社交网站后端：使用FastAPI创建社交网站后端。使用pydantic验证用户和帖子数据，fastapi-users处理用户配置文件和关系，以及fastapi-jwt-auth进行身份验证。使用fastapi-cache缓存热门帖子或用户数据，并实现fastapi-pagination搜索功能。

活动管理系统：使用FastAPI开发用于管理活动的后端。使用fastapi-users和fastapi-jwt-auth实现用户注册和活动创建。使用fastapi-mail发送活动邀请和更新，并使用fastapi-pagination管理大量参与者或活动。使用fastapi-cache优化活动数据检索。

食谱分享平台：使用FastAPI创建用于分享食谱的平台后端，使用pydantic进行食谱数据验证。使用fastapi-users管理用户账户和食谱提交。利用fastapi-mail进行食谱分享通知，使用fastapi-cache存储热门食谱以便快速访问。使用fastapi-pagination浏览食谱。

健身跟踪应用程序API：使用FastAPI构建健身跟踪应用程序API。使用pydantic验证锻炼和营养数据，fastapi-users进行用户管理，以及fastapi-jwt-auth进行安全身份验证。实现fastapi-mail发送每周进度总结和成就。使用fastapi-pagination管理大型活动日志，使用fastapi-cache访问常用数据。

## 优势


## 简介
使用FastAPI构建RESTful API的开发人员可以创建健壮、可扩展的应用程序，从严格遵守Python 3.12和现代库（用于身份验证、缓存和分页等任务）中受益。

## .cursorrules提示概述
该.cursorrules文件概述了使用Python 3.12以及几个框架和工具开发Python应用程序的最佳实践和指南。它指定使用pydantic、fastapi、sqlalchemy等框架，以及各种fastapi扩展用于用户管理、身份验证、电子邮件发送、缓存、速率限制和分页。依赖管理由poetry处理，推荐使用alembic管理数据库迁移。该文件还强调编码标准，如使用有意义的名称、遵循PEP 8、使用文档字符串、编写简单代码以及使用列表推导式和try-except块。其他建议包括使用虚拟环境、编写单元测试、利用类型提示，以及避免全局变量，以确保创建干净、高效和可维护的代码。