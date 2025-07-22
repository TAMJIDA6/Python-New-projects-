# Python-New-projects-
Problem solving 
def welcome_user():
    name = input("Enter your name: ")
    age = int(input("Enter your age: "))

    print("Welcome,", name)

    if age >= 18:
        print("You are eligible to register.")
    else:
        print("Sorry, you are too young to register.")

welcome_user()
