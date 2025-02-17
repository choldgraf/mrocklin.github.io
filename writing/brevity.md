---
title: Short attention span
tagline: Brevity is the soul of wit
date: 2020-07-13
---

# Short Attention Span

Speaking truth is easy.  Getting people to listen is hard.


## Summary

This post talks about communicating effectively to a short attention span.
It lays out practical writing style advice to respect the reader through brevity.

In particular, we discuss the construction and use of an *attention span budget*.


## Ten Tips for Keeping Attention

Let's go through the following ten tips to establish reader trust and build attention span:


### 1.  Tell them where they're going

*Uncertainty causes stress.  Reduce reader stress.*

Also, give them a roadmap in case they want to skip around.

In this post we're going to cover the following tips:

1.  Tell them where they're going
2.  Front-load content and results
3.  Break up long blocks of prose
4.  Earn and then burn attention span
5.  Say important things
6.  Avoid boilerplate
7.  Acknowledge bias to build trust
8.  Be brutally concise
9.  Don't fill time
10.  A worked example

### 2. Front-load content

*Put the important bits first.*

More readers will start your post than will finish it, and those that finish it
will skim.

You'll notice that every section of this document includes a single line of
text at the top of the section.  This is because I know that you will skim,
and I want to make sure that you get the gist of my message, even if you don't
stay around for the whole thing.

Front-loading content helps us to earn the readers' attention,
and helps make sure the reader gets our message,
even if we don't achieve their attention for long.


### 3. Break up long blocks of prose

*Humans like variety.  Switch between different visual elements every few lines.*

By "visual elements" I mean things like the following:

1.  Paragraphs of normal prose
2.  Bulleted lists, like this one
3.  **Bold text** on a single line, or an indented quote
4.  Code blocks (especially if you have colorful syntax highlighting)

Paragraphs or lists longer than four lines are often skipped.
However if you interleave paragraphs and bulleted sections,
or include some bold text lines and code blocks in there then people
find it more reasonable to go through, even if it's the exact same content.

**Interleaving style is an easy way to break things up.**


### 4. Deliver lessons after earning the reader's attention

*Win the listener's respect before you ask for their time.*

I arrive at content excited.  I've already clicked on a post or entered a
conference talk.  I've bought in.

However, that excitement lasts about 20 seconds for a blog post or three
minutes for a conference talk.  It is within that time that we need to hook the
listener/reader and make them want to stay for longer.

This looks different in different contexts:

1.  In a conference talk I often start out with a live demo.
    Most people save this for the end of the talk,
    but to me that seems like a missed opportunity to earn attention quickly.

    By seeing a flashy demo the audience is riveted and super-curious about how you achieved it.
    They'll hang on every word to figure out your magic.

2.  In a blog post you might put important results up front in the summary,
    or start with your primary image.
    You can include these results or images later in the post as well after you've built context,
    but giving them dessert before the meal can help get them excited.

As an analogy think about a child sitting down to play a game.  They'll listen
for a little while to learn about the instructions, but you have to get playing
within a few minutes, or else they get agitated and leave.  If you can
manage it, design your game so that you can start playing right away.
Then, once they're invested in the game and see that it's fun you can get
pretty deep into the rules and they'll be excited to learn more.

We have to earn the listener's attention before we can use it to teach them
things.

(*small pet peeve, when writing talk slides try to avoid placing an "About me"
section at the front.  This burns one of your three minutes of starter
attention span.  The audience probably didn't come to learn about you.*)


### 5. Teach something.

*Write for a reason.*

My most popular blog posts were written in a state of controlled rage.

1.  [Why I Avoid Slack?](https://matthewrocklin.com/blog/2019/02/28/slack-github)
2.  [The Role of a Maintainer](https://matthewrocklin.com/blog/2019/05/18/maintainer)
3.  [Write tests.](https://matthewrocklin.com/blog/work/2016/02/08/tests)

These were conversations that I had had hundreds of times and wanted to have no longer.
I wanted to change the behaviors of people immediately around me.
They weren't solving abstract problems or thinking broadly about what the world
might be.  No.  They were tightly scoped and specific and borne of great
internal turmoil.

The key to a great blog post is to channel internal turmoil into a fair, balanced, and concise document.


### 6.  Be Novel. Avoid Boilerplate.

*Most content generated by companies today is low-information.  Don't copy their bad style.*

Marketing professionals today employ ghost writers who translate a relevant
message into 1000 words.
Here is an example:

- **Product Marketing team**: *We just released our new machine learning product that helps companies meet their cyber security needs.  We would like to raise awareness.*
- **Ghost writer**: *Sure. 1000 word blog post coming right up*

This becomes a long post about the company's
history, the history of cyber-security, how machine learning has been used to
revolutionize other fields, and other things that readers have already read.
More often than not it's a waste of time.

If you're new to writing, then you might be tempted to copy what you see.
This is safe, but I encourage you to develop your own style quickly.
Be brief, be genuine, and rework the same content a few times and you'll
kick the crap out of ghost content within a few tries.
You don't need to "try to look like a blog post".

*This applies to slide presentations, talks, and everything else too*


### 7.  Stay Balanced. Acknowledge Your Bias

*The best way to establish trust is to acknowledge your bias*

*Well, hey, I get paid if you buy this thing, so you probably shouldn't trust me, but let's dive into it and you can come to your own conclusions.*

Honesty is disarming and a wonderful way to establish connection.
It has the side benefit of being the right thing to do.

My favorite example of this is our [Dask vs Spark](https://docs.dask.org/en/latest/spark.html) documentation.
It's informative and tries hard to be unbiased.
It also ends with this line, which we've gotten repeated praise for:

> If you are looking to manage a terabyte or less of tabular CSV or JSON data, then you should forget both Spark and Dask and use Postgres or MongoDB.

:)

Also, staying balanced and honest will build self-respect.
We're social animals, and being honest to our neighbors makes us feel fulfilled.


### 8.  Be Brutally Concise

*Every word costs attention.  Remove unnecessary words.*


### 9.  Don't fill time

*When you're done, be done.  Everyone appreciates getting time back.*


### 10. Example

This is the last piece of material I was working on with a colleague about an upcoming webinar.
We're going to show before and after:


#### Before

This Thursday at 5pm ET, we’ll be piloting our very first YouTube Live stream here at Coiled!

We’ll be talking about scalable computing, when you want to do it and when you don’t, and doing some live Python coding to show you how to

-   Use Dask to scale up your pandas code to larger datasets locally, in order to utilize all your cores on your laptop or local workstation and
-   Use Dask and Coiled to scale out your computation to a cluster on the cloud, when you need more cores than your laptop can provide.

We’ll first chat about the general uses of distributed computing and how to figure out when you really need to use it (generally when you’re either RAM-bound or CPU-bound). We’ll then dive into using the now famous NYC taxi dataset and we’ll see how you can seamlessly move from pandas to dask to scale up computation, all within the comfortable environment of JupyterLab. The scalable dask code you write mimics the pandas API because, as we’ve written before, the social goal of dask was to “invent nothing” (we wanted to be as familiar as possible to what users already knew in the PyData stack).

#### After

Join us for Coiled's first live stream!

We'll cover both the opportunities and the challenges of scaling data science workloads with Pandas using a real-world example:

1.  Explore and clean a raw dataset with Pandas
2.  Scale this workload locally with Dask
3.  Scale this workload onto the cloud with Dask and Coiled

Join us this Thursday 5pm US Eastern time as we encounter, triage,
and resolve common challenges that come with scaling data science in the real world.


#### Analysis

We've lost some content, but everything is a lot tighter.
The content that we lost wasn't critical to our objective of informing the
reader that they should attend the webinar, or what the webinar would be about.


## Extra: Personal Anecdote

*My first draft of this post had this section first, but I figured it wasn't
that important, so I put it down here instead.  You can safely skip it.*

Teaching students taught me the value of writing to an attention budget.

As a graduate student I taught computer science to technical non-majors
(physics/math/econ students mostly).  Students participated in practical
sessions in the computer lab where they would read a set of instructions and
then proceed to work through projects with us behind them.

The instructions looked like this:

> Today we're covering object oriented programming and classes.  A class looks
> like this:

```python
class Human:
    def __init__(self, name: str):
        self.name = name

    def mate(self, partner: Human) -> Child:
        ...
```

> In our next exercise you will extend this class to ...

And so on.  When I wrote bad instructions, all of the students would have lots
of problems, and the lab was stressful for me.  When I wrote good instructions the
students would be fine and I could relax and joke around with them (scientists
who choose to learn programming are invariably great to be around).

To be clear the difference between "good" and "bad" instructions wasn't in the
content, it was whether or not the student actually read through all of the instructions.

**Teaching is a game where you have to capture someone's attention while
simultaneously shoving knowledge into their brain.**

*Thank you to [Hugo Bowne-Anderson](https://hugobowne.github.io/) for his thoughtful remarks on this post*
