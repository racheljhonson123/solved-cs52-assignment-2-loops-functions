Download Link: https://assignmentchef.com/product/solved-cs52-assignment-2-loops-functions
<br>
<h1></h1>




Write a program that prints out a simulated candle of the entered size. The program prompts the user for two positive int numbers where the first number represents the candle and the second number represents the wick.

Create a function that expects two parameters: one parameter called candleSize defines the size of the candle, and the second parameter called wickSize defines the size of the wick. The method then draws a candle with wick of the specified sizes.

Example:          Candle size:  <strong>8</strong>

Wick size:     <strong>2</strong>

Output:  ========–

Problem 2                                           Triangle

<strong> </strong>

Write a program that prints a triangle of *. The program prompts the user to input a size and then prints out a triangle of that size. Create a function that expects the size parameter and prints out the triangle.

Example:         Enter size: <strong>4</strong> Triangle:

*

**

***

****

<h1>Problem 3                                           Sum and Average</h1>




Write a program that calculates the average of numbers inputted by a user. The program keeps prompting a user to input a number until -1 is entered. When -1 is entered the program prints out the sum and the average of all numbers that where entered excluding -1. Round the average to two fractional digits. Introduce one function that prompts the user for input and returns a whole number inputted by the user. The functions re-prompts the user if less than -1 is entered and only returns when a valid number was entered (x &gt;= -1). Introduce a second function that prints out the average and sum. Call both functions from the main.

Example:          Number:  <strong>4</strong>

Number: <strong>-7</strong>

Invalid! Re-enter: <strong>7</strong>

<table width="586">

 <tbody>

  <tr>

   <td width="96"> </td>

   <td width="336">Number:  <strong>3</strong>Number:  <strong>-1</strong>Sum:      14Average: 4.67</td>

   <td width="48"> </td>

   <td width="48"> </td>

   <td width="58"> </td>

  </tr>

  <tr>

   <td width="96"><strong>Problem 4</strong></td>

   <td width="336">                                    <strong>Fibonacci Numbers  </strong></td>

   <td width="48"><strong> </strong></td>

   <td width="48"><strong> </strong></td>

   <td width="58"><strong>8 points</strong></td>

  </tr>

 </tbody>

</table>




Fibonacci numbers are a sequence of numbers where each number is represented by the sum of the two preceding numbers, starting with 0 and 1: 0, 1, 1, 2, 3, 5, 8, etc.

Write a program that repeatedly prompts the user for a positive integer and prints out whether or not that integer is a Fibonacci number. The program terminates when -1 is entered.

Create a method with the following signature. The method tests whether the number passed to it is a Fibonacci number or not. It returns <em>true</em> if the number is indeed a Fibonacci number and it returns <em>false</em> otherwise.

<em>bool isFibonacci(int number)  </em>

Example:         Input: <strong>21</strong>

Output: 21 is a Fibonacci number




Input: <strong>9</strong>

Output: 9 is not a Fibonacci number

Input: <strong>-1</strong> Goodbye!