# Poly-Ai_Assement

### General Instructions:
#### Take care to follow these instructions, to allow us to process your submission promptly.

1. We prefer that you write your submission in Python 3.
2. The program must be a stand-alone command-line program/script.
3. All input must come from standard input, and there should be no text in the
standard output apart from the solution to the problem.
In this example, the input is over two lines, the output is the value “1”.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`prompt> python3 solution.py` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`[input line 1]` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`[input line 2]` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`1` <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You can use the “<” command line syntax to load from a file to stdin.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`prompt> python3 solution.py < input.txt` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`1` <br>

4) Please submit your submission in the following structure:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`firstname_lastname/` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`[problem_name]_report.txt` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`[problem_name]_solution.py`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In `*_report.txt:` put the thoughts and analysis of your solution. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In `*_solution.py:` put your code. <br>

5. Zip the folder as `firstname_lastname.zip` and submit it via email. Send the
solutions for multiple problems in a single Zip file, taking care to spell the
`problem_name` correctly.

<hr />

### Question (Pizzeria)
After a long deferment, the mayor of Z-city has allowed pizzerias to be opened in town. Pizzerias used to be unlawful
because of health reasons (according to the mayor). The city is big, and suddenly there are pizzerias everywhere.  <br>
We can imagine the city like a matrix with **NxN** squares, where every square represents one block of the city. Every pizzeria
only delivers pizza to the nearby blocks. Specifically, every pizzeria delivers pizza to every block that is at most R blocks
away from block the pizzeria's location. Distance is determined by the minimum number of blocks that the delivery guy must
take if he is going East/West or North/South (moving diagonally is forbidden in Z-city). For example, let's say that N=5 and a
pizzeria is located at the block (3, 3). It can deliver to a 2 block distance at most. The following map shows where the given
pizzeria delivers pizzas.
````
00X00
0XXX0
XXXXX
0XXX0
00X00
````
Mr. Little Z loves pizza, so he wants to move to the block where he can have the greatest selection of pizzas (the block that
has the maximum number of pizzerias delivering to it).<br>

Help Mr. Little Z find that maximum. In other words, if he moves to the block with the greatest selection of pizzas, how many
pizzerias will be able to deliver to his block?<br>

**INPUT:**
The first line of the standard input contains the two numbers **N** and **M**, and both numbers are on the interval [1, 10000]. The
number **N** represents the dimension of the city in blocks (the city has **NxN** blocks). **M** is the number of pizzerias in the city.
The following **M** lines contain information about each pizzeria, given by the three numbers **X, Y, R**. The numbers **X** and **Y**
represent the block where the pizzeria is located, (1 <= **X, Y** <= **N**) and the number **R** represents the maximum distance that
the given pizzeria's delivery guy will travel to deliver pizza (1 <= **R** <= 5,000). <br>

**OUTPUT:**
Write one number to the standard output that represents the number of pizzerias that deliver pizzas to the block with the
greatest selection of pizzas.
Input (stdin):
````
5 2
3 3 2
1 1 2
````
Output (stdout):
**2**


1. Write down your brief thoughts on how you approached this problem.
3. What is the complexity of your solution? Can it be improved?

