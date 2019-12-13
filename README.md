## Welcome to the Page!

#### This page is to serve as a site to tell you a little about myself!

###### 

<button type="button">About Me!</button> 
<button type="button">Future Plans</button>
<button type="button">Sample Code</button>

![A picture of me!](mypic.HEIC)

## A little about myself!

My name is William Bennett! I am currently a first year freshmen at Mizzou! 
I am enjoying my time so far in college and am trying a lot of new things! The first week of the semester I changed my major to Information Technology from Biology/Pre-Med major. It is a lot to take in but I think in the long run it will be a great choice for me.

Some of my hobbies are: 
1. playing volleyball 
2. video games. 
3. I am currently the manager of the Mizzou Women's Volleyball team. 
4. I work for Culinary Performance Services for *Mizzou Football* as well.

![Mizzou](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.themizzoustore.com%2Fimages%2Fproduct%2Flarge%2F70887.jpg&imgrefurl=https%3A%2F%2Fwww.themizzoustore.com%2Fp-70887-mizzou-tiger-head-decal.aspx&docid=KtM0BssOo4B3WM&tbnid=Xg7lWa2pyMTfOM%3A&vet=10ahUKEwie_NWIqqLmAhUYip4KHTbaBAEQMwh8KAIwAg..i&w=500&h=500&bih=733&biw=720&q=mizzou&ved=0ahUKEwie_NWIqqLmAhUYip4KHTbaBAEQMwh8KAIwAg&iact=mrc&uact=8)

### Future Plans of Mine

I currently want to do something with Information Systems Management but seeing as that it is only my first semester here I am still open to change. Who knows, I might find something completely different that I will like. 

To be completely honest I have no idea what the future holds for me or what exactly I want to do with my degree. 

I would like to move out to the **west coast**

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
    
    
