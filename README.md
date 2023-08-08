# Lab-2c: Monthly Interest 

## Objectives:

In this lab, you will learn how to do the following:

- Use a combination of mathematical operators
- Specify the order in which operators should be executed using ()

## Background and Formulas:

Suppose you want to make a $200 deposit into a new credit union account each month. Assume that the credit union where you deposit your money has an interest rate of 1.7%. You want to calculate the balance after three months.

 

We know that the annual interest rate is 1.7% or .017 or (1.7/100).

The monthly interest rate is then 1.7/100/12 or .001416…

If you deposit $200 each month for three months, then:

 

Your balance after one month is:

This month’s deposit * (1 + monthly interest rate) = balance after one month

200 * (1 + .001416) = 200.28

In other words:

Current balance = deposit * (1 + monthly interest rate)

 

Your balance after two months is:

(This month’s deposit + previous balance) * (1 + monthly interest rate) = balance after two months

(200 + 200.28) * (1 + .001416) = 400.57

In other words:

New balance = (deposit + current balance) * ( 1 + monthly interest rate)

or

balance = (deposit + balance) * (1 + monthly interest rate)

 

Your balance after three months is:

(This month’s deposit + previous balance) * (1 + monthly interest rate) = balance after three months

(200+400.57) * (1 + .001416) = 600.85

## Program: Monthly Interest:

Write a program which will ask the user to enter a monthly savings amount of their choice and an annual interest rate. Have the program calculate and output the account balance after 6 months.

## Key program requirements:

- The use of loops is not allowed


## Example Run:

_This program will ask the user for a monthly deposit, an annual interest rate and then calculate the balance after 6 months._

_Please enter the amount to be deposited each month:_
_100_
_Please enter the annual interest rate percent:_
_5_


## Hints:
**!!To get full credit you need your code to have the exact punctuations!!**