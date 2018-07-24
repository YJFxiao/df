# df
ses=open('新建文本文档.txt',encoding='gbk').readlines()
f=open('t1.txt','a',encoding='gbk')
for line in s:
    f.write("'"+line.split(',')[0].split('(')[1]+"'"+",")
    
s=open('新建文本文档.txt',encoding='gbk').readlines()
f=open('t2.txt','a',encoding='gbk')
for line in s:
    f.write(line.split(',')[1].split(')')[0]+',')
