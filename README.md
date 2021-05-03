## ICT-Bigdata-UI-Class ###

오늘 ICT 폴리텍 대학 빅데이터 UI 과정 첫날입니다. 

간단히 자기소개를 마친 후 앞으로 6개월간 배우게 될 파이썬에 대해 간략히 소개를 해주셨다.

오늘 배운 내용을 아래에 정리하겠습니다.


---------------------------------------------------------------------------------------------------------------

#### print ####

print함수는 출력함수이고 앞으로 가장 많이 쓰이게 될 함수입니다.

print(100+200) 라고 입력하면 '300' 이라는 값이 출력됩니다. 단순 숫자와 연산 기호를 입력하시면 연산이 된 값이 도출됩니다.

print('IDLE에서 파이썬 코드를')

print('작성해서 출력해보는')

print('예제')


print("   *")

print("  ***")

print(" *****")

print("*******")

print(" *****")

print("  ***")

print("   *")
----------------------------------------------------------------------------------------------------------------------

#### input ####

input은 사용자 입력값을 ㅂ당르 수 있습니다. 입력 받는 값은 문자열(str)입니다.

name=input('이름 :')

age=input('나이 :')

print('제 이름은',name,'이고 나이는',age,'입니다.')

----------------------------------------------------------------------------------------------------------------------

### print('안녕''하세요')와  print('안녕','하세요')의 차이점 ###

위의 두 코드의 차이점은 ,(콤마)가 중간에 있느냐 이다. ,(콤마)는 띄어쓰기 되어 출력된다
print('안녕''하세요') >>>>>>>>>>>>>출력: 안녕하세요

print('안녕','하세요')>>>>>>>>>>>>>출력: 안녕 하세요

--------------------------------------------------------------------------------------------------------------
### sep ###

구분자에 의해 띄어쓰기가 되어 출력이 되는데 sep옵션을 사용하여 띄어쓰기(공백) 말고 다른 문자를 넣을 수 있도록 할 수 있습니다.

print("안녕","하세요", sep="!")>>>>>>>>>>>>>>>>>>>출력:안녕!하세요

print('010','4142','9849',sep='-')

--------------------------------------------------------------------------------------------------------------------
### end ###

edn=''는 문장을 출력하고 마지막에 무엇을 쓰고 끝낼지 정해준다

다시말하자면, end옵션을 사용하지 않고 print문을 사용하면 문장을 출력하고 개행을 하도록 되어 있는데, (end='\t')는 개행이 아니라 공백8칸을 나타내고 뒤따라 같은 행에 문장이 온다

print('Hello','world',sep='',end='\T')
print('Welcome') >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>출력 : Hello world        Welcome

-------------------------------------------------------------------------------------------------------------------------

### 변수 a,b,result를 이용하여 사칙연상을 하고 출력한다.###

ex)

a=100
print(a) >>>>>>>>>>>>>>>>>>>>출력: 100

ex)

a='Hello World'
print(a) >>>>>>>>>>>>>>>>>>>출력: Hello World

ex)

a=100

b=50

result=a+b

print(a,'+',b,'=',result) >>>>>>>>>>>>>>>>>>출력: 100 + 50 = 150

result=a-b

print(a,'-',b,'=',result)>>>>>>>>>>>>>>>출력: 100 - 50 = 100

result=a*b

print(a,'*',b,'=',result)>>>>>>>>>>>>>>>출력: 100 * 50 = 5000

result=a/b

print(a,'/',b,'=',result)>>>>>>>>>>>>>>>출력: 100 / 50 = 2

-----------------------------------------------------------------------------------------------

# : 해당하는 줄만 주석처리

''' 코드 ''' : 여러 줄을 주석처리하고 싶을때 


'''      

print("   *")

print("  ***")
print(" *****")

print("*******")
print(" *****")

print("  ***")

print("   *")

'''
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>출력: 아무것도 나타나지 않음

----------------------------------------------------------------------------
###a/b= 몫, a%b= 나머지 ###

a=100

b=10

print(a/b)

print(a%b)

print(a,'/',b,'=','몫:',a/b,'나머지:',a%b) >>>>>>>>>>>>>>>>>>>>>>>>>>>출력:100 / 10 = 몫: 10.0 나머지: 0
--------------------------------------------------------------------------------------------------------------------

### /와 // 차이점

/는 나눈 값이 실수로 값이 나타나고 //는 나눈 값이 정수로 나타난다

a=10

b=3

print(10/3)>>>>>>>>>>>>출력:3.3333333333333335

print(10//3)>>>>>>>>>>>>출력:3
---------------------------------------------------------------------------------------------------------------------
 ### =와 ==의 차이점
 
 =는 = 뒤에 나오는 값이나 문자를 = 앞에 나오는 곳에 대입을 하는 의미이고, ==는 ==의 앞과 뒤의 문자나 값이 동일하다는 의미이다
 ---------------------------------------------------------------------------------------------------------------

a=99
if a<100:
    print(a,'는 100보다 작습니다')
else:
    print(a,'는 100보다 같거나 큽니다')
