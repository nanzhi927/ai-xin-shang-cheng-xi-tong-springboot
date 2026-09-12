<!-- 全局占位符：将 {SITE_URL} 替换为正式站点地址 -->
# 爱心商城系统

本商品为「爱心商城系统」，基于 SpringBoot 技术栈开发。

## 👉 完整项目 / 演示录屏 / 更多项目：{SITE_URL}

## ✨ 功能清单

- 首页：展示平台的最新动态、热门商品、公益企业捐赠信息等内容。
- 论坛：用户可以在论坛上进行交流。
- 公告：展示平台发布的公告和通知信息。
- 商品：用户可以浏览、搜索、购买商品。
- 个人中心：用户可以管理个人信息，包括修改密码、查看订单历史、捐赠记录等。
- 个人中心：企业可以管理个人信息，修改密码等。
- 论坛管理：企业可以管理论坛板块，包括审核话题、回复用户等。
- 公告管理：企业可以发布、编辑和删除公告信息。
- 商品管理：企业可以管理商品信息，包括添加、编辑和删除商品。
- 公益企业捐赠管理：企业可以管理公益企业捐赠信息，包括捐赠金额、捐赠时间等。
- 轮播图信息：企业可以管理轮播图信息，包括添加、编辑和删除轮播图。
- 个人中心：管理员可以管理个人信息，修改密码等。
- 管理员管理：管理员可以管理其他管理员的信息，包括添加、编辑和删除管理员账号。
- 企业管理：管理员可以管理企业信息，包括添加、编辑和删除企业账号。
- 用户管理：管理员可以管理用户信息，包括添加、编辑和删除用户账号。
- 论坛管理：管理员可以管理论坛板块，包括审核话题、回复用户等。
- 公告管理：管理员可以发布、编辑和删除公告信息。
- 商品管理：管理员可以管理商品信息，包括添加、编辑和删除商品。
- 用户捐赠管理：管理员可以管理用户的捐赠记录，包括捐赠金额、捐赠时间等。
- 公益企业捐赠管理：管理员可以管理公益企业的捐赠记录，包括捐赠金额、捐赠时间等。
- 基础数据管理：管理员可以管理系统的基础数据，包括商品分类、企业类型等。
- 轮播图信息：管理员可以管理轮播图信息，包括添加、编辑和删除轮播图。

## 🛠 技术栈

- spring-boot-starter-parent: 2.2.2.RELEASE
- java.version: 1.8
- org.springframework.boot:spring-boot-starter-web
- mybatis-spring-boot-starter: 2.1.1
- org.springframework.boot:spring-boot-starter-jdbc
- org.springframework.boot:spring-boot-starter-thymeleaf
- org.springframework.boot:spring-boot-devtools
- mysql:mysql-connector-java
- shiro-spring: 1.3.2
- mybatis-plus: 2.3
- mybatisplus-spring-boot-starter: 1.0.5
- protobuf-java: 3.10.0
- commons-lang3: 3.0
- validation-api: 2.0.1.Final
- commons-io: 2.5
- hutool-all: 4.0.12
- fastjson: ${fastjson.version}

## 📁 目录结构

```
ai-xin-shang-cheng-xi-tong-springboot/
├── db/
│   └── db.sql
├── docs/
│   ├── DESENSITIZE.md
│   └── REVIEW.md
├── src/
│   └── main/
├── 运行截图/
│   ├── 1.png
│   ├── 10.png
│   ├── 11.png
│   ├── 12.png
│   ├── 13.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   ├── 6.png
│   ├── 7.png
│   ├── 8.png
│   └── 9.png
├── pom.xml
└── 运行必读.txt
```

## 🚀 快速开始

### 环境要求
- JDK 1.8+（以 `pom.xml` 为准）
- Maven 3.x
- MySQL 5.7+ / 8.x

### 步骤
1. 克隆本仓库
2. 用 IDE 打开项目根目录（含 `pom.xml` / `package.json`）
3. 导入 `db/` 或根目录下的 `*.sql` 到 MySQL
4. 修改 `src/main/resources/application.yml`（或 `.properties`）中的数据库账号密码
5. 启动主启动类（`*Application.java`）或执行 `mvn spring-boot:run`
6. 浏览器访问 `http://localhost:8080`

### 端口
- `8080`

### 账号
- - 个人中心：用户可以管理个人信息，包括修改密码、查看订单历史、捐赠记录等。
- - 个人中心：企业可以管理个人信息，修改密码等。
- - 个人中心：管理员可以管理个人信息，修改密码等。
- - 管理员管理：管理员可以管理其他管理员的信息，包括添加、编辑和删除管理员账号。
- - 企业管理：管理员可以管理企业信息，包括添加、编辑和删除企业账号。
- - 用户管理：管理员可以管理用户信息，包括添加、编辑和删除用户账号。
- http://localhost:8080/aixinshangchengixitong/admin/dist/index.html
- 管理员				账户:admin 		密码：admin
- 企业				账户:a1 		密码：123456
- 企业				账户:a2 		密码：123456
- 企业				账户:a3 		密码：123456
- 用户				账户:a1 		密码：123456

## 📸 截图

![运行截图](运行截图/1.png)
![运行截图](运行截图/10.png)
![运行截图](运行截图/11.png)
![运行截图](运行截图/12.png)
![运行截图](运行截图/13.png)
![运行截图](运行截图/2.png)
![运行截图](运行截图/3.png)
![运行截图](运行截图/4.png)
![运行截图](运行截图/5.png)
![运行截图](运行截图/6.png)
![运行截图](运行截图/7.png)
![运行截图](运行截图/8.png)

## ❓ 常见问题

**跑不起来？**
- 确认 JDK / Maven / MySQL 版本与运行必读一致；先能编译通过再启动。

**端口占用？**
- 修改 `server.port`，或关闭占用 8080 的进程。

**数据库连接失败？**
- 检查库名是否已创建、账号密码、时区与 `allowPublicKeyRetrieval` 等 JDBC 参数。

## 📚 更多开源项目

完整清单见仓库内 [`PROJECTS.md`](./PROJECTS.md)。

## 免责声明与许可

- 本仓库仅供学习交流，不包含商业授权。
- 源码来源于教学/毕设实践整理，使用风险自负。
- 转载请注明出处；请勿用于非法用途。
- 详见 [`LICENSE`](./LICENSE)。

---

**更多完整项目 → {SITE_URL}**
