n=int(input("Enter the number:"))
sum=0
a=0
b=1
num=1
while(num<=n):
      print(sum,end=" ")
      num=num+1
      a=b
      b=sum
      sum=a+b

