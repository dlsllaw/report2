# Python期中作業
11024250 陳翰翔
## 求解任意一個一元二次方程，從鍵盤輸入各項係數
```
mport math
s=input("請輸入你要求的一元二次方程的三個參數a、b、c,用逗號隔開")
a,b,c=s.split(',')
a=int(a)
b=int(b)
c=int(c)
```
## 輸出判斷式的結果
```
if a==0:
   print(-c/b)
elif b*b-4*a*c<0:
   print("沒有結果")
elif b*b-4*a*c==0:
   print(-b/(2*a))
else:
   print((-b+math.sqrt(b*b-4*a*c))/(2*a),(b-math.sqrt(b*b-4*a*c)/(-2*a)))
```
# 實作結果
![Example Images](2.png.png)
