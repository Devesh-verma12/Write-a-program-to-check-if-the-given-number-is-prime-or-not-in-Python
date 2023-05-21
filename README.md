# Write-a-program-to-check-if-the-given-number-is-prime-or-not-in-Python

i,temp=0,0
n = int(input("Enter a Number : "))
for i in range(2,n//2):
    if n%i == 0:
        temp=1
        break
if temp == 1:
    print("given number is not prime")
else:
    print("given number is prime")
