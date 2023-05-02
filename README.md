Download Link: https://assignmentchef.com/product/solved-comp-6651-programming-assignment-1
<br>
<h2>1      Problem</h2>

A string is called a repeat-once string if we can obtain it by concatenating two copies of the same string. For example, <em>xxyxxy </em>and <em>xx </em>are repeat-once strings, while <em>xxx </em>and <em>xyyx </em>are not. Given a string, calculate the number of non-empty subsequences of the string such that they are repeat-once strings. For example, given the string <em>xxx </em>it has three subsequences that are repeat-once strings, each of them is <em>xx </em>(the first and second <em>x </em>from <em>xxx</em>, the second and third <em>x</em>, and the first and third <em>x</em>).

<h2>2      Input</h2>

The first line of the input is an integer <em>T</em>, which is the number of test cases. The next <em>T </em>lines contain test cases, each of which contains a string. You can assume that 1 ≤ <em>T </em>≤ 200 and that each string in the test case is of length at most 200, and consists only of lower-case letters (<em>a</em>−<em>z</em>).

<h2>3      Output</h2>

For each test case, list the number of repeat-once subsequences on a separate line. The output should therefore have <em>T </em>different lines.

<h2>4      Example</h2>

Sample Input

Sample Output

1

3

12

Explanation

For the first test case, there is only one repeat-once subsequence, namely <em>aa</em>. For the second, there are 3 identical repeat-once subsequences <em>xx</em>. For the last test case, there are the following repeat-once subsequences: <em>aa </em>(3), <em>bb </em>(3), <em>ab </em>(5), and <em>ba</em>(1)

<h2>5      Requirements</h2>

For the constraints given above, your program should run in 3 seconds. You must submit source code for a program written in C/C++/Java on the Electronic Assignment System. Some test cases will be provided on the course website. You can verify if your program works on the test cases before submitting.

<h2>6       Programmer-on-duty</h2>

There will be a programmer-on-duty, Tejas Puranik, available to help you with the assignment on Wednesdays 6pm to 9pm in H841.