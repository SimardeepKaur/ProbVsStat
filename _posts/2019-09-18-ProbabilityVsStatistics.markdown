---
layout: post
title:  "What are Random Variables??"
date:   2016-09-01 11:11:11 +0100
---
Random variables become a nightmare for the people when they first encounter it in Probability or Statistics course. In this blog, I would take you through random variables. What if I say random variables are not actually variables, but are functions which takes up random values. Are you confused? You need not worry as this post is written to remove all the confusions. I used the word **'function'** in above definition. Let us start by understanding what are functions in mathematics.

Imagine you have a juice vending machine and you have only 3 fruits: apple, mango and banana. You input apple to the machine and you get apple juice as output. Similarly with mango you get mango juice and with banana you get banana juice.

<img src="img/funAna.png" width="400"/>

Here we can see two sets:
1. Input set: {mango,banana,apple}
2. Output set: {mango juice, banana Juice, apple juice}

Both these sets are related to each other through Juice vending machine. Similarly mathematical functions are also mapping between two sets: Input set and Output set. These are related to each other by a rule which is called $f(x)$. Let $f(x) = 2x + 1$.Now if you input 1 to this function, you will get 3 as output. For -2, the output will be -3 and for input 5, output will be 11.

<img src="img/map.gif" width="300"/>

 [Source](http://dl.uncw.edu/digilib/Mathematics/Algebra/mat111hb/functions/inverse/map.gif) 

The input set is called Domain while the output set is called Co-Domain. Random variables are also functions whose input set is outcome of an experiment and output set is a set of real numbers.These are represented by represented by capital letter(Eg. $X$) Consider an experiment of tossing a coin. We can have two outcomes: *Heads* or *Tails*. Let us map Heads to 1 and Tails to 0.

<img src="img/randomVar.png" width="400"/>

In the same way we can map any experiment outcome to real numbers using random variables. Take another example where we have three different colors ball in a box: Red, Green and Blue. So we map the outcome of the experiment in the following way.

|Outcome of Experiment | Real number|
|----------------------|------------|
|Drawing a Red ball    | 1          |
|Drawing a Blue ball   | 2          |
|Drawing a Green ball  | 3          |

Now one will ask, why do we do such mapping? To understand this let me put few probability questions:

* P(getting more than 3 in single throw of a dice)
* P(getting 2 heads in 4 tosses of a coin)
* P(getting a number between 2 and 5 in single throw of die)

Don't you feel this approach of representing probability is tedious. Also probability is part of mathematics so we needed to find a way to represent these probability in mathematical form so that we can perform mathematical operations on them. This is achieved using Random Variables.Now I will rewrite the above probabilities using random variables.

* $P(X > 3)$ : Here $X$ is the value on the die
* $P(X = 2)$ : Here $X$ is number of heads
* $P(2 < X < 5)$ : Here $X$ is the value on the die

As we can see Random variable approach is more compact and provides a convenient way for performing  mathematical operations.

But why it is called *variable* and that too *random*. Let us consider our fruit juice example above. Our input to Juice machine is fruit. But which fruit? Fruit can be apple, banana or mango. So what can we say about the value of fruit? Is it fixed or variable. Since the value of fruit can take any value from fruit set, so it is variable. So anything whose value is not fixed is called variable. If we take $X$ as *outcome of tossing of coin* where Heads will be mapped to 1 and Tails to 0. So what values $X$ can take? $X$ can be 0 or X can be 1. In this way random variables are treated as variable. Let us now extend our fruit juice example. Now you own the juice shop which sells the 3 juices. So your customers will come and ask for any of the 3 juices. Can you as a shopkeeper tell with certainty which juice the next customer will demand. Based on your past experience you can only guess but cannot say anything with 100 percent certainty. The demand for type of fruit juice is random and can take any value. Similarly when you toss a coin, can you say with certainty whether it will be Heads or Tails or when you throw a die, can you predict its outcome what number will come. So the  random variables are called random because the value of this variable cannot be defined with certainty, we can only make a guess and this guess is called **probability** of having a particular value of random variable. In coin toss experiment, $P(X=1) = 0.5$. So we can only say that there is 50 percent chance of Heads.

But then what is the difference between the variable $x$ in the equation $y = 2x + 1$ and the variable $X$ of tossing a coin. If I tell you the value of $y=1$. What can you tell about the value of X. Can't you say with full certainty that the value of $x$ will be $0$. So here the variable $x$ is deterministic and not random. So this cannot be called a Random Variable.

So from the discussion above we can say a random variable is a function which maps *outcomes of random experiment* to *real numbers*. This *outcome of random experiment* is called probability space of a random variable. Since this is the input set to the function so it is called Domain of the random variable and is represented by $\Omega$. While the output set or Co Domain is a set of real numbers represented by $\mathbb{R}$. In function notation it can be defined like this: $X:\Omega \to \mathbb{R}$.

For coin tossing experiment $\Omega = \{Heads,Tails\}$ and $\mathbb{R} = \{1,0\}$. So we can write like this:

* $X(Heads) = 0 $
* $X(Tails) = 1 $

For convenience, we omit the bracket part and write it simply as $X = 0$ or $X = 1$. Hope this might have cleared the concept of Random variables and now you can see why we treat Random variables  more as a variable and not as a function, although random variables are actually functions!!!
