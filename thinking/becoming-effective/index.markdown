---
layout: page
date: 2016-01-01 00:00:00
title: How to quickly become effective
---

In general I seem to be unusually good at getting started in a new job. This piece is an outline
on how I go about doing that.

The essential goal is to treat this as a *learning* problem, and to solve it through learning by doing. This results in both my learning more rapidly but also in my getting things done almost immediately because of how I focus my learning process.

There are essentially three key principles I apply, all about information:

1. Avoid acquiring information you don't need
2. Acquire information efficiently
3. Use the information you acquire well

I’ll elaborate on each of these and how to do them.

## Avoid acquiring information you don't need

For the purpose of this piece, learning is only useful when it allows you to get things done. Filling your brain with information is all very well, but without grounding it in practical things you're trying to get done it becomes somewhat purposeless knowledge.

There are cases where you *do* need to dump a great deal of information into your brain before you can usefully get started, but most jobs are not one of those cases and you'll learn better by not trying.

The goal of learning as little information as possible forces you to do three important things:

* It forces you to learn the right information. If you only acquire information when it’s absolutely necessary then that information was by definition useful: It enabled you to do the necessary thing.
* It forces you to do things you can actually achieve soon. If task A would require you to learn a lot and task B would require you to learn a little, do task B. It will take you less time to learn the prerequisites, so you’ll get something achieved quickly.
* It prevents you from getting distracted by the immensity of the task of trying to understand everything and forces a more useful learning discipline on you by giving you concrete places to start.

That's not to say that acquiring information is *bad*. All else being equal, more information is better than less information. But acquiring information is *expensive*, so it's important to prioritise.

Additionally, prioritising like this actually helps you acquire more information in the long run. The thing about information is that once you have acquired it you can build on it. Every little bit of knowledge you put into your head provides you with a framework on which to hang more knowledge. 

I'm essentially iterating a procedure of learn, do, learn. Each time I do something, I learn, and that expands the set of things I can do next. By acquiring our knowledge incrementally, I rapidly build up to an amount that would have seemed overwhelming at the outset, and become able to do things that if we'd tried to tackle immediately we'd just have floundered with.

As well as interleaving getting things done with learning things, I think the quality of education you get this way is better than what you would otherwise get because it contains practical experience. You don’t just learn how things work, you learn how to work with them, and you learn a lot of concrete details that might have been missing from the high level description of them.

## Acquire information efficiently

My information acquisition process is very simple:

1. Can I figure out how this works on my own? (5 minutes)
2. Can I figure out how this works with googling and reading documentation, blog posts, etc? (15 minutes)
3. Ask someone to explain it to me (however long it takes)

The third step is very important. Being stuck is not helping anyone, and your colleagues want you to succeed. Asking for help benefits everyone.

The first two steps are important too: As well as being respectful of other peoples' time (it's perfectly OK to <em>use</em> other peoples' time, but it's bad to <em>waste</em> it), trying to figure it out yourself first improves your learning in the long run and gives you a better basis on which to explain your problem to people.

## Use the information you acquire well

For the purposes of becoming effective, the value of knowledge is essentially predictive. You want to be able to answer two questions:

1. If I do X, what will happen?
2. If I want Y to happen, what should I do?

These two questions are natural inverses of each-other. In principle a valid algorithm for question 2 is “Think of all possible values of X and see if they cause Y to happen”. Everything else is just an optimisation to the search algorithm, right?

First I’ll go into how to answer question 1:

At its basic it’s two words. “Mental models”

A mental model is essentially an algorithm you can run in your brain that lets you put in actions as inputs and get outcomes as outputs.

They can be implicit or explicit: An implicit mental model is essentially one that you can run without going through all the steps. You don’t need to be able to describe the model explicitly, you just know the answer. Essentially what most people mean when they say something is intuitive is “I have an implicit mental model for how this works”. You’re essentially pretty comfortable working with anything you have an implicit mental model for and can probably get things done with it pretty readily.

Explicit mental models are more work. You have to think through the steps linearly and laboriously in order to get the answer. But they’ve got a lot of benefits too:

* They tend to be more accurate. I find implicit mental models are full of shortcuts and heuristics which makes them really efficient when they work but often leaves some major gaps.
* They’re easy to fix when they’re wrong. And mental models will be wrong, all the time. The chances of you always being able to perfectly predict things are basically zero. An explicit mental model you can just patch, but adjusting your intuitions is much harder.
* You can explain your reasoning to other people. This is especially useful when you’re stuck and want to talk a problem through with someone else.

So both types of mental models have costs and benefits, which means we're going to end up wanting to use a mix of the two.

Once you think of mental models in terms of being able to predict how things behave instead of truth about how things work you can realise that having multiple mental models of how something works is not only fine but often useful: You can cross check them against eachother to see if they make different predictions, you can use whichever is cheapest when the decision doesn’t matter very much or most accurate when it does.

Additionally, it’s not really as cut and dried as I’m making it seem. What tends to happen is that explicit mental models turn into implicit ones. Once you’re familiar enough with an explicit mental model the ideas become intuitive and internalized and you need to consult it less and less.

Here are some tips for building mental models:

1. Reuse old mental models as much as possible. When learning python I started out as “Like Ruby with funny syntax”. Then I learned a bit more and replaced this with “Like Javascript with funny syntax and a decent module system”. Then I found out about descriptors and patched it as “Like Javascript with funny syntax and a decent module system, but bear in mind that the value you put into an object might not be the value you get out of it because of these magic methods”.
2. In general, build mental models as cheaply as possible. A mental model that you can build quickly is probably much more useful than a laboriously constructed one, because you’ll be likely to resist changing the latter.
3. Patch your mental models when they make wrong predictions
4. Test your mental models constantly. This is useful a) Because it leads to finding out when you need to patch them and b) Because it greatly hastens the process of turning them into implicit mental models, which makes you more able to readily apply them in future.

That’s about all I’ve got on how to build mental models. Now onto question 2: I can predict the consequences of my actions. How do I go about predicting the actions that will lead to the consequences I want?

Here is roughly what I think of as my algorithm:

1. Generate an idea
2. What would go wrong if I did this?
3. Can I fix that?
4. If yes, give it a try and see what happens. Did it work?
    1. Yes? Great! I'm done.
    2. No? What did I miss? Did I fail to understand something? At any rate, I now know what is wrong with it. Continue onwards.
5. Take a specific thing that is wrong with it and try to come up with an idea that doesn't have that problem.
6. Take that idea back to step 2.

So basically the idea is that you want to use your mental models to predict what will happen if you try something, then you try it out and either succeed or improve your mental model: Either way, progress. The key is that you refine your ideas through a process of destruction and by finding out what doesn't work.

Unfortunately it’s got a big gap right at the beginning where I say “Generate an idea”. How do you do that? Just try things at random?

It's hard to give good advice on this one other than it gets easier with experience. Here are some things that help though:

1. The most important question is "Is this similar to a problem I've seen solved before and can I use the solution from that time?"
2. Is there an *obviously terrible* solution that you'd be embarrassed to use? Start from there and see if you can make it not terrible. 
3. If a problem seems too large, try to break it down.
4. Is there a particular subproblem that you're not sure how to solve? Assume it's solved and try to figure out what the rest of the solution would be like. What did you use from that solution? Is there a simpler thing you can solve instead?

The nice thing about the testing to destruction approach for idea generation is that there are almost no useless ideas, because you always learn more about the shape of the problem by finding what doesn't work.
 
## Fitting it all together

I like to think of this as a process of exploration. You start somewhere simple (I find “actually using the product” to be a good place to start). You look around you and, step by step, you explore around you while doing whatever jobs you can find in the areas you currently have access to. Your colleagues will help you find your way, but ultimately it’s up to you to draw your own map of the territory and figure out how all the different bits connect up. 
