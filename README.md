 `print("Hello World!)`
*   就从这句话开始吧，毕竟，是世界你好啊！ 
# python基础篇
## 关于列表的一些用法
```user=['001','张三','男',18]
print("1.产品用户")
print(user)

# len()函数可以获取列表的长度
len(user)
print("列表长度")
print(len(user))

#通过索引访问列表中具体的数值
print('访问列表')
print(user[1])

#当列表来了一个新成员可以通过apend函数添加
user.append('孙悟空')
print(user)

#又来了一个新成员，不过这次的是VIP用户，只能把它放在前面啦，这时候，可以使用insert函数了
user.insert(0,"唐僧")
print(user)

#我看张三不顺眼，消灭它的时候就可以使用del函数啦
user.pop(2)
print(user)

#我想修改001了，这时就可以使用重新赋值的方法啦
user[1]='八戒'
print(user)

#貌似这些信息都不是完整的，那么我们使用空间中的空间来储存数据？列表也可以是另一个列表
newuser=[['001','唐僧',18,'男'],['002','猴子',18,'男']]
print(newuser)```
