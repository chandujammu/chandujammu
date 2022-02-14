#program for sum of digits in a given number

n=int(input("Enter a number:"))
tot=0
while(n>0):
    dig=n%10
    tot=tot+dig
    n=n//10
print("The total sum of digits is:",tot)
 
Output:
Enter a number:1892
The total sum of digits is: 20
 
