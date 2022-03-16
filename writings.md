---
layout: home
title: Writings
permalink: /Writings/
---

# Machine Learning - Wrong questions only

*"Young man, in mathematics you don't understand things. You just get used to them.”*
                                                        —_John von Neumann_

Most of these have simple answers, few don't. Over time, I will forget these questions, because I will become used to the answers. So this a note in this moment of time, that will be lost in the tomorrow.

## Infant mode questions

What are the simplest examples of linear functions?

What are the simplest examples of non-linear functions?

What is a difference between a tensor and n-dimensional array?

What is a neural network with 0 hidden layers?

What are these things that are called  ‘activations’ in neural networks? If a neural network doesn't have any activation functions, is it still a neural network?

If the ReLU is not always differentiable, how is it used in gradient descent? 

Why first order gradients and not second order gradients? Why the rate of change? And not the rate of rate of change? 

Why do we care about automatic differentiation? We could easily do differentiation in high school?  That wasn't too hard. Why use backpropagation to compute derivatives? Why don’t we just teach computers symbolic differentiation( the way we do on paper)?

Wait, gradient descent is one thing. Backpropagation is another. Are they different? Oh absolutely different, I am not very bright am I?

What are the limits to gradient based optimization? Even with no vanishing or exploding gradient, where do the optimization techniques breakdown?

How much of natural selection by variation is optimization?

## Probability is one helluva drug

You tested positive for a serious disease. 

Test accuracy = 99% 

The disease happens only to 1 in 10,000 people.

What are the chances that you actually have the disease? 

**Answer**: 0.98%

What?? Didn't you say test accuracy was 99%?

RIP intuition. Long live Bayes theorem

$$P(A|B) = \frac{P(B|A) P (A)}{P(B)}$$

## Statistics has entered the chat

What’s the difference between ‘probability’ and ‘probability density’?

What are the parameters of a probability distribution? What does this book even mean when it uses the word ‘parameters’ of a distribution?

How to measure the similarities between two probability distributions?

## Information theory will solve all my life’s problems.

*(Yes, all kind of problems. Even those kind of problems)*

How is entropy the average amount of surprise? (Hint: Think about compression)

How is entropy = the expected value of Shannon information? Why do I have to re-derive this every time, why can't I just remember how 
  $$  H(X) = 𝔼[X] = [I(X)] =  − \sum p(x) log p(x) $$ 
?

Is there any part of machine learning that cannot be described through an information theoretic framework? Is there even a slight inconsistency between the two?

What can information theory not explain?