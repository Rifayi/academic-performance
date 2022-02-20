# academic-performance
a=str(input("Enter your name:"))
b=str(input("Enter your group:"))
c=input("Enter your roll no:")
d=input("Enter your semester :")
e=float(input("enter your attendence percentage:"))
if(e>=90):
    print("excelent")
elif(e>=80 and e<=90):
    print("good")
else:
    print("poor")
f=float(input("Enter your CGPA:"))
if(f>=9.0):
    print("Excelent")
elif(f<=6.0):
    print("poor")
else:
    print("good")
g=str(input("Any sports played:"))
if(g=="yes"):
    print("Enter the sports played:")
else:
    print()
