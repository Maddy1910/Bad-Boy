name=(input("Enter your name: "))
print("Name: ",name)
age=0
while True:
    how_old=input("\nEnter your age: ")
    if how_old=="No":
        print("Don't be Ashamed of your age!")
    break
num=int(how_old)
age=age+num
print("Your age is: ",age)
gen=(input("\nEnter your Gender: "))
print("Gender: ",gen)
add=(input("\nEnter your Addres: "))
print("Your address is: ",add)
year=(input("\nEnter your Current Year(FY,SY,TY): "))
if year=='FY':
    print("You are Beginner")
elif year=='SY':
    print("You are middle position of Degree")
else:
    print("Now you are Intelligent")
mobi=int(input("\nEnter your Mobile No.: "))
print("Mobile No.: ",mobi)
mail=(input("\nEnter your E-mail ID: "))
print("E-mail ID: ",mail)
blood=(input("\nChoose your Blood Group(O+,AB+,A+,B+): "))
if blood=='O+':
    print("Your blood group is O+")
elif blood=='AB+':
    print("Your blood group is AB+")
elif blood=='A+':
    print("Your blood group is A+")
else:
    print("Your blood group is B+")
print("\nFound Your Face")

fc=(input("\nDisplay your Face(Yes Or No): "))
if fc=='Yes':
    import random
    MyList=["    ______\n"
            "   /      \ \n"
            "  /        \ \n"
            " |  @   @   | \n"
            " |    |     | \n"
            "  \  \_/   / \n"
            "   \      / \n"
            "    \____/ \n"
            ,
            "    ______\n"
            "   /      \ \n"
            "  /        \ \n"
            " |  @   @   | \n"
            " |    |     | \n"
            "  \        / \n"
            "   \  O   / \n"
            "    \____/ \n"
            ,
            "    ______\n"
            "   /      \ \n"
            "  /        \ \n"
            " |  @   @   | \n"
            " |    |     | \n"
            "  \        / \n"
            "   \  X   / \n"
            "    \____/ \n"
            ,
            "    ______\n"
            "   /      \ \n"
            "  /        \ \n"
            " |  @   @   | \n"
            " |    |     | \n"
            "  \  ___   / \n"
            "   \      / \n"
            "    \____/ \n"]
    print(random.choice(MyList))
else:
    print("\nYou are looking Very Ugly")

