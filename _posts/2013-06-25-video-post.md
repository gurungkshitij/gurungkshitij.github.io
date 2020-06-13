---
layout: post
title:  "Magic Square Project"
date:   2020-05-10
excerpt: "Custom written post descriptions are the way to go... if you're not lazy."
project: true
tags: [sample post, readability, test, image, feature]
feature: https://s3.amazonaws.com/images.penguinmagic.com/images/products/original/16578a-5cacf03e85a00.png
comments: true
---

# Magic Square Project
A n × n magic square is an arrangement of the numbers **1, 2, . . . , n^2** in a **n × n** grid in such way
that all the rows, columns, and diagonals have the same sum.
In general, there are n rows, n columns, and
2 diagonals, for a total of **2n + 2** sums. Each sum is equal to **n(n^2+1)/2**. 
We are going to find the magic square by using stimulated annealing technique and study it's behaviour.

***Our procedure to get the magic square:***

Use simulated annealing to find magic squares for at least n = 3 and n = 4. Here are some tips for setting up the problem:

• States: The states should be all possible arrangements of the numbers  **1,2,...,𝑛^2**  in the  𝑛×𝑛  grid.

• Starting State: Randomly assign the numbers  **1,2,...,𝑛^2**  to the grid.

• Function to Maximize: Define a function m(state) that indicates how far the row, column, and diagonal sums are from the desired value. You want to minimize m, so you want to maximize −m.

• Transitions: Randomly choose two entries in the grid and swap them.

• Stopping: Make your code stop when it finds a magic square.

We will be aiming to find magic square for 𝑛=3, and 𝑛=4, squares.

***Our goal is to try to answer the following questions:***

1) What values of sig2 and decFac did you find to work best? How about for  4∗4 ?

2) Using your preferred choice of sig2 and decFac, what is the average number steps required to find a magic square?

3) How does the value of your function m change during the simulated annealing process? Make a plot that shows this clearly. How about for  4∗4  Grid?

4) Conclusion, limitation, and future work. 

<iframe width="560" height="315" src="//www.youtube.com/watch?v=Sublqdi5XlU" frameborder="0"> </iframe>

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/embed/SU3kYxJmWuQ" frameborder="0"> </iframe>
{% endhighlight %}
