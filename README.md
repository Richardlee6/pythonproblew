#-*- coding: utf-8 -*-
# pythonproblew

def f2(a,b,c=0,*,d,**kw):
    print('a=',a,'b=',b,'c=',c,'d=',d,'kw=',kw)

f2=(1,3,d=8,exit=None)
'''when i run it .the result is this happend: File "E:/mypython/mypython.py", line 4
    f2=(1,2,3,d=8,exit=None)
               ^
SyntaxError: invalid syntax

Process finished with exit code 1
i need help'''

