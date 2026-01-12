Simple Interest Calculator

This project is a basic calculator that computes Simple Interest based on the given principal amount, annual rate of interest, and time period.

📌 Formula Used

\text{Simple Interest} = \frac{p \times t \times r}{100}

📥 Input
	•	p – Principal amount
	•	t – Time period (in years)
	•	r – Annual rate of interest

📤 Output
	•	Simple Interest

🧮 Example

p = 1000
t = 2
r = 5

p = 1000
t = 2
r = 5

Simple Interest = 100

p = float(input("Enter principal amount: "))
t = float(input("Enter time period in years: "))
r = float(input("Enter annual rate of interest: "))

simple_interest = (p * t * r) / 100
print("Simple Interest =", simple_interest)

