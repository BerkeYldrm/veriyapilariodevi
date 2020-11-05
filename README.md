# veriyapilariodevi(faktoriyelhesabi)
Bu depo Karadeniz Teknik Üniversitesi Bilgisayar Mühendisliği Veri Yapıları dersi ödevi için hazırlanmıştır


#Iterative solution

1.fact = 1
2.
3.print("Enter the number to be calculated with a factorial")
4.
5.n = int(input())
6.
7.if n==0 or n==1:
8.  print("Factorial of ",n,"=1")
9.elif n<0:
10.  print("Factorial calculations are not made for numbers less than 0!")
11.else:
12.  for i in range(1,n+1):
13.    fact = fact * i
14.  print("Factorial of",n,"=",fact)


#Recursive solution

1.def fact(num):
2.  if num==0 or num==1:
3.    return 1;
4.  elif num<0:
5.    return "error"
6.  else:
7.    return num * fact(num-1)
8.
9.print("Enter the number to be calculated with a factorial")
10.
11.n = int(input())
12.
13.print(fact(n))

Hazırlayan(lar):

Burak İbaoğlu - 365316
