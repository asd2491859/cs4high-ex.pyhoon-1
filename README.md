#學習重點1

##學習重點2

###學習重點3







學習重點1.使用range 函式 的功能建立整數循序數列
2.使用for 廻圈 執行固定次數的廻圈運算(通常)
3.使用while 廻圈執行沒有固定次數的廻圈運算
4.使用continue 指令--- 通常也是用於廻圈中，是在廻圈執行中途暫時停住不往下執行，而跳到廻圈的起始處執行
5.使用break 指令 通常用於廻圈中，可以在廻圈執行中途強迫跳離廻圈，跳到廻圈後面的程式繼續執行。
6.廻圈中又包含廻圈的 巢狀廻圈(nested loop)設計===九九乘法表
教科書作業:
Unit 5:重複執行的作業
Ch16-19
range的技術
range的技術(1)
list1=range(6)
list1
答案是:[0, 1, 2, 3, 4, 5]
range的技術(2)
list2=range(1,6)
list2
答案是:
range的技術(3)
list3=range(1,6,2)
list3
答案是:
range的技術(4)
for dd in range(6):
   print(dd)
答案是:
程式閱讀題:下列程式執行後會印出什麼？
list1=range(10)
list2=range(1,10)
list3=range(1,10,2)
list4=range(10,1,-2)

print(list(list1))
print(list(list2))
print(list(list3)) 
print(list(list4))  

答案是:
for 迴圈技術

程式閱讀題:下列程式執行後會印出什麼？
numbers = [21, 4, 35, 1, 8, 7, 3, 6, 9]
my_numbers = []

for number in numbers:
    if (number % 2 != 0): 
　　my_numbers.append(number)

print(my_numbers)
程式設計題:1+2+3+....n的計算
輸入::一個正整數 n
輸出::當使用者輸入一個正整數 n 後，程式就會顯示由 1+2+3+...+n 的總和
限制條件:使用 while 設計這個程式
程式設計題:完成等差數列的總和計算:1+5+9+13+ ...+81

程式設計題:完成等差數列的積和計算:1乘5乘9乘13乘 ...乘33

程式設計題:n階程的計算
n階程的計算:n!=1*2*3*⋯*n
1!=1、2!=1*2=2、3!=1*2*3=6
輸入::一個正整數 n
輸出::當使用者輸入一個正整數 n 後，程式就會顯示由 1*2*3*...*n 的乘積
限制條件:使用 while 設計這個程式
while 迴圈技術

fruits = ["香蕉","蘋果","橘子","鳳梨","西瓜"]

while True:
    fruit = input("請輸入喜歡的水果(Enter 結束)：")

    if (fruit==""):
        break

    n = fruits.count(fruit) 
    if (n>0):  # 串列元素存在
        p=fruits.index(fruit)
        print("%s 在串列中的第 %d 項" %(fruit,p+1))
    else:
        print(fruit,"不在串列中!")
程式閱讀題:下列程式執行後會印出什麼？
n = int(input("請輸入正整數："))

for i in range(1, n+1):
    if i % 5 ==0:
        continue
    print(i,end=" ")
程式設計題:1+2+3+....n的計算
輸入::一個正整數 n
輸出::當使用者輸入一個正整數 n 後，程式就會顯示由 1+2+3+...+n 的總和
限制條件:使用 while 設計這個程式
程式設計題:n階程的計算
n階程的計算:n!=1*2*3*⋯*n
1!=1、2!=1*2=2、3!=1*2*3=6
輸入::一個正整數 n
輸出::當使用者輸入一個正整數 n 後，程式就會顯示由 1*2*3*...*n 的乘積
限制條件:使用 while 設計這個程式



