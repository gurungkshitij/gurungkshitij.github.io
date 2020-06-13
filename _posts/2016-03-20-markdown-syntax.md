---
layout: post
title:  "Randomwalk Project"
date:   2020-04-23
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
tag:
- markdown 
- syntax
- sample
- test
- jekyll
feature: https://coderiff.com/wp/wp-content/uploads/2015/08/1.jpg
comments: true
---



# Random Project

Consider the following two-dimensional random walk that is not confined to integer-valued coordinates: the walk starts at the origin, and each step is a randomly chosen unit vector. That is, to
determine a step of the walk, first choose an angle θ (uniformly) from the interval [0, 2π). The step
of the walk will then be (cos(θ),sin(θ)).

***I will investigate the following questions:***

1. What is the average squared distance from the origin after n steps?

2. When does the walk first return near the origin? Since the walk is not on a grid, it’s very
unlikely that it will return exactly to (0, 0). Instead, when does it return to a small circle
around the origin? For example, what is the average number of steps until the walk returns
to a circle of radius 0.5
around the origin?

3. How does the walk behave if it is constrained to the region −5 ≤ y ≤ 5? Modify your code to
keep the y-coordinate of the walk between −5 and 5. (You have freedom to decide how you
would like to do this!) Then reconsider questions 1 and 2 for your modified random walk.




> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

Make any link standout more when applying the `.btn` class.

{% https://gurungkshitij.github.io//projects/%}
<a href="#" class="btn btn-success">Hobbies Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Hobbies Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
