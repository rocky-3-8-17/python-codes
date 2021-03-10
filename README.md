# python-codes
#Divisor and common divisors 

a=int(input("input a positive integers: "))
b=int(input("input a positive integers: "))
print ("divisors")
print(a,":",end=" ")
for x in range(1,a+1):
    if a%x==0:
        print(x,end=" ")
print()
print(b,":",end=" ")
for y in range(1,b+1):
    if b%y==0:
        print(y,end=" ")
print()
print("common divisors")
for z in range(1,a+b+1):
    if a%z==0 and b%2==0:
        print(z,end=" ")
