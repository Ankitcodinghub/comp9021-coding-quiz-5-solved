# comp9021-coding-quiz-5-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/comp9021-solved-5/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131714&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9021 Coding Quiz 5  Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
COMP9021 Principles of Programming

Coding Quiz 5

Description

You are provided with a stub in which you need to insert your code where indicated without doing any changes to the existing code to complete the task.

Given the value of seed and density, the provided code randomly fills an array (or grid) of size 10 x 10 with 0s and 1s. Your task is to determine and output the size of the largest parallelogram with horizontal sides. A parallelogram consists of a line with at least 2 consecutive 1s, with below at least one line with the same number of consecutive 1s, all those lines being aligned vertically in which case the parallelogram is actually a rectangle, for instance:

1 1 1

1 1 1

1 1 1

1 1 1

or consecutive lines move to the left by one position, for instance:

1 1 1

1 1 1

1 1 1

1 1 1

or consecutive lines move to the right by one position, e.g.

1 1 1

1 1 1

1 1 1

1 1 1

The size is the number of 1s in the parallelogram. In the above examples, the size is 12.

See test cases below for more examples.

Make sure not to change the filename quiz_5.py while submitting by clicking on [Mark] button in Ed. It is your responsibility to check that your submission did go through properly using Submissions link in Ed otherwise your mark will be zero for Quiz 5.

Test Cases

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 1 Here is the grid that has been generated:

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

There is no parallelogram with horizontal sides.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 2 Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 0

0 1 0 0 1 0 1 0 0 1

1 0 1 1 1 0 1 1 1 0

0 0 1 0 1 1 0 1 0 0

0 0 0 1 0 0 1 1 0 1

1 0 1 0 1 1 0 1 1 0

1 0 0 0 0 1 1 0 0 0

0 0 0 1 1 0 0 1 1 1

1 1 0 1 0 1 1 0 0 0

1 0 0 1 0 1 1 0 0 0 The largest parallelogram with horizontal sides has a size of 4.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 3

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 0 1 0 1 0 0 1 1 1

1 1 0 1 0 1 0 1 1 1

1 0 1 1 1 1 1 0 1 1

1 1 1 0 1 0 0 1 1 1

1 1 0 1 1 1 0 1 1 1

0 0 1 0 0 0 1 1 0 0

1 1 1 0 1 1 1 1 0 1

1 1 0 1 1 1 1 1 0 1

1 1 1 0 1 0 0 0 0 1

The largest parallelogram with horizontal sides has a size of 12.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 4

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 0 1 1 1 0 0 1

1 0 1 1 1 1 1 1 1 0

0 0 1 0 1 1 1 1 0 1

1 1 1 1 0 0 1 1 0 1

1 0 1 1 1 1 0 1 1 1

1 1 1 1 0 1 1 0 0 1

1 0 0 1 1 1 1 1 1 1

1 1 0 1 0 1 1 1 1 0

1 0 1 1 1 1 1 0 0 1

The largest parallelogram with horizontal sides has a size of 12.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 1 4

Here is the grid that has been generated:

1 0 1 0 1 1 1 1 1 0

1 0 1 1 0 1 1 1 0 1

0 0 0 0 1 1 1 0 1 1

1 1 1 1 1 1 1 0 1 0

1 1 0 1 1 1 1 1 1 1

0 1 1 1 1 1 1 1 0 1

0 1 1 1 1 0 1 0 1 1

1 1 1 0 1 1 1 1 1 1

1 0 1 1 1 1 0 1 1 1

1 1 1 1 1 0 1 1 0 1

The largest parallelogram with horizontal sides has a size of 16.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 5

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 1 1 1 0 1 1 1

1 1 1 0 0 1 1 1 0 1

1 1 1 1 1 1 1 1 1 0

1 0 0 1 0 1 1 1 1 1

0 1 1 1 1 1 1 1 0 0

1 1 1 0 1 1 1 0 1 1

1 1 1 1 1 1 1 0 1 1

1 1 1 1 1 1 1 0 1 1

1 0 0 1 1 0 0 1 1 1

The largest parallelogram with horizontal sides has a size of 15.

Test Cases Explained

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 1

Here is the grid that has been generated:

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0 0 0

There is no parallelogram with horizontal sides.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 2 Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 0

0 1 0 0 1 0 1 0 0 1

1 0 1 1 1 0 1 1 1 0

0 0 1 0 1 1 0 1 0 0

0 0 0 1 0 0 1 1 0 1

1 0 1 0 1 1 0 1 1 0

1 0 0 0 0 1 1 0 0 0

0 0 0 1 1 0 0 1 1 1

1 1 0 1 0 1 1 0 0 0

1 0 0 1 0 1 1 0 0 0

The largest parallelogram with horizontal sides has a size of 4. $ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 3

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 0 1 0 1 0 0 1 1 1

1 1 0 1 0 1 0 1 1 1

1 0 1 1 1 1 1 0 1 1

1 1 1 0 1 0 0 1 1 1

1 1 0 1 1 1 0 1 1 1

0 0 1 0 0 0 1 1 0 0

1 1 1 0 1 1 1 1 0 1

1 1 0 1 1 1 1 1 0 1

1 1 1 0 1 0 0 0 0 1

The largest parallelogram with horizontal sides has a size of 12.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 4

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 0 1 1 1 0 01 0 1 1 1 1 1 1 1 0 1

0 0 1 0 1 1 1 1 0 1

1 1 1 1 0 0 1 1 0 1

1 0 1 1 1 1 0 1 1 1

1 1 1 1 0 1 1 0 0 1

1 0 0 1 1 1 1 1 1 1

1 0 1 1 1 1 1 0 0 1

The largest parallelogram with horizontal sides has a size of 12.

$ python3 quiz_5.py Enter two integers, the second one being strictly positive: 1 4

1 1 0 1 0 1 1 1 1 0

Here is the grid that has been generated:

1 0 1 0 1 1 1 1 1 0

1 0 1 1 0 1 1 1 0 1

0 0 0 0 1 1 1 0 1 1

1 1 1 1 1 1 1 0 1 0

1 1 0 1 1 1 1 1 1 1

0 1 1 1 1 1 1 1 0 1

0 1 1 1 1 0 1 0 1 1

1 1 1 0 1 1 1 1 1 1

1 0 1 1 1 1 0 1 1 1

1 1 1 1 1 0 1 1 0 1

The largest parallelogram with horizontal sides has a size of 16.

$ python3 quiz_5.py

Enter two integers, the second one being strictly positive: 0 5

Here is the grid that has been generated:

1 1 0 1 1 1 1 1 1 1

1 1 1 1 1 1 0 1 1 1

1 1 1 0 0 1 1 1 0 1

1 1 1 1 1 1 1 1 1 0

1 0 0 1 0 1 1 1 1 1

0 1 1 1 1 1 1 1 0 0

1 1 1 0 1 1 1 0 1 1

1 1 1 1 1 1 1 0 1 1

1 1 1 1 1 1 1 0 1 1

1 0 0 1 1 0 0 1 1 1

The largest parallelogram with horizontal sides has a size of 15.
