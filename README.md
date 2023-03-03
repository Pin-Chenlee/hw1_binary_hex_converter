# hw1_binary_hex_converter
num = input("please enter number :")
num=int(num)
if num >=128:
    num1 = 1
    num=num-128
else:
    num1 = 0

if num >=64:
    num2 =1
    num=num-64
else:
    num2 = 0

if num >=32:
    num3 =1
    num=num-32
else:
    num3 = 0

if num >=16:
    num4 =1
    num=num-16
else:
    num4 = 0
    
if num >=8:
    num5 =1
    num=num-8
else:
    num5 = 0

if num >=4:
    num6 =1
    num=num-4
else:
    num6 = 0
    
if num >=2:
    num7 =1
    num=num-2
else:
    num7 = 0
    
if num >=1:
    num8 =1
    num=num-2
else:
    num8 = 0

print(num1,num2,num3,num4,num5,num6,num7,num8)

x=num1*8+num2*4+num3*2+num4*1
y=num5*8+num6*4+num7*2+num8*1

if x==10:
    x="A"
if x==11:
    x="B"
if x==12:
    x="C"
if x==13:
    x="D"
if x==14:
    x="E"
if x==15:
    x="F"
    
if y==10:
    y="A"
if y==11:
    y="B"
if y==12:
    y="C"
if y==13:
    y="D"
if y==14:
    y="E"
if y==15:
    y="F"
print(x,y)
