''' check whether the given input is a leap year for 4 yrs and centurians by if-else'''
y= int(input("enter year:"))
if y%4==0 or y%100==0 or y%400==0:
    print(y, "is a leap year")
else:
    print(y, "is not a leap year")
