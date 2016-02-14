---
layout: page
date: 2016-01-01 00:00:00
title: How to quickly become effective
---

In general I seem to be unusually good at getting started in a new job. This piece is an outline
on how I go about doing that.

There are essentially three key principles I apply, all about information:

1. Acquire as little information as possible
2. Acquire information as efficiently as possible
3. Use the information you acquire as effectively as possible

I’ll elaborate on each of these and how to do them.

## Acquire as little information as possible

This one is the only one that might be counter-intuitive. The others… well, yes. You want to acquire information efficiently and use it effectively. That’s kinda what learning quickly means. But acquiring as little information as possible? What’s that about? Surely when trying to learn stuff you want to acquire as much information as possible, right?

Wrong.

This sort of thinking fundamentally misunderstand the purpose of learning, at least in this context.

Learning is only useful when it allows you to get things done. Filling your brain with information is all very well, but what if you’ve filled your brain with entirely the wrong information?

Work example (a hypothetical one. I’ve not seen this happen, though I have seen similar): Suppose you diligently sit down, trace through the database schema, learning how everything fits together. You spend about a week doing this. Then you get told that that’s the old schema and we’re 2/3rds of the way through migrating to an entirely new data storage system after which that schema will be retired. Now the knowledge of the history isn’t entirely useless, but there’s certainly more useful things you could have been doing with that week.

The goal of learning as little information as possible forces you to do three important things:

* It forces you to learn the right information. If you only acquire information when it’s absolutely necessary then that information was by definition useful: It enabled you to do the necessary thing.
* It forces you to do things you can actually achieve soon. If task A would require you to learn a lot and task B would require you to learn a little, do task B. It will take you less time to learn the prerequisites, so you’ll get something achieved quickly.
* It prevents you from getting distracted by the immensity of the task of trying to understand everything and forces a more useful learning discipline on you by giving you concrete places to start.

“But David!”, I hear you cry in horror so profound that it causes you to use exclamation marks as commas, “Are you suggesting that learning is bad? That I shouldn’t try to learn how things work?”

Rest your mind and set aside your fears, for I am not!

The thing about information is that once you have acquired it you can build on it. Every little bit of knowledge you put into your head provides you with a framework on which to hang more knowledge. The journey of a thousand miles begins with a single step. Other profound sounding metaphors that convince you of the wisdom of my advice!

We’re essentially iterating this procedure over and over again. “What can I do? Oh, there’s a thing. Lets do that. Done. What can I do now? Oh, hey, there’s another thing which I couldn’t previously have done but now can because I’ve learned stuff from the last thing I did”. By acquiring our knowledge in little bite sized chunks we’ve rapidly consumed an entire information meal.

As well as interleaving getting things done with learning things, I think the quality of education you get this way is better than what you would otherwise get because it contains practical experience. You don’t just learn how things work, you learn how to work with them, and you learn a lot of concrete details that might have been missing from the high level description of them.

Now go back and read this section again (if you haven’t already. Don’t get stuck in an infinite loop and forget to eat and die. Because I’d feel really bad about that and it’s not an efficient way to learn at all). It’s literally the most important bit of this post and I really want you to take it on board.
Acquire information as efficiently as possible

Here is my knowledge acquisition procedure. I bequeath it to you. Use it well:

1. Can I figure out how this works on my own? (5 minutes)
2. Can I figure out how this works with googling and reading blog posts? (15 minutes)
3. Ask someone to explain it to me (however long it takes)

OK, I know I said the previous section was the most important thing in this essay, but this one is pretty important too. For the love of all, please do not sit there ineffectual and frustrated because you can’t figure out what’s going on. It’s nice that you don’t want to bother your colleagues, and the first 20 minutes or so of trying to figure things out on your own is important as a way of preventing you from doing that too much, but your colleagues need you to be useful. They also probably possess the exact information you need. It is their responsibility and to their benefit to help you out when you get stuck.
Use the information you acquire as effectively as possible

This is a fuzzy one. It’s basically “Be good at thinking”. If there were a fool proof set of advice on how to do this the world would look very different than it currently does. Still, here are some ideas you might find useful.

Here is roughly what my thinking procedure looks like. Or, more accurately, here is my inaccurate model of what my thinking procedure looks like that I currently use to make predictions but don’t really expect corresponds that exactly to reality.

Err. That paragraph might be a bit of a clue as to what I’m about to say.

If I may get all meta for a moment: What is the purpose of knowledge acquisition?

I mean, sure, you want to get stuff done, but how does knowledge help you do that?

To me the value of knowledge is essentially predictive. You want to be able to answer two questions:

1. If I do X, what will happen?
2. If I want Y to happen, what should I do?

These two questions are natural inverses of each-other. In principle a valid algorithm for question 2 is “Think of all possible values of X and see if they cause Y to happen”. Everything else is just an optimisation to the search algorithm, right?

First I’ll go into how to answer question 1:

At its basic it’s two words. “Mental models”

A mental model is essentially an algorithm you can run in your brain that lets you put in actions as inputs and get outcomes as outputs.

They can be implicit or explicit (note: This is my terminology and is probably non-standard): An implicit mental model is essentially one that you can run without going through all the steps. You don’t need to be able to describe the model explicitly, you just know the answer. Essentially what most people mean when they say something is intuitive is “I have an implicit mental model for how this works”. You’re essentially pretty comfortable working with anything you have an implicit mental model for and can probably get things done with it pretty readily.

Explicit mental models are more work. You have to think through the steps linearly and laboriously in order to get the answer. But they’ve got a lot of benefits too:

* They tend to be more accurate. I find implicit mental models are full of shortcuts and heuristics which makes them really efficient when they work but often leaves some major gaps.
* They’re easy to fix when they’re wrong. And mental models will be wrong, all the time. The chances of you always being able to perfectly predict things are basically zero. An explicit mental model you can just patch, but adjusting your intuitions is much harder.
* You can explain your reasoning to other people. This is especially useful when you’re stuck and want to talk a problem through with someone else.

So both types of mental models have costs and benefits. So which do we choose?

Answer: Both!

Once you think of mental models in terms of being able to predict how things behave instead of truth about how things work you can realise that having multiple mental models of how something works is not only fine but often useful: You can cross check them against eachother to see if they make different predictions, you can use whichever is cheapest when the decision doesn’t matter very much or most accurate when it does.

Additionally, it’s not really as cut and dried as I’m making it seem. What tends to happen is that explicit mental models turn into implicit ones. Once you’re familiar enough with an explicit mental model the ideas become intuitive and internalized and you need to consult it less and less.

Here are some tips for building mental models:

1. Reuse old mental models as much as possible. When learning python I started out as “Like Ruby with funny syntax”. Then I learned a bit more and replaced this with “Like Javascript with funny syntax and a decent module system”. Then I found out about descriptors and patched it as “Like Javascript with funny syntax and a decent module system, but bear in mind that the value you put into an object might not be the value you get out of it because of these magic methods”.
2. In general, build mental models as cheaply as possible. A mental model that you can build quickly is probably much more useful than a laboriously constructed one, because you’ll be likely to resist changing the latter.
3. Patch your mental models when they make wrong predictions
4. Test your mental models constantly. This is useful a) Because it leads to finding out when you need to patch them and b) Because it greatly hastens the process of turning them into implicit mental models, which makes you more able to readily apply them in future.

That’s about all I’ve got on how to build mental models. Now onto question 2: I can predict the consequences of my actions. How do I go about predicting the actions that will lead to the consequences I want?

Here is roughly what I think of as my algorithm:

Section 1:

1. Generate an idea
2. Is it obviously stupid? Throw it away and go back to 1.
3. Is it still not obviously stupid after a little bit more thought? Set it aside
4. How many not-obviously-stupid ideas do have I set aside? 3 or so? If so, proceed to the next section.
5. How long have I taken over this? Too long? If so and I have any ideas set aside, go to the next section. Else, step away from the problem. Either come at it from another angle of attack or go do something else and let it simmer away in the background.

Section 2:

I now have a bunch of idea candidates. Put some proper thought into it and attempt to determine which amongst them is best. This may require actually trying some things out and gathering new information.

Once I have determined which of these is the best, decide if I’m satisfied with it. If I’m not, start the whole process again. If I am, this is the solution I’m going to go with for now.

So basically the idea is that you want to use cheap mental models to filter ideas quickly, then once you’ve got a few goodish ideas to compete against eachother you can properly explore how they work as solutions. I don’t know how accurate a description this is, but I think it’s broadly OK.

Unfortunately it’s got a big gap right at the beginning where I say “Generate an idea”. How do you do that? Just try things at random?

Well, you just… do. I don’t really know. This may be where I have to fall back on my “Maybe I’m just kinda smart?” answer, but if so then sadly I’m not actually smart enough to give a good answer here. Here are some things I think that I might be doing, but it’s mostly speculation:

1. Try and narrow the search space as much as possible. If you think you might be able to solve the problem by making changes to a specific thing, only look at ideas which change that thing. If that’s proving not to work, try a different thing. You should be able to use a mix of past experience and proximity to guide you here – think of similar problems you’ve solved in the past and look near what the solutions to those were. If you can’t think of any similar problems or those solutions don’t pan out, look nearby to the problem. The advantage of looking at a smaller area is that there are fewer things to try so you’re more likely to hit on the right one quickly.
2. Try and narrow the problem by breaking it up into smaller pieces. When you do this it becomes much easier to narrow the search space as in the previous section. In order to do this try to find natural “cleave points” where the problem breaks neatly along specific lines.
3. When you decide a solution is a bad idea, see if there are any general reasons why it’s a bad idea and try to avoid areas that relate to those reasons.
4. Conversely, if an idea almost works but not quite, try exploring around it to see if there are any variations on it that work better.
5. If you’re totally stuck, try thinking of something completely out there. It probably won’t work, but exploring why it won’t work might tell you interesting things about the problem and give you other areas that worked.

I don’t think that’s sufficient. I’m afraid this might just be a case of practice makes less imperfect. I think part of why I’m “smart” is that my brain just won’t shut up (seriously. It’s annoying), so tends to gnaw at problems like a dog with a bone until they give in, which has given me a lot of practice at trying to figure things out. Really, this might be the best advice I can give you, but you’ve probably heard it so many times that it’s redundant: Practicing solving problems and figuring things out makes you better at it. Still, I think there should be things you can do above and beyond that – practice is no good if you’re practicing doing something badly. I’d love to have a firmer idea of what they were.

## Fitting it all together

I like to think of this as a process of exploration. You start somewhere simple (I find “actually using the product” to be a good place to start). You look around you and, step by step, you explore around you while doing whatever jobs you can find in the areas you currently have access to. Your colleagues will help you find your way, but ultimately it’s up to you to draw your own map of the territory and figure out how all the different bits connect up. Think of this post as my personal and eclectic guide to software cartography.

Does it work? Beats me. Certainly I seem to be doing something right, and I really hope that this encapsulates some of it. I think it’s mostly good advice, but there’s definitely a bit of a danger that I’m cargo culting my own brain here.

If you try any of this, do let me know how it goes, and please do share your own ideas in comments, email, etc. because I’d really like to know how to get better at this too.
