---
layout: post
title: Trouble Project
date: 2020-04-16
excerpt: "MathJax Example for Moon Jekyll Theme."
tag:
- markdown 
- mathjax
- example
- test
comments: true
---

# Trouble Project

In the game Trouble the goal is to move a bunch of markers from a starting point all the way to
the ending point. Ignoring some subtleties of the game, the basic move is very simple:
- You roll a standard 6-sided die.
- You move your marker the number of spaces equal to the value on the die.
- If you rolled a six, you roll and move again. You keep doing this as a long as you roll sixes.

For example, if you roll a 3, then you move 3 spaces. If you roll a 6 followed by a 3, then you move
6 + 3 = 9 spaces. If you roll a 6, another 6, and then a 3, then you move 6 + 6 + 3 = 15 spaces.

***My investigation:*** 
1) What is the average **length** of a move?
2) How does the average length of a move depend on the roll-again value? That is, if you change the rules so that you roll again after rolling a 1, what is the average length of a move? 
Do this for all six possible roll-again values.
3) Suppose you are playing a head-to-head game with another person. You use the “roll again on 1” rule, the other person uses the “roll again on 6” rule.
You both roll your die to complete a move. The winner is who ever has a the larger move. (If there is a tie, repeat until there is a winner.) Is this a fair game, in the sense that
both players have an equal probability of winning? 
If not, who has the advantage? How can you explain this, given what you found **for** question 2? 
4) What is the distribution of move lengths for each roll again value? Make a histogram of move lengths
for at least 1000 simulations of each roll-again value. How does this help you understand what you found for question 3?
5) Conclusion, Limitation, and Future work.

[MathJax](http://www.mathjax.org/) is a simple way of including Tex/LaTex/MathML based mathematics in HTML webpages. To get up and running you need to include the MathJax script in the header of your github pages page, and then write some maths. For LaTex, there are two delimiters you need to know about, one for block or displayed mathematics `\[ ... \]`, and the other for inline mathematics `\( ... \)`.

## Usage

To enable MathJax support be sure Kramdown is your Markdown flavor of choice and MathJax is set to true in your `_config.yml` file.

~~~
markdown: kramdown
mathjax: true
~~~

~~~
Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]
~~~

Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]

The only thing to look out for is the escaping of the backslash when using markdown, so the delimiters become `\\[ ... \\]` and `\\( ... \\)` for inline and block maths respectively.
    

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$
