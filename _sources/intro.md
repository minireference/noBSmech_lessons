# No Bullshit Mechanics Lessons

Lessons and missions to accompany [Chapter 2](https://minireference.com/static/excerpts/noBSmathphys_v5_preview.pdf#page=42)
and [Chapter 4](https://minireference.com/static/excerpts/noBSmathphys_v5_preview.pdf#page=73) in the
**No Bullshit Guide to Math & Physics** published by [Minieference Co.](https://minireference.com).

:::{admonition} Product placement
The **No Bullshit Guide to Math & Physics**
(Minireference Publishing, v5.4 2020, ISBN 0992001005) is available in print from 
[amazon](https://amazon.com/dp/0992001005)
or [lulu](https://bit.ly/noBSmathphys-sc).
For digital download (PDF, ePub, mobi) see gumroad: https://gum.co/noBSmathphys (US$29).
:::

## Contents

- tutorials = self-contained explainers (1-3 pages)
- missions = project based learning




## Context
After solving exercises and problems using pen-and-paper approach,
you must be wondering how you can solve physics problems using code.

If know mechanics you should be able to code-up solutions to the five missions
you will find in the `missions/` folder of this repo with no trouble at all.

If you don't know mechanics, you can consult the tutorials and lessons to
learn about mechanics topics in a just-in-time manner
(a.k.a. the [pull condition](https://minireference.com/blog/learning-loops/#reference-materials)).

The give you an idea of the missions you'll have to face,
consider the [Interception example](https://minireference.com/static/excerpts/noBSmathphys_v5_preview.pdf#page=78) in Chapter 4.
A mission problem statement will provide you with all the 
data of the problem as code:

```
# incoming projectile A
rAi = [0, 3]
vAi = [8*cos(40), 8*sin(40)

# intercepting projectile B
rBi = [10, 0]

```
and your job will be to write a function that solves the problem.
In this example,
compute the intitial speed `w` that sets the intitial velocity `vBi`
so that peojectile B will intercept projectile A.

Simple questions, right? 
Can you code it?

If you manage to code it, we then I'll make you extend it to variable `rAi`, `vAi`, and `rBi`, and other scenarios.
By the end of this we'll have a proper interceptor system.


Interested?
If so get started with the [SymPy Mechanics tutorial](./tutorials/Mechanics),
which will introduce you to the various math tools available to you through
the computer algebra system called SymPy. Good stuff.
If this were an RPG game, starting by printing out the [SymPy Tutorial](https://minireference.com/static/tutorials/sympy_tutorial.pdf)
and reading it would be equivalent to starting with a really good inventory.







