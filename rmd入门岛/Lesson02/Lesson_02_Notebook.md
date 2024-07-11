书生大模型实战营-第三期-L0-Python


#任务1

编写python统计单词的程序

#设置环境

使用vscode连接远端服务器 





编写python统计单词的程序

#思路

1.获取输入字符串

2.将字符串设置为小写

3.去除字符串里面标点符号，替换为空格

4.对替换后的字符串进行split，过滤的字符为空格

5.将split结果存入字典，如果key相同则加1，如果key不存在说明是首次添加，需要设置为值为1

6.输出字符串

代码：

# coding: utf-8

biaodian='''!;.(){}[]?!:<>-,@#$%^&*\r\n'''

input="""Hello world!  

This is an example.  

Word count is fun.  

Is it fun to count words?  

Yes, it is fun!"""

print("input is ", input)

str = ""

for ch in input:

    if ch not in biaodian:

        str = str + ch

    else:

        str = str + " "

print("str is ", str)

str2 = str.lower()

words = str2.split()

word_count = {}

for word in words:

    if word in word_count:

        word_count[word] = word_count[word] + 1

    else:

        word_count[word] = 1

print("word_count is ", word_count)

输出结果



#debug过程







左上角查看本地变量

