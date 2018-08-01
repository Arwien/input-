# input-interaction
# addition calculation

num1 = input('Enter the first number: ')
while True:
    try:
        num1 = int(num1)
        break   #The break statement is only reached
                #when there is no exception in the line before.
    except:
        print('Enter a real number!')
        num1 = input('Enter the first number: ')

num2 = input('Enter the second number: ')
while True:
    try:
        num2 = int(num2)
        break
    except:
        print('Enter a real number!')
        num2 =input('Enter the second number: ')

num3=num1+num2

print("Alright the answer is",num3)
