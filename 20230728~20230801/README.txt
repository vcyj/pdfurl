变更内容：
1、前端ORACLE单库总览“存储”改成“库容量”
2、邮件发送100分的不发
3、邮件发送DBA支持多邮箱
4、修复邮件通知记录下载bug
5、SFTP配置免密互信


变更步骤：
1、备份并解压替换前端包dist
2、备份并解压microservice/problem-manage-service/lib/newdt-custom-problem-1.0.jar，重启问题服务
3、SFTP配置免密互信参考《SFTP配置免密互信教程.pdf》

变更人：唐志谦、张笑笑

变更内容：
1、取消部门管理员默认拥有全部功能权限
2、健康基线邮件模板内容新增


变更步骤：
1、备份并解压替换前端包dist
2、备份并替换basic-service/lib/newdt-custom-basic-1.0.jar，重启基础服务
3、备份并替换probmeln-manage-service/lib/newdt-custom-problem-1.0.jar，重启问题服务
4、【ID1030532】容量总览-容量增长图的三级图展示数据不对，前两级图都有值，第三级图显示无值


变更人：唐志谦、张笑笑