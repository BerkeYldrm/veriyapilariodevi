# veriyapilariodevi
Bu depo Karadeniz Teknik Üniversitesi Bilgisayar Mühendisliği Veri Yapıları dersi ödevi için hazırlanmıştır


#Iterative solution

fact = 1

print("Enter the number to be calculated with a factorial")

n = int(input())

if n==0 or n==1:
  print("Factorial of ",n,"=1")
elif n<0:
  print("Factorial calculations are not made for numbers less than 0!")
else:
  for i in range(1,n+1):
    fact = fact * i
  print("Factorial of",n,"=",fact)


#Recursive solution

def fact(num):
  if num==0 or num==1:
    return 1;
  elif num<0:
    return "error"
  else:
    return num * fact(num-1)

print("Enter the number to be calculated with a factorial")

n = int(input())

print(fact(n))

Hazırlayan(lar):

Burak İbaoğlu - 365316
