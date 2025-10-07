📘 Project Description

This project is a Python-based Financial Calculator that helps users compute:

Loan Amortization Schedule — Calculates monthly payments, interest, and remaining balance for a given loan.

Investment Growth — Calculates the future value of an investment based on compounding interest.

It’s a simple yet powerful console-based tool for students, finance learners, and developers to understand the concept of amortization and compound interest.

⚙️ Features

✅ Calculate monthly loan payments.
✅ Display full amortization schedule month-by-month.
✅ Compute future value of investments with customizable compounding frequency.
✅ Interactive CLI menu for easy navigation.

🧩 Requirements

Before running this project, ensure you have the following installed:

Python 3.7 or higher

No external libraries required (uses only built-in modules like math)

🧰 Installation
1️⃣ Clone the repository
git clone https://github.com/your-username/loan-amortization.git

2️⃣ Navigate to the project folder
cd loan-amortization

3️⃣ Run the program
python main.py

🚀 How It Works

When you run the program, you’ll see a menu like this:

--- Financial Calculator ---
1. Loan Amortization
2. Investment Growth
3. Exit


If you choose Loan Amortization:

Enter your loan amount, annual interest rate, and loan term in years.

The program calculates:

Monthly payment

Principal and interest for each month

Remaining balance after each payment

If you choose Investment Growth:

Enter initial investment, annual interest rate, investment period, and compounding frequency.

The program outputs the future value of your investment.

📊 Sample Output
--- Loan Amortization Calculator ---

Monthly Payment: Rs.8.65

Amortization Schedule:
Month   1: Payment: Rs.8.65, Principal: Rs.8.07, Interest: Rs.0.58, Balance: Rs.91.93
Month   2: Payment: Rs.8.65, Principal: Rs.8.12, Interest: Rs.0.54, Balance: Rs.83.81
...
Month  12: Payment: Rs.8.65, Principal: Rs.8.60, Interest: Rs.0.05, Balance: Rs.0.00

🧠 Working Logic

Loan Amortization:

Converts annual interest to monthly rate.

Calculates total number of payments.

Uses amortization formula:

M = P * [r(1 + r)^n] / [(1 + r)^n – 1]


Where:

M = Monthly Payment

P = Principal

r = Monthly Interest Rate

n = Total Months

Investment Growth:

Uses compound interest formula:

FV = P * (1 + r/n)^(n*t)


Where:

FV = Future Value

P = Principal

r = Annual Interest Rate

n = Compounding Frequency per Year

t = Time (Years)

📁 File Structure
loan-amortization/
│
├── main.py            # Main program file
├── README.md          # Project documentation
