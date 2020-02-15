# MyPython


# Python Runoob https://www.runoob.com/python3/python3-tutorial.html
# Python 入門教學  https://docs.python.org/zh-tw/3/tutorial/index.html
# https://docs.python.org/3/library/functions.html

# 深度學習 http://moocs.nccu.edu.tw/course/172/intro

# 機器學習 https://www.youtube.com/watch?v=CXgbekl66jc&list=PLJV_el3uVTsPy9oCRY30oBPNLCo89yu49

# 資訊安全技術 https://www.youtube.com/watch?v=Y-V9LLJHfjQ&list=PLFCAlv-jS6C5E7Qh4ZWvHH4WCyxGMwuo3&index=9

# 更詳細的課程 https://www.youtube.com/watch?v=o0b4e6poCuU&list=PLTUz0iSGGyykaahKxzU0dF80TtVfmM-dC

# 爬蟲實戰 https://www.youtube.com/watch?v=9Z9xKWfNo7k


# 什麼是機器學習（Machine Learning）？

`````````
機器學習是一種資料科學的技術也是一種實現人工智慧的一種方式

協助電腦從現有的資料學習，以便預測未來的行為、結果和趨勢
根據學習的方式又可以分為需要解答的監督式學習（Supervised learning）
非監督式學習（Unsupervised learning）和增強學習（Reinforcement learning）等

`````````

# 「強人工智慧（Strong AI）和「弱人工智慧」（Weak AI）

`````````
「強人工智慧」指的是有自我意識、有知覺可以自己推理和解決問題的機器智慧

「弱人工智慧」只能模擬人類的思維與行為表現，但缺乏真正的推理與解決問題的能力，也不具有自主意識。
 
`````````

`````````
a = 1
b = 2.0
print(type(a))
print(type(b))

`````````

`````````
a = 1
b = 1.0
print(a==b)
print(a!=b)

`````````

````````
a = 0b11 # 二進制
print(a)
a = 0o11 # 八進制
print(a)
a = 0x11 # 十六進制
print(a)

````````
````````
a = 10
b = 3
print(a/b)  # a除b
print(a%b)  # 取餘數
print(a//b) #只取整數

# ** 次方

print(a**2)

# 正負號
a = 3
b = -a
print(b)

````````

````````
a = input("Input a number:")
print(a)
print(type(a))

# 型別轉換

strA = input("Input a number:")
print(type(strA))
a = int(strA)
print(type(a))

```````

```````
a = eval(input("Input your name"))
b = eval(input("Input your name")) 
print(a+b)
print(a-b)
print(a*b)         # 運算值
print(a/b)
print(a%b)
print(type(a))
print(type(b))

```````
a = input("Input you number")
b = input("Input you number")

intA = int(str(a))
intB = int(str(b))

print(intA+intB)
print(intA-intB)
print(intA*intB)
print(intA/intB)
print(intA%intB)

```````
a = 3
b = 5
a,b = b,a  數值對調
print(a)
print(b)

tmp = a
a = b
b = tmp
print(a)
print(b)

```````

score = int(input("number"))
if score < 100:
    print("true")
else:
    print("= =")

```````

a = 1+2j
b = 3+5j
c = a + b
print(c)
print(c.real)
print(c.imag)

```````

name = 'wang'"long""jie"
print(name)

s = "A"
s = s*10
print(s)

fullname = "wang\tlong\tjie"  跳脫字元
print(fullname)

fullname = r"wang\tlong\jie"
print(fullname

```````

name1 = input("請輸入第一位學生的姓名：")
score1 = input("請輸入第一位學生的成績")

name2 = input("請輸入第二位學生的姓名：")
score2 = input("請輸入第二位學生的成績")

intscore1 = int(str(score1))
intscore2 = int(str(score2))

print("姓名\t\t成績")
print(name1 + str(score1))
print(name2 + str(score2))
print("成績的總分為:",intscore1 + intscore2)

```````
