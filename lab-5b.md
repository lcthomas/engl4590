---
id: 175
title: Lab 5b
date: 2015-12-17T16:29:26+00:00
author: lindsaythomas
layout: page
guid: http://lindsaythomas.net/engl4590/?page_id=175
ample_page_layout:
  - no_sidebar_full_width
---
<a href="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2015/12/Lab-5b-ENGL-4590-S16.pdf" rel="">PDF version of this assignment</a>.

### **Lab 5b: Topic Modeling with MALLET**

The goal of this lab is to experiment with the most popular topic modeling tool, MALLET.

For this lab, you will follow along with the excellent Programming Historian tutorial &#8220;<a href="http://programminghistorian.org/lessons/topic-modeling-and-mallet" target="_blank">Getting Started with Topic Modeling and MALLET&#8221;</a> by Shawn Graham, Scott Weingart and Ian Milligan.

1. We will download and install MALLET in class together on Wednesday, March 2, following the instructions in the above tutorial.

  * You will need to be at least somewhat familiar with file path names and how to use them in the command line in order to use MALLET successfully (this is what we discussed in class on Monday, Feb 29). Read through this information about absolute file paths for <a href="http://www.mactips.info/2011/11/how-to-read-and-write-a-filepath" target="_blank">Mac machines</a> and <a href="http://demo.mavrosxristoforos.com/relative-and-absolute-file-paths" target="_blank">Windows machines</a> if you&#8217;re not familiar with the concept. You should set up MALLET in its own folder, named &#8220;mallet&#8221; and located in your user directory (Mac) or directly in your C:\ directory (Windows). This will help you to follow along more easily with the tutorial. My username on my Mac is lindsaythomas, so the absolute file path for MALLET on my machine looks like this: **/Users/lindsaythomas/mallet** (you do not have to include Macintosh HD as part of the file path). On a Windows machine, it would look like this: **C:\mallet**. You will need to know this file path in order to import and export files in MALLET.
  * In order to run MALLET commands, you need to first navigate to your mallet folder via the command line. You must be &#8220;in&#8221; your mallet folder in order to run MALLET.

2. Read and follow along with the rest of the <a href="http://programminghistorian.org/lessons/topic-modeling-and-mallet" target="_blank">Programming Historian MALLET tutorial</a>. Make sure to work through each step as it&#8217;s described in the tutorial (Except one: you DO NOT need to increase your heap space &#8212; described in the section &#8220;Issues with Big Data&#8221; &#8212; unless you get the error message described there). Take note of two things about the code windows provided in the tutorial: many of them have horizontal scroll bars; and you will need to include your specific file path in many of the commands. Please note that they are also organized by operating system. Mac users, remember that Macs use forward slashes ( / ), not backslashes ( \ ), in file paths. Mac users, remember also that MALLET commands on a Mac **must** begin with ./bin/mallet (for Windows machines, it&#8217;s bin\mallet).

3. Upload your own files into MALLET and produce your own topic model, based on the steps described in the Programming Historian tutorial. If you completed Lab 3, use the mini-corpus you created for that lab. If you didn&#8217;t complete Lab 3, use the State of the Union addresses corpus we used for Lab 4 (or part of that corpus). If you get the hang of it, you might play around with producing models with different numbers of topics.

4. Create a folder on your desktop (or wherever you keep work for this course on your machine) and title it like this: YourLastName-Lab5b. Save the following souvenirs from step 3 in your Lab5b folder:

  * Your keys file (make sure to save the keys file for your corpus, NOT the keys file from the tutorial, in this folder)
  * Your composition file (again, make sure to save YOUR composition file, NOT the tutorial one, in this folder)

5. Upload your Lab5b folder to our class Box drive (upload it to the &#8220;Lab 5b&#8221; folder).

6. Create a post on our course site for your Lab 5b lab report (categorize it under &#8220;Lab 5b&#8221;). Write a report that begins to interpret the topic model you made in step 4 of this lab and that reflects on this interpretive process itself. Some questions you might consider as you compose your report include:

  * Which texts did you model for step 4 of this lab? How many topics did you choose to model? Why did you choose that number?
  * What challenges did you face in modeling your own corpus?
  * Which topics appear to be most coherent? Why are these topics coherent?
  * Which topics appear to be less coherent or are confusing at first glance?
  * What does topic modeling tell us about your corpus?
  * What does topic modeling _do_ for researchers in literary studies? Why might we want to do it? What kinds of questions does it allow us to answer?

You do not need to answer all of these questions in your post; focus on those about which you have the most to say. You do not need to have a central argument (although it’s fine if you have one).

Shoot for 500-750 words.