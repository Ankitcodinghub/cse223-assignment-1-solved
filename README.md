# cse223-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE223  Assignment 1 Solved](https://www.ankitcodinghub.com/product/cse223-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95914&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE223&nbsp; Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

This assignment is more complex that Programming Assignment A, but if you work methodically and ask questions along the way, it is not extremely di􏰅cult. The biggest challenge here is getting a better understanding of the mechanics of classes and objects, methods, and more generally, learning about object oriented programming and developing an OO mindset.

This won’t happen in a day: it will take multiple coding sessions for your brain to settle into this way of thinking. Start early! Starting the project a day or two before it’s due won’t su􏰅ce, and you’ll su􏰃er the reminder of the class if you do so.

Do not use Eclipse, IntelliJ, or any other IDEs: work from the command line on the linux server (or your own linux environment). This will ensure you know the syntax for de􏰄ning classes, writing a main method, and so on. We’ll get to IDEs later, but for now, you must work from the command line only (vi etc. to edit; javac to compile; java to run).

2 Description

For assignment 1, you are going to implement a new Java class for processing even integers. Even integers work exactly like regular integers, except they are all even! Addition, subtraction and multiplication of even numbers works as usual. Division might normally result in an odd number: if the result of division is odd, add 1 to make the result even.

3 Details

Your class must be named Even.

Constructor

Provide a single constructor: Even x=new Even(2);

for example would construct the even number 2. You will need a single class variable (call it whatever you like) to store the (int) value of your Even object.

If the constructor is called with an odd number, add 1 to make it even and the construct using that even number.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Main Methods (manipulate Evens)

You must also provide the following methods (assume x and y are both objects of type Even):

<pre>x.add(y); // creates a new Even whose value is x+y
x.sub(y); // creates a new Even whose value is x-y
x.mul(y); // creates a new Even whose value is x*y
x.div(y); // creates a new Even whose value is x/y. If x/y is odd, add 1 to it
</pre>
<pre>    x.toInt(); // return the value of the even number as a plain int
</pre>
toString

You should also write a toString method for returning a String representation of the number. The string should consist of words separated by spaces, with one word for each digit of the number (

<pre>    x.toString();
</pre>
To do this, consider turning your (int) value into a string (by concatenating to an empty string 􏰁􏰂); using the charAt() method (from String) to read each digit one at a time (inside a loop); and using a switch statement (or a series of ifs) to append the appropriate word to a result string.

Your string should consist of the following words (separated by spaces): ‘-‘ negative

‘0’ zero

‘1’ one

‘2’ two

‘3’ three

‘4’ four

‘5’ 􏰄ve

‘6’ six

‘7’ seven

‘8’ eight

‘9’ nine

Remember: do not print anything from the toString method; just return a string.

4 Testing

The following sample main program might be used to test your Even class. Note that you should thoroughly test your class with your own test code. This is only an example:

<pre>// Sample test code for CSE 223 PA1 Spring 2020
// Nick Macias, April 2020
// Construct some Even objects and test the methods
// Also do some string concatenation to exercise toString
</pre>
<pre>class Main{
// just need a (standard) main method to run some tests
</pre>
<pre>  public static void main(String[] args) // no arguments processed
  {
</pre>
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<pre>Even a,b,c,d;
a=new Even(-10);
b=new Even(15);
c=a.add(b);
d=b.div(a);
</pre>
</div>
<div class="column">
<pre>// some Even objects to play with
// -10
// should round up to 16
// expecting result of 6
</pre>
<pre>// 16/(-10) would be -1.6 which, as an int, is -1
// this should round up to 0, so d should be 0
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// we'll print these out using the toString method
    System.out.println("a="+a+" b="+b+" c="+c+" d="+d); // e.g. a=negative one zero
    c=new Even(2);     // c is a running product
    d=new Even(2);     // d is our multiplier
    for (int i=2;i&lt;12;i++){
</pre>
<pre>      c=c.mul(d);      // keep doubling c
</pre>
<pre>      System.out.println("2^"+i+"="+c); // and print it out in words
    }
</pre>
} }

Corresponding Output

<pre>a=negative one zero b=one six c=six d=zero
2^2=four
2^3=eight
2^4=one six
</pre>
<pre>2^5=three two
2^6=six four
2^7=one two eight
2^8=two five six
2^9=five one two
2^10=one zero two four
2^11=two zero four eight
</pre>
5 Grading

Your assignment must be downloadable from GITLab by me in order to be graded. I will download using the command:

<pre>git clone git@gitlab.com:yourGITid/CSE223PA1.git
</pre>
You can mimic this yourself to con􏰄rm that your repository is located and named correctly. There’s no sure way to check that you have added me as a reporter: just make sure you do!

Points are awarded as follows:

• Class de􏰄ned properly; Even.java compiles and creates Even.class; Constructor written: 25 points

• add, sub, mul, div and toInt methods all de􏰄ned: 25 points 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
• add, sub, mul, div, toInt all work perfectly: 15 points • toString implemented and works well: 15 points

• style: 20 points if you have all of the following:

<ul>
<li>􏰆 &nbsp;consistent indenting, placement of braces, etc.</li>
<li>􏰆 &nbsp;all code commented (every line unless it’s extremely obvious why that line is there)</li>
<li>􏰆 &nbsp;each method described by an introductory block of comments. Not just 􏰁div method􏰂 but 􏰁div method: accept an Even argument and divide current object’s value by argument’s value. If the result is odd, add 1. Return a newly-constructed Even object with the resulting value. No special handling for division by 0 (may throw an exception). 􏰂</li>
<li>􏰆 &nbsp;entire class described by a block of comments in the beginning. Not just 􏰁Even class􏰂 or 􏰁PA1 Myname􏰂 but all relevant information about the class, in your own words.</li>
</ul>
</div>
</div>
</div>
