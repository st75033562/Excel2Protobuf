配置路径路径：
项目名/Tools/Excels

表中工作簿命名必须是首字母大写的英文。@开头的工作簿名除外(@开头表示不打的表，可作为备注使用)

行规范：
第一行注释行(方便自己读懂)
第二行变量名，首字母必须大写
第三行变量类型

|   |   |  |
| --- | --- | --- |
| int32 | 数字 | |
| string | 字符串 |  |
| Dic_int32 | 字典 (key是int32)	 | 仅第三行第一列有效 |
| Dic_string | 字典 (key是是字符串	)	 | 仅第三行第一列有效 |

编译分两步
第一步： Tools->ExcelBuild->ToProtobuf->生成c# 等编译完成  
第二步： Tools->ExcelBuild->ToProtobuf->生成数据文件

