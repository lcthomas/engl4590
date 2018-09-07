---
id: 183
title: Lab 4
date: 2015-12-16T14:15:59+00:00
author: lindsaythomas
layout: page
guid: http://lindsaythomas.net/engl4590/?page_id=183
ample_page_layout:
  - no_sidebar_full_width
---
<a href="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2015/12/Lab-4-ENGL-4590-S16.pdf" rel="">PDF version of this assignment</a>.

### **Lab 4: Corpus Analysis with Antconc**

The goal of this lab is to learn more about Antconc as a tool for analyzing large collections of texts.

I will be introducing the basics of <a href="http://www.laurenceanthony.net/software/antconc/" target="_blank">Antconc</a> in class on Wednesday, February 17. This lab assumes you have learned these basics. If you need more help with basics, you can read through <a href="http://programminghistorian.org/lessons/corpus-analysis-with-antconc" target="_blank">Heather Froehlich&#8217;s Antconc tutorial</a>, published in The Programming Historian, or check out the <a href="http://www.laurenceanthony.net/software/antconc/releases/AntConc343/help.pdf" target="_blank">Antconc help file</a>.

1. The Lab 4 folder in our class Box drive contains a corpus of every State of the Union presidential speech through 2014. We will be using this corpus for this lab. Download the corpus from our Box drive and save it to your computer.

2. First, create a post for Lab 4 on our course site (categorize it under &#8220;Lab 4&#8221;) OR create a document to save locally on your computer that you will eventually copy and paste into your Lab 4 post.

3. Load the State of the Union corpus into Antconc. You may use the entire corpus, or a subset of the corpus. Just make sure you record in your lab report what corpus you used.

4. Using Antconc, find collocates for the word &#8220;future&#8221; (see our course calendar for today for notes on opening Antconc for the first time):

  * Select the Collocates tab.
  * Make sure Words is selected as the Search Term.
  * Set the minimum collocation frequency to 5.
  * Click Start

In your Lab 4 post, record the frequency and stat column values for the bigram “the future.&#8221; Next, record 3 other frequently occurring **AND** statistically significant collocates. This doesn’t have to be an exact top three list, but come as close as you can.

5. Search for clusters of words that contain the word &#8220;future&#8221; (this step asks you to search for bigrams, word clusters composed of two words):

  * Select the Clusters/Ngrams tab.
  * Make sure Words is selected as the Search Term.
  * Make sure “future” appears in the search bar.
  * Set the minimum frequency to 2 or 3.
  * Make sure Cluster Size is set to 2 (min of 2 and max of 2).
  * Make sure On Left is checked under Search Term Position.
  * Click Start. Note your results.
  * Repeat for the right side of the word (select On Right under Search Term Position).

Find the top 3 most frequent bigrams for both the right and left sides of the word “future.” Record them all in your post, with their frequency values. Choose two of these frequently occurring bigrams to use in the next step; make the two bigrams you choose appear bold in your post.

**NOTE:** There are many other ways to search for words or groups of words in Antconc. Read the &#8220;Search Operators&#8221; section of <a href="http://programminghistorian.org/lessons/corpus-analysis-with-antconc" target="_blank">Heather Froehlich&#8217;s Antconc tutorial</a> to get a sense of some of the things you can do.

6. Search for common bigrams containing the word “future”:

  * In the same Clusters/Ngrams tab, click the Ngrams Search Term box.
  * Make sure the minimum frequency is still set to 2 or 3.
  * Select Sort by Word from the Sort by dropdown menu.
  * Click Start.

Find both of the bigrams you chose in the last step and note their frequency in your post. Choose one of these bigrams to use for the next step.

7. Use the Concordance tab to find 3 specific texts where your chosen bigram occurs frequently:

  * Select the Concordance tab.
  * Type the bigram you are searching for the in search box.
  * Make sure Words is selected as the Search Term.
  * Click Start.

Write down the file names of 3 specific documents where your bigram occurs in your post.

8. Explore your top files using the File View tab:

  * Find a file in the Concordance Plot tab that contains a high number of your selected bigram (one that has a high number of hits).
  * Click on one of the vertical lines on this file’s bar (you know when to click because your cursor will turn into a hand that&#8217;s pointing when you&#8217;re over the vertical line).
  * This will take you to the File View, which shows you your bigram in context in this specific file.

Take note of something interesting that this view reveals in your post.

9. Comparing corpora:

  * Read through the &#8220;Comparing Corpora&#8221; section of <a href="http://programminghistorian.org/lessons/corpus-analysis-with-antconc" target="_blank">Heather Froehlich&#8217;s Antconc tutorial</a>. The Keyword tool finds unusually frequent words in the corpus.
  * We will be using the <a href="https://en.wikipedia.org/wiki/Brown_Corpus" target="_blank">Brown corpus</a> as a reference corpus for this part of the tutorial. You can find the Brown corpus word frequency list in the Lab 4 folder of our class Box drive. Download the word frequency list and save it to your computer.
  * To upload the Brown word frequency list to Antconc (these directions are Mac-specific but are similar to what you will do if you have a Windows machine), go to Settings > Tool Preferences > Keyword List. Under Reference Corpus, make sure &#8220;Use raw files&#8221; is checked. Choose &#8220;Add Files&#8221; and select the Brown corpus word frequency list. Select &#8220;Load&#8221; under Reference Corpus, and then once it reads &#8220;Clear,&#8221;  select &#8220;Apply&#8221; to exit the Tool Preferences menu. Navigate to the Keyword List tab in Antconc and click &#8220;Start.&#8221; 
      * See Heather Froehlich&#8217;s tutorial (under &#8220;Comparing Corpora&#8221;) for Windows-specific instructions.
      * See this video for more instruction (and for Windows-specific instructions): <a href="https://www.youtube.com/watch?v=JvasTvQY7kU" target="_blank">https://www.youtube.com/watch?v=JvasTvQY7kU</a>
  * As <a href="http://programminghistorian.org/lessons/corpus-analysis-with-antconc" target="_blank">Heather Froehlich</a> writes, what you see after clicking Start is &#8220;a list of Keywords that are much more &#8216;unusual&#8217; – more statistically unexpected – in the corpus we are looking at when compared to the reference corpus.&#8221; Keyness is a statistical measure of &#8220;the frequency of a word in the text when compared with its frequency in a reference corpus.&#8221; (For more on keyness, see <a href="http://www.lexically.net/downloads/version6/HTML/index.html?keyness_definition.htm" target="_blank">this link</a>).

Take note of **at least 3 expected words APART FROM ARTICLES, PREPOSITIONS, OR CONJUNCTIONS** that appear more often in the State of the Union corpus than in general English-language usage. Then take note of **at least 1 unexpected word APART FROM ARTICLES, PREPOSITIONS, OR CONJUNCTIONS** that appears more often in the State of the Union corpus than in general English-language usage.

10. Write a report that reflects on what you did in Lab 4 and on Antconc and corpus analysis more generally. Some questions you might consider as you compose your report include:

  * How are the State of the Union addresses different in their use of language from &#8220;standard&#8221; American English (as represented by the Brown corpus)? What might these differences tell us?
  * What has Antconc revealed to you about the State of the Union corpus that you didn&#8217;t know before? What are you now intrigued about or interested in that you weren&#8217;t before?
  * What can Antconc and corpus analysis more generally _do_ for researchers in literary studies? What kinds of questions can we use Antconc to answer? You might think about the Mahlberg reading here.
  * What challenges does Antconc present to researchers in literary studies?

You do not need to answer all of these questions in your post; focus on one or two. You do not need to have a central argument (although it’s fine if you have one). The goal of this lab report is to think about corpus analysis more generally and about what tools like Antconc can do for the study of literature.

Shoot for 500-750 words.