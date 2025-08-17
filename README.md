# Step4_Word_Code

1.	If current time is 12:00am
a.	Create new text edit file for log history
b.	Log every action and outcome in text edit file until new day
2.	Get current time from real-time 24-hour clock
3.	If current time is 8:00am or 18:00pm
a.	Rotate motor to dispense food
Else: Go back to Step 1
a.	Check if bowl weight has increased
If Yes:
a.	Record the bowl weight
b.	Check if bowl weight matches desired weight limit
If Yes: Feeding successful
If No: Send error notification to app
If No:
a.	Start real-time clock timer of 10 minutes
b.	Wait until 10 minutes has elapsed
c.	After 10 minutes, check bowl weight
If bowl weight has increased
a.	Check if bowl weight matches desired weight limit
If Yes: Feeding successful
Else: Send error notification to app
4.	If current time is 11:59pm
a.	Save log history text edit file 
b.	Name according to the current date
c.	Store file in logs folder
Loop

