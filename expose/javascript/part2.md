1. Line 12 will prints prices.length because it's the last i before exiting the loop above as it's not < prices.length. It's accesible because its declared by 'var'.
2. Line 13 will prints the discounted price for the last price given in the orignal price array. Because its varible holds the last discounted price before finishing all prices and exiting the loop. It's accesible because its declared by 'var'.
3. Line 14 will prints the rounded last discounted price to the 100th, because it's assigned to discounted price that is rounded to intiger after times 100 before divided by 100. This make rounding to 100th place. It's accesible because its declared by 'var'.
4. The function will returns an array that stores the final 100th place rounded discounted price. Because the varible discounted is assigned to an empty array at line 3, before pushed in at line 9 each rounded discounted price in a loop that loop through the provided list of original price times the (1-discount rate). It's accesible because its declared by 'var'.
5. Line 12 returns an error 'ReferenceError ReferenceError: i is not defined' because varible 'i' is declared by 'let' in line 6 for loop, which is not in the same block environment as line 12, therefore not accesible in line 12.
6. Line 13 returns an error 'ReferenceError ReferenceError: discountedPrice is not defined' because varible 'discountedPrice' is declared by 'let' in line 19 for loop, which is not in the same block environment as line 13, therefore not accesible in line 13.
7. Line 14 will prints the rounded last discounted price to the 100th, because varible 'finalPrice' although declared by 'let' in line 4, is in the same block enviroment as line 14, therefore accesible.
8. The function will returns an array that stores the final 100th place rounded discounted price. Because the varible discounted although is declared by 'let' to an empty array at line 3, is in the same block enviroment as line 16 return, therefore accesible.
9. Line 11 returns an error 'ReferenceError ReferenceError: i is not defined' because varible 'i' is declared by 'let' in line 6 for loop, which is not in the same block environment as line 11, therefore not accesible in line 11.
10. Line 12 returns the length of argument 'prices' because varble 'length' is assigned  'prices.length' at line 4. It is accessible because it's in the same block enviornment as it is declared. No error is reported because the const varible is not assigned nother value.
11. The function will returns an array that stores the discounted price. Although the varible discounted although is declared by 'const' to an empty array at line 3, is in the same block enviroment as line 16 return, therefore accesible. Although the content change, the assignment varible "pointer" does not change.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting();
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' Because '3' is a string, which makes the 2 type converted to string '2', which is concanited to the string '2' through the '+' operator. Therefore it outputs string '32'.
    B. 1 Because for '-' operator, '3' is converted to 3, which is - 2 = 1
    C. 3 Because null is converted to 0
    D. '3null' Because first '3' is a string, therefore null is converted to string 'null'
    E. 4 Because true is converted to 1
    F. 0 Because both false and null are converted to 0
    G. '3undefined' because undefined is converted to string 'undefined' before the first argument '3' is a string
    H. NaN Because for '-' operator, both '3' is converted to 3, and undefined is converted to NaN. And the calcualtor results in NaN.
14. A. True Because '2' is converted to 2 which is > 1
    B. False Because both are string, it's comparing the position of the first char in ACEII table, which '2' is larger than '1'
    C. True Because second '2' is converted to 2 and it's the same
    D. False Because === operator is strict comparision which does not do auto type conversion and the two arguments are not the same.
    E. False Because true is converted to 1 and != 2
    F. True Because even with strict comparision, 2 is manuely converted to true boolean, therefore strict equal holds.
15. '==' ignores the datatype and do auto type conversion before comparision. '===' is strict conversion that does not do auto type conversion and cares about datatype
17. It will return a new array, which is modified according to the function passed in as second argument. In this case, that function returns a number times 2, therefore the modifyArray function return a new array [2,4,6].
19. 1,4,3 followed by 2. Because 1 4 is printed ignoring anything that's inside setTimeOut function which is set to another thread. Then 3 is printed because the timeout is 0, followed by 2 after 1 second.
20. 