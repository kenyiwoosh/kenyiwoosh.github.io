---
layout: post
comments: true
#title:  "Um_nik method"
title: "Getting out of the plateau in competitive programming "
excerpt: "I came across an interview Um_nik gave some days ago where he was quite convinced that anyone can become red and that raw talent just plays 1%. This blog is an attempt to come up/hack/crack an strategy to get out of the plateu."
date:   2024-04-10 12:30:00
mathjax: true

---

<style>
.post-header h1 {
    font-size: 35px;
}
.post pre,
.post code {
    background-color: #fcfcfc;
    font-size: 13px; /* make code smaller for this post... */
}
</style>

**4-10-2024**

`current mmr = 1352`

I find it fascinating how some people is able to solve problems really fast in competitive programming. The ones with higher rating, the red ones ($$2300\geq$$), usually have a $$4\times$$ performace than the green or cyan ones ($$1600\geq x\geq1200$$). I would like to have that superpower, but unfortunately it is just too fun to quite even if one is average!

As someone who has been stuck quite a while in a plateau, I would like to try some strategies that might help "hack" how someone can get out of that low _mmr_.

>  Disclaimer: I didn't use to practice real time contests, but I already studied algorithms and data structures 

## Resources and ideas

### Basic `[,1500]`

There are tons of resources out there but it is important to be able to separate the real pearls.<br>Find problems according to your rating $$+200$$. AtCoder and Codeforces will do, these are pages to visualize the problems and its corresponding ratings, and keep track of the problems you already solved.

- https://cftracker.netlify.app/contests
- https://kenkoooo.com/atcoder

> Do not be afraid of losing rating. At the end no matter how much you gain or loss, your rating will eventually find its place. That is, if you actual level corresponds to a rating equal to `rank` then the sum of all your rating changes across contests will lead to `rank`.  See [this video](https://www.youtube.com/watch?v=E-aylp6MZnM).

### Low-Intermediate `[1500,1800]`

At my current level, I can consistently solve until `problem C`, nevertheless I find two limiters that might be holding me back. The first one is that I am too slow at solving A,B,C. The second one is that I am not used to solve problems with a `+1800` rating so even if I manage to solve the first three fast I would strugle to solve D.

- The first point can be solved by **just participating at contests**, be comfortable with the pressure, and then **look at red coders solutions**, as they usually write lesser lines than I do. That means their solution idea is probably more simple and that is the key to solve them faster as also the implementation does't get messy. 
- The solution for the second point is **always practice offline with problems with `+1700` of rating**. The brain evetually get used to that level of difficulty.
  - [Atcoder Problems](https://kenkoooo.com/atcoder/#/list/?fromDiff=1600&toDiff=1999&sortBy=solverCount&sortOrder=desc)
  - [Codeforces Problems](https://codeforces.com/problemset?order=BY_SOLVED_DESC&tags=1700-)

____

...

---

## Log of solved problems

[Link to spreadsheet](https://docs.google.com/spreadsheets/d/1_cvh_1Dn9l7P_vZ2F-5hmWu5f0wQMM9UtR11HFlsrsM/edit?usp=sharing)

---

## Misc

- [Here](https://codeforces.com/blog/entry/66909) someone gave away a list of high quality problems which are a bit more mathematical but still fun. I gathered the problems in vjudge lists:
  - [[1st part](https://vjudge.net/contest/317361)], [[2nd part](https://vjudge.net/contest/317362)], [[3rd part](https://vjudge.net/contest/317363)], [Roadmap](https://docs.google.com/document/d/1-7Co93b504uyXyMjjE8bnLJP3d3QXvp_m1UjvbvdR2Y/edit)

- Another good idea on how to practice is to watch screencasts and listen how they go through a problem. Some good channels are:
  - [SecondThread](https://www.youtube.com/@SecondThread/videos), [ColidGalen](https://www.youtube.com/@ColinGalen/videos), [Umnik](https://www.youtube.com/@umnik_team/videos), [Errichto2](https://www.youtube.com/@Errichto2/videos), [Errichto]( https://www.youtube.com/@Errichto/videos).
- I was thinking about doing some notes on dynamic programming but I think I need to solve more problems.
