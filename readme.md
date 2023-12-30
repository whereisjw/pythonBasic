```
print('안녕')
python app.py
```

실행

```
이름 = '슈퍼 에이전트 하이퍼 초필살 드래곤'

print(이름[0:2])
```

변수 // 결과는 슈퍼

```
중고차 = ['k5', 'white', 5000]

print(중고차[0])
```

리스트 자료형

```
중고차 = ['k5', 'white', 5000]
중고차[1] = 'black'
print(중고차[1])
// 결과 black
중고차 = ['k5', 'white', 5000]
중고차2 = {'brand':'bmw', 'model' : '520d'}

print(중고차2['brand'])
//bmw
```

조건문

```
재고량 = 10

if 재고량>0 :
   print('지금주문가능합니다')
```

```
중고차재고 = ['k5','bmw','Tico']

if 'k5' in 중고차재고:
   print('지금주문가능합니다')
//주문가능합니다
중고차재고 = ['k5','bmw','Tico']

if 'k7' in 중고차재고:
   print('지금주문가능합니다')
else :
       print('지금 주문 불가능함')
//지금주문불가능함
```

for 문

```
 for i in range(0,10) :
    print('k5 있어요')

중고차들 = ['k5','bmw','Tico']
for i in 중고차들 : print(i)
```

함수만들기

```
def 인사하기 (구멍) : print(구멍+1)


인사하기(12333);
```

# 변수
~~~
a= 2
b = 3
c = a+ b
c = 1
a=1
b=10

print(c) //출력 1
~~~

my_name = nico
//NameError: name 'nico' is not defined
""" my_name = 'nico'

print(my_name) """

""" my_name = "12" """
""" 이경우 12 는 스트링임 """
""" bol = True

print(bol)
Booleans  타입 첫글자는 반드시 대문자로 적어야함 
 """


 ~~~
 def 안녕함수():
    print("ㅎㅇㅎㅇ") //두칸을 들여쓰기해야함
    
안녕함수()
안녕함수()
안녕함수()
안녕함수()
안녕함수()
//ㅎㅇㅎㅇ
ㅎㅇㅎㅇ
ㅎㅇㅎㅇ
ㅎㅇㅎㅇ
ㅎㅇㅎㅇ
~~~
def 안녕함수():
    print("ㅎㅇㅎㅇ")
def 바이함수():
    print('ㅂㅇㅂㅇ')
    안녕함수()
 
바이함수()
def 안녕함수(이름,나이):
    print(이름,"ㅎㅇㅎㅇ",나이,'살임?')
 
 
안녕함수('익점',12)
안녕함수('루이스',10)
""" 익점 ㅎㅇㅎㅇ 12 살임?
루이스 ㅎㅇㅎㅇ 10 살임? """

조건문
~~~
a = 10

if a == 10 : 
    print('correct')
~~~
