---
title: "Adding Exercises"
teaching: 20
exercises: 10
questions:
- "How do I add and exercise?"
objectives:
- "Understand how to add an exercise to a lesson."
keypoints:
- "Add an exercise using a block."
---

Next, an R code block.

---
n = 100
m = 10
x = matrix(rnorm(n * m), n, m)
head(x)
---
{: .language-r}


Introductory text....

Exercise

> ## What is needed in an exercise
> 
> List the elements of an exercise. 
> 
> > ## Solution
> > 
> > Exercises are place inside of blocks that start with `>`. The solution is placed in a sub-box that starts with `> >`.
> > 
> > - title
> > - exercise
> > - solution
> {: .solution}
{: .challenge}
