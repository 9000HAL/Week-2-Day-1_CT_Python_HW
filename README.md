# Week-2-Day-1_CT_Python_HW
Jupyter Notebook &amp; Python Basics



EXERCISE #1

#REMEMBER TO INDENT BLOCKS!!! --->STUDY FORMATTING

# starting the loop at 1
num = 1

# keep the loop going WHILE the cube of "1" here is less than or equal <= to 1000
while num ** 3 <= 1000:

# calculate cube of current number
    cube = num ** 3

# print the cube of the current number
    print(cube)

# keep increment the number for next ongoing iteration
    num += 1



    
    EXERCISE #3

    #ask user for their age and make their answer an integer
age = int(input("Kindly enter your age: "))

# "IF" for user younger than 18 [0-17]
if age < 18:
    print("kids")

# "ELSE IF" for user age is between 18 and 65, including age 18 or 65
elif age >= 18 and age <+ 65:
    print("adults")

# "ELSE" for user is older than 65 [66+]
else:
    print("seniors")

