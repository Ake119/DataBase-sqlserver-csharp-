# 期末数据库SQl Server大作业
* 使用VS2022 C#语言进行开发
* 项目解决方案被误删不能恢复 仅剩设计文档及数据库文件
* 设计文档包含相应代码截图及系统布局截图


## 导入数据库文件
EXEC  sp_attach_db  @dbname  =  '你的数据库名',      
@filename1  =  'mdf文件路径（包缀名）',     
@filename2  =  'Ldf文件路径（包缀名）'