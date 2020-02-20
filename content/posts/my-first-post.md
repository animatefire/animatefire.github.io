---
title: 'CS50 Week 3: Algorithms'
date: 2020-02-19T14:43:27-05:00
draft: true
toc: false
images:
tags:
  - untagged
---

## Humbled by CS50: Learning to Do Things Recursively (In Life)

### Week 3: Algorithms

Week 3 is where shit really hit the fan, and I felt like I was staring up at an insurmountable task. In weeks 0-2, I pushed myself to not even consider the "lesser" problem sets labeled "feeling less comfortable" and went straight for the more challenging ones.

But week 3's focus on the divide and conquer algorithm known as merge sort.

I have no interest in hating on CS50 or its creators. I personally love the course. And part of this post is about how to _use_ CS50, and how not to use it. Long story short: make use of the "less comfortable/more comfortable" tracks.

My first suggest is to do _all_ of the problem sets for a given week, in order, and only submit the ones that you feel most proud of. For example, for Week 3: Algorithms, there are 3 problem sets:

- Plurality [Required]
- Runoff [Option A: Feeling Less Comfortable]
- Tideman [Option B: Feeling Less Comfortable]

On my original run through I did Plurality followed by Tideman, because, you know--I'm a legend in my own mind.

#### Not So Fast, Pard'ner

I got my butt handed to me. Not only did I want to do Tideman, but I wanted to do Tideman using _merge sort_. Hilarious.

It's one thing to grok merge sort and recursion, it's quite another to implement it in C as a beginner to that language. Heck--I didn't even _get_ to the sort part of the program before I gave up; I wasn't even understanding how to implement the other aspects of the program.

I banged my head against the wall for a few days, and then in the shower, where I have all of my ephiphanies, I decided I would give myself a "warm up" by going through the Runoff [Optiona A: Feeling *Less* Comfortable] problem first, and then return to Tideman.

Taking my time, and making a few silly mistakes, it took me about 2 days to knock out Runoff with a perfect score (versus their automatic testing suit check50).

So I returned to Tideman, a bit more humble, a bit more ready--or so I thought.

#### Fail

So even with the experience of Runoff under my belt, Tideman was still too much. I worked in it for another two days, making much better progress all the way up to the point of writing the sort pairs function. It was at this point that I tried to hobble something silly together--and the more I hobbled, the more I realized it wasn't going to happen; not with my current level of knowledge with C.

I started combing through solutions on the internet for a mergesort solution in C. Not to cheat, mind you, but to learn. I wanted to peak at the answers of others, and then turn around and try it again myself.

Here's what I learned: you can pass expressions as arguments into functions in C. I felt as if I did not know this. I think I did know it--somewhere deep down in the fundamentals of my education, but somewhere along the way I'd forgotten it.

In looking at some popular solutions online, I learned two things about C:

1. You can pass expressions as arguments (into functions).
2. You can call a function without supplying all of its arguments.

Additionally, you can call a function without supplying all of its arguments in C; in other words, arguments can be _optional_.

I did not know this either. But it seems crucial to writing merge sort in the CS50 Tideman problem recursively, within the strictures that they give you--since you are not allowed to write functions outside of the functions you are given.
