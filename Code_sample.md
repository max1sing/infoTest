# Code Sample

# This code sample was written by me

def cone_numbers():
    """
    This function multiplies by pi and radius, and divides height by 3
    """
    #prompt the user for the numbers
    number1 = float(input("Please enter the radius of the cone: "))
    number2 = float(input("Please enter the height of the cone: "))
    number3 = 3.14159265359
    # calculate the numbers to make the cone
    result = number3 * number1 * number1 * number2 / 3

    return result


def cube_numbers():
    """
    This function multiplies the length of the cube
    """
    #prompt the user for the number
    number1 = float(input("Please enter the length of the cube: "))

    # calculate the numbers to make the cube
    result = number1 * number1 * number1

    return result

def cylinder_numbers():
    """
    This function multiplies the radius, height, and pi
    """
    #prompt the user for two numbers
    number1 = float(input("Please enter the radius of the cylinder: "))
    number2 = float(input("Please enter the height of the cylinder: "))
    number3 = 3.14159265359
    # calculate the numbers to make a cylinder
    result = number3 * number1 * number1 * number2

    return result

# print a menu for the user
print("Choose an option below")
print("1. Calculate volume of a cone")
print("2. Calculate volume of a cube")
print("3. Calculate volume of a cylinder")

# get the user's menu choice
print()
user_choice = input("Enter your menu choice: ")

# call the function and get the result
if (user_choice == "1"):
    total = cone_numbers()
elif(user_choice == "2"):
    total = cube_numbers()
elif(user_choice == "3"):
    total = cylinder_numbers()
else:
    print("Error: You entered a horrific value, goodbye!")
    exit()
    
#print the result    
print()
print("The result is: " + str(total))

[return to home page](./README.md)