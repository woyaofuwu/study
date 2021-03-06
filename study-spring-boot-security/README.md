# study-spring-boot-security #
Spring Security 学习笔记

实现自定义登录认证

## 参考链接 ##
- Securing a Web Application [https://spring.io/guides/gs/securing-web/](https://spring.io/guides/gs/securing-web/)
- Spring Security Reference [https://docs.spring.io/spring-security/site/docs/5.2.0.BUILD-SNAPSHOT/reference/htmlsingle/](https://docs.spring.io/spring-security/site/docs/5.2.0.BUILD-SNAPSHOT/reference/htmlsingle/)
- Hierarchical Roles [https://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/#authz-hierarchical-roles](https://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/#authz-hierarchical-roles)
- FAQ [https://docs.spring.io/autorepo/docs/spring-security/4.2.x/reference/html/appendix-faq.html](https://docs.spring.io/autorepo/docs/spring-security/4.2.x/reference/html/appendix-faq.html)
- 527515025/springBoot [https://github.com/527515025/springBoot](https://github.com/527515025/springBoot)

## Spring Security ##
自定义登录
自定义权限配置
自定义密码校验

## 角色权限控制 ##
- ADMIN 角色(admin/admin) [http://localhost:8080/admin/hello](http://localhost:8080/admin/hello)
- DBA+ADMIN 角色(dba/dba) [http://localhost:8080/db/hello](http://localhost:8080/db/hello)

## 动态权限控制 ##
可以进行添加角色，用户，动态管理权限

## 角色继承 ##
目前 ADMIN > USER





