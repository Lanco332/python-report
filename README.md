# 南華大學Python程式設計-期中報告
11124233 黃文龍 11125005 林啟陽
## 生成一個包含50個隨機整數的清單
```
import random
x=[random.randint(0,100)for i in range(50)]
print(x)
```
## 刪除其中所有奇數
```
i=len(x)-1
while i >= 0:
  if x[i] % 2 == 1:
    del x[i]
  i-=1
print(x)
```
## 實作畫面
![image](https://github.com/Lanco332/python-report/blob/main/python-report.png)
