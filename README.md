# python-lab-10
def division_OF_TWO_NUMBERS():
    try:
        a=int(input("enter the value = "))
        b=int(input("enter the value = "))
        c=a/b
    except ValueError:
        print("please enter correct details")
    except ZeroDivisionError:
        print("the zero is detected")
    else:
        print(f"the division of {a} and {b} is {c}")
    finally:
        print("the whole code is executed")
division_OF_TWO_NUMBERS()
#output:-enter the value = 3
enter the value = 5
the division of 3 and 5 is 0.6
the whole code is executed


