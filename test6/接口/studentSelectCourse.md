# 接口:studentSelectTeacher <a href="https://github.com/FateBerserker/is_analysis/tree/master/test6">返回</a>
### 用例:<a href="../用例/学生选课.md">学生选课</a>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;功能:学生选择已有老师授课的课程
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;权限:学生
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;API请求地址:http://entomb/testmanagersystem/login
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;请求方式:POST
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;请求实例:
	    {
			"account":"201510414406",
			"courseId":"16479"
	    }	
### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;请求参数说明:
<table cellspacing="0" style="width:600px;">
<tr>
	<td>参数名称</td>
	<td>说明</td>
</tr>
<tr>
	<td>account</td>
	<td>学生的学号</td>
</tr>
<tr>
	<td>courseId</td>
	<td>课程的Id值</td>
</tr>
</table>

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;返回实例:

	    {
			"data":null,
			"status":"success",
			"msg":"选课成功!"
		}

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;返回参数说明:

<table cellspacing="0" style="width:600px;">
<tr>
	<td>参数名称</td>
	<td>说明</td>
</tr>
<tr>
	<td>data</td>
	<td>执行后返回的数据</td>
</tr>
<tr>
	<td>status</td>
	<td>操作的成功与否,<br>
	success表示操作正常执行没有发生异常错误，<br>
	fail则表示有错误发生</td>
</tr>
<tr>
	<td>msg</td>
	<td>提示信息，以便与用户更好的交互</td>
</tr>
</table>