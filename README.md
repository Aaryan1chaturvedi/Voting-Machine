# Voting-Machine
made a voting machine using if and else statement with  the help of python language in which the program ask the user's age and his choice for the voting party.



print("Welcome to the Voting Machine!")
age = int(input("Enter your age: "))

if age < 18:
    print("You can't vote")
else:
    print("You can vote!")
    print("Choose your party:")
    print("A. BJP")
    print("B. Congress")
    print("C. AAP")

    choice = input("Enter your choice (A for BJP and B for congress): ")
    if choice == "A":
        print("You voted for the BJP. Thank you!")
    elif choice == "B":
        print("You voted for the Congress. Thank you!")
    elif choice == "C":
        print("You voted for AAP.  Thank you")
    else:
        print("Invalid choice. Please select A for BJP or B for Congress or C for AAP.")
