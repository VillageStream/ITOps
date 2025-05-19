SQL Server日常运维中同仁误删除Table资料，执行恢复时对整个数据库，故需对Table的资料进行二次提取

使用SSMS 2017 及以上工具将表的数据导入sql文本，以便资料转移
操作步骤：

	* 选择数据对象，右键‘Tasks’
	* 在选项列表中选择 ‘Generate Script’
	* 对话框选择‘下一步’
	* 选择需要的对象或表‘<表名称>’
	* 选择右侧‘Advanced’高阶选项中‘Types of data to script’->‘Data Only’
	* 选择存放位置
	* 生成概要文件
	* 执行情况
	* 查看SQL文本生成的语句



#选择数据对象

![Image](https://github.com/user-attachments/assets/47a4df6d-3e0b-4301-b33d-eef4e6aae101)
![Image](https://github.com/user-attachments/assets/0674140a-8f81-4306-9f8b-105ffdc3b6e1)

#选择需要的对象或表

![Image](https://github.com/user-attachments/assets/27057646-dd6f-4ed8-bd47-58ed9d2cf854)

#选择右侧‘Advanced’高阶选项中‘Types of data to script’->‘Data Only’

![Image](https://github.com/user-attachments/assets/b191fa83-8758-4b84-ad2f-683454d5f7eb)

#选择存放位置

![Image](https://github.com/user-attachments/assets/a3fd5a45-cff4-467a-94fb-562f115fa18b)

#生成概要文件

![Image](https://github.com/user-attachments/assets/40db2cde-d949-45f9-96d0-d569f07e3f9e)

#执行情况

![Image](https://github.com/user-attachments/assets/ff522bf9-c894-4c62-a69b-b0f63e6837e9)

#查看SQL文本生成的语句
![Image](https://github.com/user-attachments/assets/6556f489-6c79-4371-b205-27568a0001f9)

