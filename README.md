## ICT-Bigdata-UI-Class ###

오늘 ICT 폴리텍 대학 빅데이터 UI 과정 첫날입니다. 

간단히 자기소개를 마친 후 앞으로 6개월간 배우게 될 파이썬에 대해 간략히 소개를 해주셨다.

오늘 배운 내용을 아래에 정리하겠습니다.

#### print ####

print함수는 출력함수이고 앞으로 가장 많이 쓰이게 될 함수입니다.

print(100+200) 라고 입력하면 '300' 이라는 값이 출력됩니다. 단순 숫자와 연산 기호를 입력하시면 연산이 된 값이 도출됩니다.


----------------------------------------------------------------------------------------------------


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

name=input('이름 :')

age=input('나이 :')

print('제 이름은',name,'이고 나이는',age,'입니다.')

print('Hello','world',sep='',end='\T')
print('Welcome')


kor=int(input('국어점수:'))
math=int(input('수학점수:'))
eng=int(input('영어점수:'))
print('총점:',kor+math+eng,'이고 평균은',(kor+math+eng)/3,'입니다')


a=100
print(a)
a='Hello World'
print(a)

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


a=99
if a<100:
    print(a,'는 100보다 작습니다')
else:
    print(a,'는 100보다 같거나 큽니다')
