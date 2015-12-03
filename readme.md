Release Note
       
可执行版本[需要 NET Framework 4.6] 更新时间:2015/12/01 16:00
下载地址:  <http://files.cnblogs.com/files/TextEditor/ReleaseVersion.zip>
GitHub 项目地址 <https://github.com/magicdict/MongoCola/>
版本号：Ver 1.5(Beta)

开发和测试环境

操作系统：
Windows 7
Windows 10

运行时：
NET Framework 4.6
MongoDB 3.2.0 RC4

驱动程序
CSharp Mongo Driver 2.2.0-RC0

=============================================
=                  计划
=============================================
0.Fix Bug
	解决所有发现的Bug 
1.Config Options
	一个MongoService用Config File文件的生成工具 
2.扩大Model.TryUpdate的使用范围
	Winform使用了MVC的概念，自动将Model和UI双向绑定
	已经在frmConnnection/frmOption里面尝试了
3.MutliLanguage
	进一步改进多语言系统
4.User System
	用户系统

=============================================
=                  发布履历
=============================================
Ver 1.5(Beta)  2015/11/30 @ Shanghai China
MongoDB 3.2.0 新功能对应版本
1.Text Search V3 的对应：大小写敏感
2.Partial Index 的创建  
3.独立外部工具 Configuration Creator 初版
4.创建Collection时候可以设定DocumentValidation参数
5.MongoDump 增加 --gzip --archive
6.修复添加Collection后UI没有实时更新的BUG 

=============================================
Ver 1.5(Alpha)  2015/07/09 @ Shanghai China
重构代码，Mongo业务代码和界面代码分开
新代码尽可能适配MongoDriver2.0.1
MongoServer尽可能用MongoClient代替
窗体TabPage管理功能的独立化
TextSearch功能的修改（MongoDB 2.6之后使用不同的方法）
各种Status改用树型结构表示
新建数据库无效,删除数据库错误等问题.

=============================================
=                  已知BUG
=============================================
1.新建数据库时,必须要新建一个数据集.
