
print("Welcome in EvenOdd game")
print("Please press (x) to exit game")
while True :
    number = input("Please Enter a number: ")

    if number == "x":
        print("exit Game")
        print("Thank you...")
        print("-------Exit------")
        break
    try:
        number = int(number)
        if number % 2 == 0:
            print("{0} is Even Number".format(number))

        else:
            print("{} is Odd Number".format(number))

    except ValueError:
        print("Please Enter a Valid Number")


    print("----------------------")