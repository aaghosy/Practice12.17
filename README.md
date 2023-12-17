# Practice-12.17

### 习题 1：变量赋值和类型
定义三个变量：一个存储整数，一个存储浮点数，一个存储字符串。然后打印出这三个变量的值和类型。

### 习题 2：类型转换
给定一个字符串 `"123"` 和一个整数 `456`，将字符串转换为整数，然后将这两个数字相加，打印结果。

### 习题 3：字符串操作
定义一个字符串 `"Python"`，使用索引和切片来打印出 `"Py"` 和 `"hon"`。

### 习题 4：列表操作
创建一个包含任意五个数字的列表。完成以下任务：
1. 打印列表的第二个和第四个元素。
2. 将列表中的第三个元素改为 `"Python"`，然后打印整个列表。

### 习题 5：字典基础
创建一个字典，它包含至少三对键值对，其中键是国家名称，值是该国的首都。例如，`{"中国": "北京", "日本": "东京", "美国": "华盛顿"}`。完成以下任务：
1. 打印出指定国家的首都。
2. 添加一个新的国家和首都到字典中，然后打印整个字典。

###习题1: 
int_var = 10
float_var = 2.5
str_var = "hello world!"

print("整数变量的值:", int_var, "类型:", type(int_var))
print("浮点数变量的值:", float_var, "类型:", type(float_var))
print("字符串变量的值:", str_var, "类型:", type(str_var))

### 习题 2：
str_num = "123"
int_num = 456
converted_str_to_int = int(str_num)
result_of_num = converted_str_to_int + int_num 

### 习题 3
str_var= "python"
py = str_var[0:2]
hon = str_var[3:]

### 习题 4：列表操作
numbers = [1,2,3,4,5]
second_element = numbers[1]
forth_element = numbers[3]
python = numbers[2]

### 习题 5：字典基础
capitals = {"中国": "北京", "日本": "东京", "美国": "华盛顿"}
capitals["法国"] = "巴黎"
