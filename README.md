💰 Simple Python Tip Calculator
This is a straightforward command-line application written in Python that calculates how much each person needs to pay when splitting a bill, including a specified tip percentage.

✨ Features
Calculates Total Bill: Computes the total amount including the tip.

Splits the Bill: Divides the final amount evenly among a specified number of people.

User Input: Prompts the user for the total bill, the desired tip percentage, and the number of people splitting the bill.

Formatted Output: Displays the final, rounded amount each person should contribute.

💻 How to Use
Prerequisites
You need to have Python 3 installed on your system.

Running the Script
Save the code: Ensure the code is saved as task.py.

Open your terminal/command prompt.

Run the script using the following command:

Bash

python task.py
Example Interaction
The script will guide you through the process by asking for input:

welcome to the tip calculator!
what was the total bill? $150.55
What tip would you like to give? 10 12 15 12
How many people to split the bill? 4
Each person should pay: $42.15
🧠 The Code
The core calculation logic is as follows:

Get the bill, tip percentage, and number of people as input.

Calculate the tip amount: total_tip_amount = bill * (tip / 100)

Calculate the total bill: total_bill = bill + total_tip_amount

Calculate the amount per person: bill_per_person = total_bill / people

Round the final amount to two decimal places for currency: final_amount = round(bill_per_person, 2)
