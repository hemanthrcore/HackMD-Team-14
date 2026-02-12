# HackMD-Team-14

**Python Programming Tasks:**
Case Study Title:Fuel cost calculation

USN:24BCAR0485

Name:Rafsha Jabin SM
     
Algorithm: 

STEP 1: Start
STEP 2: Read the value of price
STEP 3: Read the value of litres 
STEP 4: Calculate cost = litres* price
STEP 5: Display the value of cost
STEP 6: Stop

Code:

price_pe=float(input("Enter the price per litre:"))
litres=float(input("Enter the number of litres:"))

cost=litres * price

print("The total cost is:",cost)

Output:
Enter the price per litre:104
Enter the number of litres:4
The total cost is: 416.0

     **Python Programming Tasks:**
Case Study Title:Bonus eligibility based on salary

USN:24BCAR0505

Name:Shwetha kumari

Algorithm:
STEP 1: Start
STEP 2: Read the salary from the user
STEP 3: Check if salary is greater than or equal to 90000
 If yes, then display “You are eligible for bonus”
 If no, then display “You are not eligible for bonus”
STEP 4: Stop 

CODE:

salary = int(input("Enter your salary: "))

if salary >= 90000:
    print("You are eligible for bonus")
else:
    print("You are not eligible for bonus")
    
    
OUTPUT:
 Enter your salary: 70000
You are not eligible for bonus

Enter your salary: 100000
You are eligible for bonus
    
    
    **Python Programming Tasks:**
Case Study Title:Countdown timer using loop 

USN:24BCAR0483

Name:R Hemanth 

Algorithm:

STEP 1: Start 

STEP 2: Input numbers or seconds from user 

STEP 3: While seconds is greater than 0, repeat

STEP 4: Display the current value of seconds

STEP 5: Create a delay using another loop

Decrease seconds by 1 (-1)

When seconds becomes 0, 

STEP 6: display Time's up!

STEP 7: stop


Code:

seconds = int(input("Enter time in seconds : "))

while seconds > 0:
    print(" Time left :", seconds , " seconds")
    i = 0
    while i < 10000000 :
        i += 1
    seconds -= 1

print("Time's up!!!!!!! ")



OUTPUT:
Enter time in seconds : 5
Time left : 5 seconds
Time left : 4 seconds
Time left : 3 seconds
Time left : 2 seconds
Time left : 1 seconds
Time's up!!!!!!!


    
    
    
        **Python Programming Tasks:**
Case Study Title:Bonus Calculation functions

USN:24BCAR0488

Name: Arpit Arjun Ray

STEP 1:  Start

STEP 2: Set salary = 50000

STEP 3: Set bonus = 5000

STEP 4: Calculate total_salary = salary + bonus

STEP 5: Display salary

STEP 6: Display bonus

STEP 7: Display total_salary

STEP 8: Stop


Code:
salary = 50000
bonus = 5000

total_salary = salary + bonus

 print("Salary : ", salary  )
print("Bonus : ", bonus)
 print(" Total Salary : ", total_salary )

OUTPUT:
Salary :  50000
Bonus :  5000
 Total Salary :  55000
