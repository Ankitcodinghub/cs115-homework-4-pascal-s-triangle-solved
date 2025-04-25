# cs115-homework-4-pascal-s-triangle-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs-115-hw-4-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128255&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS115 Homework 4-Pascal’s Triangle Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Pascal’s Triangle was developed by a French mathematician named Blaise Pascal. The rows are numbered starting with 0 and go all the way to n, just like list indices in Python. The triangle always starts with a single term in the 0th row, which is a [1]. The nth row of the triangle has n+1 terms, and each term is found by adding the values of the two terms above it. For example, row number 2 (actually the third row) has three terms: [1, 2, 1]. The row above it, row number 1, is [1, 1], and the row above that one, row 0, is just [1]. Pascal’s Triangle has several uses in mathematics, such as binomial expansions. (http://en.wikipedia.org/wiki/Pascal%27s_triangle contains more information.) See how the terms are obtained in the figure below.

Task 1:

Here are some examples of calling the pascal_row function:

&gt;&gt;&gt; pascal_row(0) [1]

&gt;&gt;&gt; pascal_row(1) [1, 1]

&gt;&gt;&gt; pascal_row(5)

[1, 5, 10, 10, 5, 1]

CS 115 – Hw 4

Task 2:

Write a second function called pascal_triangle that takes as input a single integer n and returns a list of lists containing the values of the all the rows up to and including row n.

Here are some examples of calling the pascal_triangle function:

&gt;&gt;&gt; pascal_triangle(0)

[[1]]

&gt;&gt;&gt; pascal_triangle(1) [[1], [1, 1]]

&gt;&gt;&gt; pascal_triangle(5)

[[1], [1, 1], [1, 2, 1], [1, 3, 3, 1], [1, 4, 6, 4, 1], [1, 5, 10, 10, 5, 1]]

Task 3:

Write two functions, named test_pascal_row and test_pascal_triangle,with no

arguments. They should do what the name suggests – test the corresponding function. There should be at least four tests each. For testing, use assertions, in the way shown in the file assert_LCS_change.py that was posted online. In brief, each test asserts that a call of your function equals the value expected.
