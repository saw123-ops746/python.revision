# python.revision
python.pratice
def arithmetic_operations():
    
    a = int(input("Enter first integer:"))
    b = int(input("Enter second integer:"))
    print("Addition:", a+b)
    print(("Subtraction:", a-b))
    print("multiplicaton:", a*b)
    print("division:", a/b if b != 0 else "cannot divide by zero.")


    print("please enter  valid integrs.")
arithmetic_operations() 


# Boolean and  Logical Operations
def boolean_condition():
    a = int(input("Enter frist number:"))
    b = int(input("Enter a second number:"))
    print("Both values are  greater than 50>:", a>50 and b>50)
    print("At least one value is even:", a %2 == 0 or b%2 == 0 )
    print("both vallues divisible by 5:", a % 5 == 0  and b  % 5 == 0)

    boolean_condition()

    # age Categorization 
    age = int(input("Enter age:"))

    if age < 18:
        print("minor")
    elif 18 <= age <= 59:
        print("Adults")
    else:
        print("Senior Citizen")

     # statistical Measures

    import statistics
    def statistics_program():
        scores = []
        for i in range(5):
            score  = float(input(f"Enter your  score for subjects {i+1}:"))
            scores.append(score)
            print("Maximum score:", max(scores))
            print("Minmum score:", min(scores))
            print("mean:", statistics.mean(scores))
            print("standard Devitiaon:", statistics.stdev(scores))

            statistics_program()


# grade and pass/fail stauts

def grading_program():
    marks = {}
    for i in range(3):
        marks = float(input(f"Enter marks for subject  {i+1}:"))
        
        total = sum (marks)
        
