# cs61a-homework-2--higher-order-functions-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Homework 2- Higher Order Functions Solved](https://www.ankitcodinghub.com/product/cs61a-homework-2-higher-order-functions-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119645&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A  Homework 2- Higher Order Functions Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Instructions

Download hw02.zip. Inside the archive, you will find a file called hw02.py, along with a copy of the ok autograder.

Using Ok: If you have any questions about using Ok, please refer to this guide.

Readings: You might find the following references useful:

Section 1.6

Grading: Homework is graded based on correctness. Each incorrect problem will decrease the total score by one point. There is a homework recovery policy as stated in the syllabus. This homework is out of 2 points.

Required questions

Several doctests refer to these functions: “`py from operator import add, mul square = lambda x: x * x identity = lambda x: x triple = lambda x: 3 * x increment = lambda x: x + 1 “`

Getting Started Videos

YouTube link

Parsons Problems

To work on these problems, open the Parsons editor:

python3 parsons

Q1: Count Until Larger

Implement the function count_until_larger. count_until_larger takes in a positive integer num. count_until_larger counts the distance between the rightmost digit of num and the nearest greater digit; to do so, the function counts digits from right to left. Once it encounters a digit larger than the rightmost digit, it returns that count. If no such digit exists, then the function returns -1.

For example, 8117 has a rightmost digit of 7 and returns a count of 3. 9118117 also returns a count of 3: for both, the count stops at 8.

0 should be treated as having no digits and returns a count of -1.

Consult the following doctests for specific behaviors of count_until_larger.

“`py def count_until_larger(num): “”” Complete the function count_until_larger that takes in a positive integer num. count_until_larger examines the rightmost digit and counts digits from right to left until it encounters a digit larger than the rightmost digit, then returns that count.

&gt;&gt;&gt; count_until_larger(117) # .Case 1

-1

&gt;&gt;&gt; count_until_larger(8117) # .Case 2

3

&gt;&gt;&gt; count_until_larger(9118117) # .Case 3

3

&gt;&gt;&gt; count_until_larger(8777) # .Case 4

3

&gt;&gt;&gt; count_until_larger(22) # .Case 5

-1

&gt;&gt;&gt; count_until_larger(0) # .Case 6

-1

“””

“*** YOUR CODE HERE ***”

“`

Q2: Filter Sequence

Write a function filter_sequence which takes in two integers, start and stop, as well as a function cond, which takes in a single argument and outputs a boolean value. filter_sequence returns the sum of all digits from start to stop (inclusive) for which cond returns True.

“`py def filter_sequence(cond, start, stop): “”” Returns the sum of numbers from start (inclusive) to stop (inclusive) that satisfy the one-argument function cond.

&gt;&gt;&gt; filter_sequence(lambda x: x % 2 == 0, 0, 10) # .Case 1

30

&gt;&gt;&gt; filter_sequence(lambda x: x % 2 == 1, 0, 10) # .Case 2

25

“””

“*** YOUR CODE HERE ***”

“`

Code Writing Questions

Q3: Hailstone

Douglas Hofstadter’s Pulitzer-prize-winning book, GÃ¶del, Escher, Bach, poses the following mathematical puzzle.

1. Pick a positive integer n as the start.

2. If n is even, divide it by 2.

3. If n is odd, multiply it by 3 and add 1.

4. Continue this process until n is 1.

The number n will travel up and down but eventually end at 1 (at least for all numbers that have ever been tried — nobody has ever proved that the sequence will terminate). Analogously, a hailstone travels up and down in the atmosphere before eventually landing on earth.

This sequence of values of n is often called a Hailstone sequence. Write a function that takes a single argument with formal parameter name n, prints out the hailstone sequence starting at n, and returns the number of steps in the sequence:

“`py def hailstone(n): “””Print the hailstone sequence starting at n and return its length.

&gt;&gt;&gt; a = hailstone(10)

10

5

16

8

4

2

1

&gt;&gt;&gt; a

7

&gt;&gt;&gt; b = hailstone(1)

1

&gt;&gt;&gt; b

1

“””

“*** YOUR CODE HERE ***”

“`

Hailstone sequences can get quite long! Try 27. What’s the longest you can find?

Note that if n == 1 initially, then the sequence is one step long.

Use Ok to test your code:

python3 ok -q hailstone

Curious about hailstones or hailstone sequences? Take a look at these articles:

Check out this article to learn more about how hailstones work!

Q4: Product

“`py def product(n, term): “””Return the product of the first n terms in a sequence.

n: a positive integer term: a function that takes one argument to produce the term

&gt;&gt;&gt; product(3, identity) # 1 * 2 * 3

6

&gt;&gt;&gt; product(5, identity) # 1 * 2 * 3 * 4 * 5

120

&gt;&gt;&gt; product(3, square) # 1^2 * 2^2 * 3^2

36

&gt;&gt;&gt; product(5, square) # 1^2 * 2^2 * 3^2 * 4^2 * 5^2

14400

&gt;&gt;&gt; product(3, increment) # (1+1) * (2+1) * (3+1)

24

&gt;&gt;&gt; product(3, triple) # 1*3 * 2*3 * 3*3 162

“””

“*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q product

Q5: Accumulate

Let’s take a look at how summation and product are instances of a more general function called accumulate, which we would like to implement:

“`py def accumulate(merger, start, n, term): “””Return the result of merging the first n terms in a sequence and start. The terms to be merged are term(1), term(2), …, term(n). merger is a two-argument commutative function.

&gt;&gt;&gt; accumulate(add, 0, 5, identity) # 0 + 1 + 2 + 3 + 4 + 5 15

&gt;&gt;&gt; accumulate(add, 11, 5, identity) # 11 + 1 + 2 + 3 + 4 + 5 26

&gt;&gt;&gt; accumulate(add, 11, 0, identity) # 11

11

&gt;&gt;&gt; accumulate(add, 11, 3, square) # 11 + 1^2 + 2^2 + 3^2 25

&gt;&gt;&gt; accumulate(mul, 2, 3, square) # 2 * 1^2 * 2^2 * 3^2 72

&gt;&gt;&gt; # 2 + (1^2 + 1) + (2^2 + 1) + (3^2 + 1)

&gt;&gt;&gt; accumulate(lambda x, y: x + y + 1, 2, 3, square)

19

&gt;&gt;&gt; # ((2 * 1^2 * 2) * 2^2 * 2) * 3^2 * 2

&gt;&gt;&gt; accumulate(lambda x, y: 2 * x * y, 2, 3, square)

576

&gt;&gt;&gt; accumulate(lambda x, y: (x + y) % 17, 19, 20, square)

16

“””

“*** YOUR CODE HERE ***”

“` accumulate has the following parameters:

term and n: the same parameters as in summation and product merger: a two-argument function that specifies how the current term is merged with the previously accumulated terms. start: value at which to start the accumulation.

For example, the result of accumulate(add, 11, 3, square) is

11 + square(1) + square(2) + square(3) = 25

After implementing accumulate, show how summation and product can both be defined as function calls to accumulate.

Important: You should have a single line of code (which should be a return statement) in each of your implementations for summation_using_accumulate and product_using_accumulate, which the syntax check will check for.

Use Ok to test your code: python3 ok -q accumulate python3 ok -q summation_using_accumulate python3 ok -q product_using_accumulate

Submit

Make sure to submit this assignment by running:

python3 ok –submit

Bonus Questions

Homework assignments will also contain prior exam-level questions for you to take a look at. These questions have no submission component; feel free to attempt them if you’d like a challenge!
