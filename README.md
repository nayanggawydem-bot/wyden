print("===================================")
print("     WELCOME TO PYTHON TUTORIAL")
print("===================================")

print("\nHello! Welcome to Python Tutorial System.")
print("How can I help you today?")

while True:
    print("\nWhat chapter do you want to study?")
    print("[1] Chapter 1 - Introduction to Programming")
    print("[2] Chapter 2 - Python Basic Syntax")
    print("[3] Chapter 3 - Arithmetic Operators and Expressions")

    chapter = input("\nEnter Chapter Number: ")

    if chapter == "1":
        print("\nCHAPTER 1: INTRODUCTION TO PROGRAMMING")
        print("What lesson do you want to learn?")
        print("[1] What is Python Programming?")
        print("[2] Why Learn Python?")
        print("[3] What Do You Need to Start Python?")

        lesson = input("\nEnter Lesson Number: ")

        if lesson == "1":
            print("\nLESSON: WHAT IS PYTHON PROGRAMMING?")
            print("Python is a high-level, interpreted, and")
            print("general-purpose programming language.")
            print("It was created by Guido van Rossum in 1991.")

            print("\nEXAMPLE CODE:")
            print('print("Hello, World!")')

            print("\nOUTPUT:")
            print("Hello, World!")

        elif lesson == "2":
            print("\nLESSON: WHY LEARN PYTHON?")
            print("Python is simple and easy to learn.")
            print("It has readable syntax and is versatile.")
            print("It also has a huge community.")

            print("\nEXAMPLE CODE:")
            print('print("Python is easy to learn!")')

            print("\nOUTPUT:")
            print("Python is easy to learn!")

        elif lesson == "3":
            print("\nLESSON: WHAT DO YOU NEED TO START PYTHON?")
            print("You need Python and a code editor or IDE.")
            print("Examples are PyCharm, VS Code,")
            print("and Jupyter Notebook.")

            print("\nEXAMPLE CODE:")
            print('print("I am ready to learn Python!")')

            print("\nOUTPUT:")
            print("I am ready to learn Python!")

        else:
            print("\nInvalid lesson number!")

    elif chapter == "2":
        print("\nCHAPTER 2: PYTHON BASIC SYNTAX")
        print("What lesson do you want to learn?")
        print("[1] What is Python Syntax?")
        print("[2] Python is Case-Sensitive")
        print("[3] Indentation")

        lesson = input("\nEnter Lesson Number: ")

        if lesson == "1":
            print("\nLESSON: WHAT IS PYTHON SYNTAX?")
            print("Syntax refers to the rules used to")
            print("correctly write a Python program.")

            print("\nEXAMPLE CODE:")
            print('name = "John"')
            print("print(name)")

            print("\nOUTPUT:")
            print("John")

        elif lesson == "2":
            print("\nLESSON: PYTHON IS CASE-SENSITIVE")
            print("Python treats uppercase and lowercase")
            print("letters differently.")
            print("Name and name are not the same.")

            print("\nEXAMPLE CODE:")
            print('name = "John"')
            print("print(name)")

            print("\nOUTPUT:")
            print("John")

        elif lesson == "3":
            print("\nLESSON: INDENTATION")
            print("Indentation refers to spaces at the")
            print("beginning of a line of code.")
            print("It defines blocks of code in Python.")

            print("\nEXAMPLE CODE:")
            print("age = 18")
            print("if age >= 18:")
            print('    print("Adult")')

            print("\nOUTPUT:")
            print("Adult")

        else:
            print("\nInvalid lesson number!")

    elif chapter == "3":
        print("\nCHAPTER 3: ARITHMETIC OPERATORS")
        print("What lesson do you want to learn?")
        print("[1] What are Arithmetic Operators?")
        print("[2] Arithmetic Operators in Python")
        print("[3] Expressions in Python")
        print("[4] PEMDAS")

        lesson = input("\nEnter Lesson Number: ")

        if lesson == "1":
            print("\nLESSON: WHAT ARE ARITHMETIC OPERATORS?")
            print("Arithmetic operators are symbols used")
            print("to perform mathematical calculations.")

            print("\nEXAMPLE CODE:")
            print("print(5 + 3)")

            print("\nOUTPUT:")
            print("8")

        elif lesson == "2":
            print("\nLESSON: ARITHMETIC OPERATORS")
            print("+ Addition")
            print("- Subtraction")
            print("* Multiplication")
            print("/ Division")
            print("// Floor Division")
            print("% Modulus")
            print("** Exponentiation")

            print("\nEXAMPLE CODE:")
            print("a = 10")
            print("b = 5")
            print("print(a + b)")

            print("\nOUTPUT:")
            print("15")

        elif lesson == "3":
            print("\nLESSON: EXPRESSIONS IN PYTHON")
            print("An expression is a combination of")
            print("values, variables, and operators")
            print("that evaluates to a result.")

            print("\nEXAMPLE CODE:")
            print("a = 10")
            print("b = 5")
            print("result = a + b")
            print("print(result)")

            print("\nOUTPUT:")
            print("15")

        elif lesson == "4":
            print("\nLESSON: PEMDAS")
            print("Python follows the order of operations:")
            print("P - Parentheses")
            print("E - Exponents")
            print("M - Multiplication")
            print("D - Division")
            print("A - Addition")
            print("S - Subtraction")

            print("\nEXAMPLE CODE:")
            print("result = 2 + 3 * 4")
            print("print(result)")

            print("\nOUTPUT:")
            print("14")

        else:
            print("\nInvalid lesson number!")

    else:
        print("\nInvalid chapter number!")

    again = input("\nDo you want to study another lesson? (yes/no): ")

    if again.lower() != "yes":
        print("\nThank you for using Python Tutorial System!")
        print("Have a great day!")
        break

