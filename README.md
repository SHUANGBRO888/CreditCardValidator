# CreditCardValidator
luhn algorithm 
1. Write down the credit card number:

4417 1234 5678 9113

2. Starting from the first number, double every other digit.

4(x2) 4 1(x2) 7 1(x2) 2 3(x2) 4 5(x2) 6 7(x2) 8 9(x2) 1 1(x2) 3

The doubled numbers result in: 8 2 2 6 10 14 18 2

3. If the result of the doubling ends up with a two digits, then add those two digits together:

10 = 1+0 14= 1+4 18= 1+8

4. Add up all numbers: 8+4+2+7 + 2+2+6+4 + 1+0+6+1+4+8 + 1+8+1+2+3 = 70

If the final sum is divisible by 10, then the credit card is valid. If it is not divisible by 10, the number is invalid or fake. In the above example, credit card number 4417 1234 5678 9113 has passed the Luhn test.
