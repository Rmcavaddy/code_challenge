# code_challenge
Code challenge for CIS105 10/09/23 
#input for monthly expenses
rent = float(input('How much do you spend on rent per month?: '))
electric = float(input('How much do you spend on electric per month?: '))
water = float(input('How much do you spend on water per month?: '))
internet = float(input('How much do you spend on internet per month?: '))
PE = float(input('How much do you spend on personal expenses per month?: '))
groceries = float(input('How much do you spend on groceries per month?: '))
gas = float(input('How much do you spend on gas per month?: '))
#calculation of expenses
monthly_total = rent + electric + water + internet + PE + groceries + gas
#output of calculation
print('The total of your Monthly Expenses is: ', monthly_total)
