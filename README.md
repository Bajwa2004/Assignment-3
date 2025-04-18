# Assignment-3
#Readme- prototype of ferry booking system
This is my python program to create basic ferry booking system. It faciliate a customer to provide personal information, select ferry services, recieve a total cost, and simulate a decision of whetehr the manager would approve. Here is an explanation coloumn by coloumn how each line of the code works.
##Explanation
customerbooking()-Take basic customer information in this function.
def customerBooking()
define function named 
python define customer booking
form_of_id= input("enter form of id(ex; passport, driver license):")
It prompts the user for type of id to be entered and stores it in the variable form_of_id
python enter id number id:number = input ()
prompt bytes number and save it in id_number
name = input ("enter name:")
Return form_of_id, id_number, id_name,ticket_name
Return all four so that they can be used later in the program.
###Function 2
ferry_service_total():
def ferry_service_total
It calls the customerbooking() function and assign its return value to individual variables.
total=0.0
print("\nenter service names and their prices (type done to finish):")
Display message, informing user to start typing in services.
###while true
this i used because for an infinite loop to continuosly ask for services.
services_name=input ("service name:")
prompts user to input ferry service name 
if service_name.lower() == "done" break
The loop continues unless the user input "done", in which case it exits the loop.
try:price =float (inpyt(input(f"price of {service_name}:$")) total+=
Adds the input price of the total cost after attempting to convert it to a number.
##except valueerror:print("invalid input. inputinvalid +("please input a price a price as a number value,")
This display an error message if the input cannot be converted to a number.
return form_of_id, id_number, name, ticket_id, total.
Finally, after the loop, it returns the customer details and the final total cost.
###function3- booking\approval()
The subsequent function inquires the manager to approve the booking and return the ouitcome.
def booking_approval():
form,idnum, name, ticket, total_cost = ferry_services_total()
Invokes ferry_services_total() and assigns return returned value.
status= "pending"
approval_ref= none
Creats a placeholderfor the approval reference number.
manager_decision = input ("do you approve this booking?(y/n)")
(yes/no): "). lower()
The manager approve the booking which is converted to lowercase.
if manager_decision == "yes":
stauts = "approved"
approval_ref = idnum {:3} = ticket [-2 :]
#update this status to "approved"
#reference number, first 3 characters of id + last two digits of ticket id.
print(f"\ntotal_cost:.2f}")
Displays the total amount in 2 decimal points.
print(f"status: {status}")
Displays the booking status
if approval_ref:
print(f"approval reference number if the bookinmg was confirmed.
### program execution
###booking_approval()
This line covers the entire program. calling the booking_approval()function. it is firing automatically for other step in sequence.
##summary
This program captures user input allows the user to add services with prices.
Joins the price togather to a total
Request manager approval.








