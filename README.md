# 葫芦侠自动签到所有板块

葫芦侠自动签到所有板块

# 本地运行

打开编辑脚本将账号填入然后运行python3 huluxia.py

# 阿里云云函数自动运行

1.函数自动运行需要将'user.json'修改为'/tmp/user.json'

2.将main函数增加参数def mian(event, context):

3.把main函数中的main() 修改为 mian('','')

4.设置函数的定时触发器
