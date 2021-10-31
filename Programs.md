# to find the summation of numbers
s=input("Enter the string:")
length=len(s)
sum=0
for i in range(length):
    sum+=int(s[i])
print(sum)
