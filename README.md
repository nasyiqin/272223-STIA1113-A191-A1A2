# Student Info 

- Matric: 272223
- Name : Nurul Asyiqin Mohd Nawi

# Introduction
In this assignment, Monthly Repayment (RM) will be calculated after user entering input of Car Price (RM), Down Payment (RM), Loan Periods (Years) and Interest Rate (%). Loop will happened when the input that was entered is not satisfying the condition. Later, the program will display the output which is the Monthly Repayment (RM). Next, balance and principle will be calculated based on years which loop happened. 

# Pseudocode

Start
	Display “Enter Car Price (RM): ”
	Input car price
	Loop if input car price is 0 or negative and car price is not less than 30000
	Display “Enter Down Payment (RM): ”
	Input down payment
	Loop if input down payment is less than 0
Display “Enter Loan Period (Years): ”
Input loan period
Loop if input loan period is 0 or negative and in the range between 5 to 9 years
	Display “Enter Interest Rate (%): ”
	Input interest rate 
Loop if input interest rate is 0 or negative and in range between 3% to 7%
	Calculate monthly repayment = (car price – down payment) * (interest rate / 100) * loan period
	Display monthly repayment
	Loop when I not more than loan period
	Years = i+1
	Calculate principle = monthly repayment * 12 * years
	Calculate balance = (month repayment * loan period * 12) – principle
	Display years, principle, balance
End

# Flowchart
![Flowchart 1](https://user-images.githubusercontent.com/55252513/68547493-1caec580-041d-11ea-837b-9b738822e585.PNG)
![Flowchart 2](https://user-images.githubusercontent.com/55252513/68547558-e6be1100-041d-11ea-859b-7140918cca43.PNG)

# Output
![output](https://user-images.githubusercontent.com/55252513/68547451-baee5b80-041c-11ea-8aa8-8e6b08605f34.PNG)
