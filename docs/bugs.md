# simple_calculator bugs

**bugs.md** is used to track and record bugs and issues related to the latest released version.


## v0.1.0

Release Date : 04 Feb 25 <br/>
GitHub Branch : [v0.1.0](https://github.com/pranavdharkar/simple_calculator/tree/v0.1.0)

### .exe
+ simpleCalculator.exe file closes after entering the input (Can't able to read the result).

### code 
+ Change the name of the fuctions:
    + `isNum1Valid()`       to  `get_valid_num1()`
    + `isNum2Valid()`       to  `get_valid_num2()`
    + `isOpValid()`         to  `get_valid_op()`
    + `isCalculationCon()`  to  `get_valid_yn_to_continue()`