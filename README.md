# 19th-Aprl
1
22
333
4444
55555

i = 1
j = 1
x = int(input("Enter the number : "))
for i in range (1,x+1):
        for j in range (1,i+1):
            print(i,end=' ')
        print()
        
  palindrome
  
  num=int(input("Enter a number:"))
temp=num
rev=0
while(num>0):
    dig=num%10
    rev=rev*10+dig
    num=num/10
if(temp==rev):
    print("The number is palindrome")
else:
    print("Not a palindrome")
    
    armstrong num
num = int(input("Enter a number : "))
sum = 0
temp = num
while temp > 0:
    digit = temp % 10
    sum += digit * digit * digit
    temp = temp//10
 
if sum==num:
    print('It is an Armstrong number')
else:
    print('It is not an Armstrong number')
 
 
 fibonacci 
 num = int(input())
n1, n2 = 0, 1
print("Fibonacci Series:", n1, n2, end=" ")
for i in range(2, num):
    n3 = n1 + n2
    n1 = n2
    n2 = n3
    print(n3, end=" ")


    
