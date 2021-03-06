---
toc: true
layout: post
description: A minimal example of using markdown with fastpages.
categories: [resources, Data Anlysis]
title: Data Analysis Resources for Python
---

# Data Analysis Resources for Python

This not mine I just find it on reddit and want to post it here to remind myself where to look


## Introduction

Data Science is an increasingly important tool for companies looking for competitive advantage, and Data Scientist jobs are coveted and often well paid. As a result, the internet is awash with sites and Medium posts dedicated to teaching data science topics, many of which are of questionable value.

This post includes a list of resources which could help start you on the journey to being a data scientist, but focus on data analysis. This means there is little to no machine learning mentioned here, but there is a lot of focus on statistical analysis of data.

## Disclaimer

This post is purely my opinion, and in particular reflects my view that people too quickly jump to ML/DL methods when ‘traditional’ methods could do better. Obviously this is very domain-specific—you’d struggle to generate meaningful text with a linear regression.

Two final points before diving in:

-   There is a lot of content between the sources below; don’t feel you have to read and understand them all by any stretch, but don’t expect to be on top of this stuff in a week or a month. Three months is probably the minimum amount of time required to get a  _feel_  for this, and more like a year to be useful to a third party
    
-   Domain knowledge is super important; if you are interested in a particular industry, read up on that too to make yourself saleable
    

Learning Resources

Python Basics

Nothing here is specific to data analysis, so take a look at the  [r/learnpython FAQ](https://reddit.com/r/learnpython/w/index?utm_source=share&utm_medium=ios_app&utm_name=iossmf).

In general, good data science often looks to the outside observer like software engineering. It’s not enough to build something in a Jupyter notebook and be done (many claim success in “productionising” notebooks, and all are wrong); so you also need to learn about:

-   Version control ([git](https://try.github.io/)  is the de facto standard, and if you understand that you’ll be able to pick another VCS easily enough. Note that IDEs such as PyCharm give a friendly interface to many commands, but you still have to know the basics.)
    
-   [Packaging](http://packaging.python.org/)
    
-   Unit testing (I like  [pytest](https://docs.pytest.org/en/latest/))
    

## Data Analysis

There’s no getting away from the fact that mathematics is at the core of data analysis, but you don’t have to be John Conway to be useful. In addition, statistics is by far the most important at this level and you don’t need to understand the minutiae of the subject (which is based in measure theory and is  _tough_). Unfortunately I’ve never found a good introduction to statistics with Python (there are plenty for R!), so you have to dip into a number of different resources.

[All of Statistics](https://www.stat.cmu.edu/~larry/all-of-statistics/)  ([PDF available here](https://link.springer.com/book/10.1007/978-0-387-21736-9))

Perhaps not  _all_, but Larry Wasserman has written a very approachable introduction to statistics here. The link includes the few data sources given in the book, but it’s very much a textbook. At 500 pages it’s a bit daunting, so I recommend focusing on chapters 1–11 first, then the chapters on linear regression and multivariate models, which is about 200 pages total. Read along with the  [SciPy docs](https://docs.scipy.org/doc/scipy/reference/); in addition take a look at  [pythonfordatascience.org](https://pythonfordatascience.org/inferential-statistics/)  which calls out useful functions in SciPy and statsmodels.

[OpenIntro Statistics](https://www.openintro.org/book/os/)

An alternative (and possibly a better alternative) to AoS, this textbook is available with an optional contribution, and used by a number of colleges in the U.S. I’ve not read it, but a closer look, it appears to be pretty great. As with AoS you’ll have to read along with the SciPy and statsmodels docs.

[Linear Algebra Done Right](https://link.springer.com/book/10.1007/978-3-319-11080-6)

Currently available for free from Springer, this covers a lot of ground in ~300 pages. Less immediately applicable than the stats books, but definitely worth keeping for the future

[Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

Jake VanderPlas is the author of the excellent  [altair](https://altair-viz.github.io/)  plotting library and a pretty bright chap. This book serves as a good introduction to NumPy, Pandas, Matplotlib and Scikit-Learn, and the link includes its full text as Jupyter Notebooks, which is awesome. You needn’t bother with the Scikit-Learn chapters unless you want to jump ahead.

[Python for Data Analysis](http://shop.oreilly.com/product/0636920050896.do)  and the  [pandas docs](https://pandas.pydata.org/docs/user_guide/index.html)

Which of these you prefer is largely a matter of preferring one medium over another, but PfDA’s second edition is already slightly outdated for pandas 1.0.3, though certainly not enough that it’s not a very useful resource.

[Data Science from Scratch](https://www.oreilly.com/library/view/data-science-from/9781492041122/)

Joel Grus’s book kinda  _does_  do what I assert isn’t possible—take you from zero to data scientist hero in a relatively short text. The criticism I would level at it is that it (necessarily) doesn’t go into sufficient depth everywhere, but what it does brilliantly is implement most things from scratch (duh!) to give you a good grounding in the basics.

[Anatomy of Matplotlib](https://youtu.be/6gdNUDs6QPc)

This is a great video to get a better understanding of how to work with Matplotlib, which is definitely the least Pythonic library still in use by data analysts today. It’s also slightly outdated, but hugely valuable.

[Introduction to Survival Analysis — lifelines docs](https://lifelines.readthedocs.io/en/latest/Survival%20Analysis%20intro.html)

Great introduction to survival analysis, which will either help you look like a superstar or be completely irrelevant.

[Winning with simple, even linear models](https://youtu.be/68ABAU_V8qI)

I was at this talk at PyData London a few years ago and it was the best of the conference in my opinion. Vincent makes the argument that people are too quick to leap to ML/DL methods when simpler models could do as well or if not better.

[The Visual Display of Quantitative Information](https://www.edwardtufte.com/tufte/books_vdqi)

If you buy one book on visualisation, it should be this. (If you buy two, it should be this an  _The Grammar of Graphics_)

Data Science

Briefly, here’re a few resources that cover data science proper, but don’t expect to get here any time soon!

-   [r/datascience](https://www.reddit.com/r/datascience/wiki/resources?utm_source=share&utm_medium=ios_app&utm_name=iossmf)  (includes all the other resources in this section)
    
-   [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)  and  [An Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/)  (the former goes into more detail on the maths than the latter)
    
-   [Pattern Recognition and Machine Learning](https://www.springer.com/gp/book/9780387310732)
    
-   [Andrew Ng’s Machine Learning course](https://www.coursera.org/learn/machine-learning)
    

## Data Sources

As mentioned before, if you’re interested in a particular industry then see if you can get data related to it. Otherwise, these are some general sources of good-quality data.

-   [Scikit-Learn data](http://scikit-learn.org/stable/datasets/index.html)  has some really good ‘toy’ datasets that are useful for playing around with descriptive and inferential statistics, besides the skl estimators
    
-   [data.gov.uk](https://data.gov.uk/)  and  [data.gov](https://www.data.gov/)  have hundreds of thousands of data sets. Many of these offer a great opportunity to practice cleaning up data with pandas because they come in all shapes and sizes
    
-   [OpenIntro Statistics](https://www.openintro.org/data/)  data sets used in this textbook
    

Out-of-scope

The following topics haven’t been mentioned in this post yet, because I consider them adjuncts to the main theme, but will probably be of importance:

-   SQL (probably very important!)
    
-   Big data (possibly less so, but in general the problems of big data are about finding efficient ways of doing the same stuff with… big data) inc. e.g. PySpark etc.
    
-   Continuous integration/continuous delivery
    
-   Docker/Kubernetes
    
## for me to check
1. [Learn Numpy the hard way](https://www.kaggle.com/python10pm/learn-numpy-the-hard-way-70-exercises-solutions)
2. [Pandas](https://www.kaggle.com/python10pm/pandas-75-exercises-with-solutions)  
3. [notebooks](https://github.com/donnemartin/data-science-ipython-notebooks)    
4. [Lab Workshops](https://github.com/YaleDHLab/lab-workshops)
5. [Carpentry Data training](https://datacarpentry.org/lessons/)
6. [Software Carpentry](https://software-carpentry.org/lessons/)
7. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
8. [Open Source Society University](https://github.com/ossu/data-science)
9. [Practical Business Python](https://pbpython.com/roadmap.html)
10. [What Can I Do with Python](https://www.goskills.com/Development/Resources/What-can-I-do-with-Python)
11.  Python Crash Course, 2nd Edition,  [https://nostarch.com/pythoncrashcourse2e](https://nostarch.com/pythoncrashcourse2e)
    
12.  YT: Corey Schafer,  [https://www.youtube.com/user/schafer5](https://www.youtube.com/user/schafer5)
    
13.  YT: Data analysis in Python with pandas,  [https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y](https://www.youtube.com/playlist?list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y)
    

Afterwards
 
-   Automate the Boring Stuff with Python, 2nd Edition,  [https://nostarch.com/automatestuff2]https://automatetheboringstuff.com/2e/chapter0/)
    
-   Impractical Python Projects,  [https://nostarch.com/impracticalpythonprojects](https://nostarch.com/impracticalpythonprojects)
    
-   Serious Python,  [https://nostarch.com/seriouspython](https://nostarch.com/seriouspython)
    
-   YT: Bonus: sentdex,  [https://www.youtube.com/c/sentdex/playlists](https://www.youtube.com/c/sentdex/playlists)

These 2 projects can be done in any language but best in python. And they make money! Only if you are smart though. There’s no way to make money only knowing how to code, unless you get a coding job. You need to know some marketing, some finances, some analytics, etc. Coding has absolutely nothing to do with money, so don’t assume one day things will just click and you’ll be able to code a tree made of money.

Here are the projects:

-   Web Scraper - Data is the new gold. You can scrape anything off of any website and sell it to people. There’s plenty of public data sets, data etc. You could even scrape quora answers to see which words/phrases are more likely to get more upvotes. The possibilities are endless. Cant remember the library for python for http requests, i think its called ‘requests’
-   Price Matcher - This is similar to a web scraper, but a little less scraping and a little more marketing. Find the same item on different sites and match the prices in order to find the cheapest deals. Send them to your subscribers. This gets difficult as stores have daily deals, customers live in different areas (meaning different shipping costs), etc.

Both of these can be monetized. Both will also prepare you for a straight up job writing python.
