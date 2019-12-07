## Sample Code

Below is a sample code from the IT course I took this year.

`import math
while (True):
    while (True):
        try:
            square_feet = float(input("Enter the square footage of the area being painted: "))
            if (square_feet < 0):
                print("Negative values are not allowed.")
                continue
        except ValueError:
            print("The value you entered is invalid. Only numerical values are accepted.")
            continue
        else:
                break

    paint_gallons = (square_feet / 350)

    new_gallons =math.ceil(paint_gallons)

    print("The total amount of paint needed is,",new_gallons,"gallons")

    labor_hours = (new_gallons * 6)

    new_hours =round(labor_hours,2)

    print("The total amount of labor hours needed is,", new_hours)
    
    labor_charges = (62.25 * labor_hours)

    labor_charges = (new_hours * 62.25)

    new_charges =round(labor_charges,3)

    print("The total labor charge will be","\N{DOLLAR SIGN}", labor_charges)

    another_calculation = input("Do you want to perform another calculation? (y/n): ")
    if (another_calculation != "y"):
        break
    `
