while(True):
    l = input("Choose your operation and press the enter key :  +,-,*,/,% \n")

    if "+" in l:
        v1 = int(input("enter your first number="))
        v2 = int(input("enter your second number ="))
        print("this is your result = ", v1 + v2, "\n")
        continue
    elif "-" in l:
        v1 = int(input("enter your first number="))
        v2 = int(input("enter your second number ="))
        print("this is your result = ", v1 - v2, "\n")
    elif "*" in l:
        vj = int(input("enter your first number="))
        vh = int(input("enter your second number ="))
        print("this is your result = ", vj * vh, "\n")

    elif "/" in l:
        v1 = int(input("enter your first number="))
        v2 = int(input("enter your second number ="))
        print("this is your result = ", v1 / v2, "\n")
    elif "%" in l:
        v1 = int(input("enter your obtain marks = "))
        v2 = int(input("enter your maximum marks  ="))
        print("this is your percentage = ", v1 / v2 * 100, "%", "\n")

    else:
        print("Please choose suitable operation")
        break







