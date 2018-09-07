---
id: 1248
title: 'Lab 5b&#8211;Thomas'
date: 2016-03-11T20:11:20+00:00
author: katet
layout: post
guid: http://lindsaythomas.net/engl4590/?p=1248
permalink: /2016/03/11/lab-5b-thomas/
ample_page_layout:
  - default_layout
categories:
  - Lab 5b
---
Topic modeling is the “statistical technique for inferring the distribution of topics in a given corpus. Another way of saying this is that topic modeling is a method of finding out what words are likely to occur together across and entire corpus. humans interpret these lists of words as being related to each other in some way we read them as. Topics (in topic modeling) consist of a collocation on a much larger scale. They are lists of words that are likely to occur together across an entire corpus. Topic modeling allows for researchers in literary studies to see what words go together consistently. This paves the way for a sort of knowledge about the text without even reading it. With topic modeling, you are able to look across an entire corpus for these topics, not just a singular document. What this tells us is what these certain texts have in common and how they relate to each other. If we were only able to see one document, we would have a limited amount of access to the knowledge of the texts but with the ability to see the topics within an entire corpus we can see on a much larger scale, as stated earlier.

&nbsp;

This lab was very difficult for me and I faced many challenges through the duration of it. A lot of the time I got very frustrated with the terminal and mallet. When we were going through it together in class, I could do it. It took awhile and I made a lot of mistakes on the way but I could do it. But when I tried to sit down and do it myself, I wasn’t really getting it. I pulled up terminal and tried to do the command to import my own data: “./bin/mallet import-dir –input /users/admin/mallet/corpus –output corpus.mallet –keep-sequence –remove-stopwords” is what I originally tried. When that didn’t work, I tired a lot of different things. I tried for about an hour. I’m not really sure if I was typing the command in wrong or if I wasn’t in the right place or there was a typo. I don’t know. So, when this wasn’t working I decided to do some topic modeling of my corpus in the Topic Modeling Tool that we had downloaded last week. So for the lab, I am going to show some screen shots of my topic modeling of my corpus and how I looked at different numbers of topics. I am going to turn in a folder with the screen shots and everything that I did with Mallet in class. I hate that I couldn’t get Mallet and the commands working and I hope that this is okay.

First, I tried looking for ten topics.

<a href="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.40.05-PM.png" rel="attachment wp-att-1249"><img class="alignnone size-medium wp-image-1249" src="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.40.05-PM-300x269.png" alt="Screen Shot 2016-03-11 at 7.40.05 PM" width="300" height="269" srcset="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.40.05-PM-300x269.png 300w, http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.40.05-PM.png 767w" sizes="(max-width: 300px) 100vw, 300px" /></a>

Then, I went lower and tried five.

<a href="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.43.05-PM.png" rel="attachment wp-att-1250"><img class="alignnone size-medium wp-image-1250" src="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.43.05-PM-300x268.png" alt="Screen Shot 2016-03-11 at 7.43.05 PM" width="300" height="268" srcset="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.43.05-PM-300x268.png 300w, http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.43.05-PM-768x687.png 768w, http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.43.05-PM.png 769w" sizes="(max-width: 300px) 100vw, 300px" /></a>

Then, I tried looking for 25 topics.

<a href="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.44.05-PM.png" rel="attachment wp-att-1251"><img class="alignnone size-medium wp-image-1251" src="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.44.05-PM-300x268.png" alt="Screen Shot 2016-03-11 at 7.44.05 PM" width="300" height="268" srcset="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.44.05-PM-300x268.png 300w, http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.44.05-PM-768x685.png 768w, http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Screen-Shot-2016-03-11-at-7.44.05-PM.png 769w" sizes="(max-width: 300px) 100vw, 300px" /></a>

As you can see the list gets much longer as you add how to how many topics you want to look for. I still get confused as to how the lists and numbers of topics fit together. I get that the list gets longer but sometimes I&#8217;m still not sure I really get what this means. I think that this means that you are telling the tool how many topics to look for so it gets bigger because of that reason. So, if we look for a smaller amount of topics the corpus would be narrowed down more and we would get a better sense of what words are more likely to go together.