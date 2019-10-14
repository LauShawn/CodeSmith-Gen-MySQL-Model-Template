# CodeSmith-Gen-MySQL-Model-Template
CodeSmith生成MySQL实体模板

## 替换DLL
替换解压或安装后的目录CodeSmith_jb51\v7.0\SchemaProviders中的SchemaExplorer.MySQLSchemaProvider.dll文件为本文件夹里修改过的dll

## 创建模板
打开CodeSmith_jb51\v7.0目录中的TemplateEditor.exe程序，在My Templates上右键新建CodeSmith Generator Template (CSharp)类型文件，并分别复制以下两个文件：
* AutoGenDO.cst用于生成数据库实体
* AutoGenDTO.cst用于生成传输层实体或展示层实体

## 添加新的Mysql连接信息并选择想要生成的表
server=...;port=3306;User Id=...;database=...;password=...

## 输入命名空间，点击Generate即可生成相应的类。
