---
id: 1238
title: MALLET and Topic Modelling
date: 2016-03-11T18:08:15+00:00
author: tannerm
layout: post
guid: http://lindsaythomas.net/engl4590/?p=1238
permalink: /2016/03/11/mallet-and-topic-modelling/
ample_page_layout:
  - default_layout
categories:
  - Lab 5b
---
Topic modelling still seems a bit abstract to me. I understand what the figures represent on a mathematical scale, but I cannot quite wrap my head around what exactly the topics represent. Perhaps I can work that out here. Lab 5b demonstrates the back-end of the graphs and figures we have gone over in class. It demonstrates the processes that GUIs simplify and presents a few new aspects of the process itself. First, while using a command interface might seem to be a complex task, we can see how many more tasks MALLET must run through after we type in a few lines of code.

In my particular usage of MALLET, I ran my corpus of fantasy novels through three separate times. Using 25, 20, and 15 topics, the average time it took to produce the two plain text files was 47 seconds. If we compare that to time it takes many of the programs we use daily to run through a few operations, we can see that what is going on is quite complex. Not only must the computer read through the textual data, it also must attempt to decipher it within the set parameters. This by no means says that the computer performs this particular task slowly. If we look at the time it would take ten individuals to come to an equally viable conclusion, we can see how a 47 second process is far less than a blip in time.

However, I must now interpret this data. **That** is the difficult task. I initially chose 20 topics because that&#8217;s what the tutorial called for. It wasn&#8217;t adventurous enough, so I chose 25. 25 topics created many topics with numbers under .01, so I settled on 15 topics. While there definitely exist many topics within the eight books in my corpus, 15 topics creates a list that never sees an individual topic go below .01729. This data led me to interpret this list that as one that contains topics with greater significance than that of 20 and 25 topics. However, I get a smaller spectrum of topics, perhaps limiting their variability.

As I stated earlier, the products of this lab seem a bit abstract. When I typically deal with numbers, they have an obvious set of conclusions attached to them. Here, I must come to my own conclusions. Were I still within the field of engineering, this would mean I have done something very wrong, but since most things in literary studies are subjective interpretations, I won&#8217;t stress so much. If we look at the most common topics, 1 and 13 (I&#8217;ve disregarded topic 9 because it seems to be the Gutenberg introduction piece in every novel), sitting at 0.36847 and 0.31747 respectively, we can note certain trends that make a good bit of sense. Both of these topics seem to be concerned with death, family, and heroism, which in the realm of fantasy is quite common. When I look at these results and how they sit within the fantasy genre as a whole, topic modelling becomes a bit less abstract. Now, I have a sense of what this does for those who use it in literary studies. In this particular instance, at least, it allows us to see what might define a genre as a whole. This harkens back to the articles that discussed the importance of discovering what is written in the multitude of literature that remains unread. Ultimately, I can see this as a fantastic tool for those who wish to pursue the deeper meanings that become ingrained in specific societies or the pieces that somehow stretch across boundaries and permeate the works of multiple cultures.

**Topic 1**

blood die father hands sword loved wise lands slain rode pity true thy mercy high white mother riding faith truth

**Topic 13**

people earth continued big air began moment beautiful mother body order replied decided appeared scarcely person wouldn&#8217;t king bad attention

&nbsp;

&nbsp;