# 💰 Simple Python Tip Calculator

![GitHub language count](https://img.shields.io/github/languages/count/google/python-tip-calculator?style=for-the-badge&color=blue)
![GitHub top language](https://img.shields.io/github/languages/top/google/python-tip-calculator?style=for-the-badge&color=green)

A straightforward command-line application written in **Python** that quickly calculates how much each person needs to pay when splitting a bill, including a specified tip percentage. Perfect for those moments when the check arrives!

---

## ✨ Features

* **Calculates Total Bill:** Computes the total amount including the tip.
* **Splits the Bill:** Divides the final amount evenly among a specified number of people.
* **User Input:** Prompts the user for the total bill, the desired tip percentage (10, 12, or 15), and the number of people splitting the bill.
* **Formatted Output:** Displays the final, **rounded amount** each person should contribute (to two decimal places for currency).

---

## 💻 How to Use

### Prerequisites

You need to have **Python 3** installed on your system.

### Running the Script

1.  **Save the code:** Ensure the code is saved as `task.py`.
2.  **Open your terminal** or command prompt.
3.  **Run the script** using the following command:

    ```bash
    python task.py
    ```

### Example Interaction

The script will guide you with clear prompts:


## 🔍 The Code Logic

The core calculation logic handles the math precisely:

1.  Calculates the **tip as a decimal**: `tip_as_percent = tip / 100`
2.  Determines the **total tip amount**: `total_tip_amount = bill * tip_as_percent`
3.  Finds the **total bill with tip**: `total_bill = bill + total_tip_amount`
4.  Calculates the **cost per person**: `bill_per_person = total_bill / people`
5.  Rounds the final output to two decimal places: `final_amount = round(bill_per_person, 2)`

---

## 🚀 Future Enhancements (Ideas)

* Add input validation to ensure users enter numbers.
* Allow the user to input a custom tip percentage, not just 10, 12, or 15.
* Handle errors for dividing by zero (i.e., if the user enters 0 people).
