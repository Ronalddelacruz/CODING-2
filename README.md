# CODING-2
LOOP SYSTEM

num1 = 5
attemp = 0

while attemp < 5:
    print("guess number 1 to 5: ")
    num2 = int(input("Number: "))
    attemp = attemp + 1
    if num1 == num2:
        print("correct")
        break
    else:
        print("incorrect")
