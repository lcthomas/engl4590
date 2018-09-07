---
id: 1259
title: Lab 7
date: 2016-03-17T15:13:06+00:00
author: lindsaythomas
layout: page
guid: http://lindsaythomas.net/engl4590/?page_id=1259
ample_page_layout:
  - no_sidebar_full_width
---
<a href="http://lindsaythomas.net/engl4590/wp-content/uploads/sites/10/2016/03/Lab-7-ENGL-4590-S16.pdf" rel="">PDF version of this assignment</a>.

### Lab 7: Data Visualization

Thanks to <a href="http://www.miaridge.com/resources-for-data-visualisation-for-analysis-in-scholarly-research/" target="_blank">Mia Ridge</a> for the original version of this lab.

Over the course of the semester, we have used various data visualization techniques in our other labs without really thinking much about it. We&#8217;re now going to take a step back and think in more detail about data visualization itself, and about what different data visualization techniques and types can tell us, and what they can&#8217;t. The goal of Lab 7 is to reflect on different kinds of data visualizations and to gain some hands-on experience with data visualization tools.

**NOTE: **A helpful resource for this lab is Jeffrey Heer, Michael Bostock, and Vadim Ogievetsky&#8217;s <a href="http://homes.cs.washington.edu/~jheer//files/zoo/" target="_blank">&#8220;A Tour Through the Visualization Zoo</a>.&#8221;

1. Create a post on our course site for Lab 7 (categorize it under &#8220;Lab 7&#8221;). This is where you will post the souvenirs you collect from the lab and where you will write your lab report.

**NOTE: **The written component of this lab report is built into the lab itself (rather than appearing as a separate step at the end). Steps 2 &#8211; 5 of the lab ask you to experiment with various visualization tools and then to write up short analyses of these tools. **Shoot for about 1 paragraph for each analysis. **The TOTAL word count for this post &#8212; including all of these separate analyses &#8212; should therefore be about 500-750 words, although honestly I think 500 words is a bit slim for this lab.****

2. Comparing N-gram tools: In Lab 2, we experimented with Voyant, which has a built-in word frequency visualization tool. Another popular word frequency visualization tool is Google&#8217;s N-grams tool. Historian Ben Schmidt has also created a similar word frequency analysis tool. This part of the lab asks you to compare these two tools.

<ol type="i">
  <li>
    Think of two words or phrases you&#8217;d like to compare over time.
  </li>
  <li>
    Open two browser windows.
  </li>
  <li>
    In one, go to <a href="http://books.google.com/ngrams" target="_blank">http://books.google.com/ngrams</a>.
  </li>
  <li>
    In the other, go to <a href="http://benschmidt.org/OL/" target="_blank">http://benschmidt.org/OL/</a>.
  </li>
  <li>
    Enter your chosen words or phrases in each. In the Bookworm tab, make sure you are searching for two words/phrases (i.e., you should see two lines on the graph), and that you are searching for books written in English (UK and USA). Also make sure that you remove any subject or book categories.
  </li>
  <li>
    Take a screenshot of the time-series graph created with each tool. Upload these screenshots to your Lab 7 post with brief explanations of what each graph depicts.
  </li>
  <li>
    Write up a brief analysis and comparison of these two visualizations in your lab report. These graphs are both showing the frequency of your chosen words/phrases over time, but what differences do you see? How are these graphs/tools different? Why might these differences be important? More broadly, how might humanists utilize and/or re-imagine time series graphs to foreground humanistic, interpretive principles, as Drucker and Klein argue for?
  </li>
</ol>

Google Ngram tips: <a href="http://books.google.com/ngrams/info" target="_blank">http://books.google.com/ngrams/info</a>
  
Bookworm tips: click the &#8216;cog&#8217; icon next to the &#8216;i&#8217; to change the time period or click the
  
underlined words next to the search term to change which books are searched (e.g.
  
subject, language, country, gender of author). You can also compare the same word or
  
phrase in a different corpus.

3. Visualizing topic models: In Labs 5a and 5b, we experimented with topic modeling. <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos</a> allows you to visualize topics in an interesting and easy way. This part of the lab asks you to use Lexos to visualize topic modeling data.

<ol type="i">
  <li>
    Our class Box folder (in the &#8220;Lab 7&#8221; folder) contains a file called &#8220;sotu-word-topic-counts.txt.&#8221; This is a kind of file that MALLET can give you. It is a list of the words in the State of the Union Addresses corpus and all of the topics to which they are assigned. Download this file and save it on your computer in some place that is easily accessible (like your Desktop).
  </li>
  <li>
    Go to <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos</a>.
  </li>
  <li>
    Under &#8220;Visualize,&#8221; select &#8220;Multicloud.&#8221;
  </li>
  <li>
    Click the slider under &#8220;Multicloud Options&#8221; so that &#8220;Topic Clouds&#8221; is displayed.
  </li>
  <li>
    Click the box that reads &#8220;Convert Topics to Documents.&#8221;
  </li>
  <li>
    Upload the &#8220;sotu-word-topic-counts.txt&#8221; file by clicking &#8220;Upload File.&#8221;
  </li>
  <li>
    Click &#8220;Get Graphs.&#8221;
  </li>
  <li>
    Take a screenshot of at least one of the topic word clouds and upload it to your lab report. In your Lab 7 post, write a brief analysis of what this tool allows you to see and why this might be useful. What is this a visualization of? And what are the advantages/disadvantages of this kind of visualization? Does the visualization open up new questions about the data? More broadly, are word clouds &#8220;humanistic&#8221; graphical displays, according to how Drucker and/or Klein uses that term? Why or why not? How might we re-imagine this form of graphical display to foreground humanistic, interpretive principles?
  </li>
</ol>

**NOTE:** If you want a challenge, you can create a word-topics count file using MALLET yourself. Create a topic model of your mini-corpus (like we did in Lab 5b). To get a word-topics count file, include this command in your train topics command:

&#8212;-word-topic-counts-file filename.txt

(That is a double dash before &#8220;word.&#8221; Remember, every MALLET command starts with a double dash.)

4. Network visualizations: In Lab 6, we experimented with network analysis. Let&#8217;s look at network visualizations more closely.

<ol type="i">
  <li>
    In your browser, go to <a href="http://fredbenenson.com/2012/12/05/the-data-behind-my-ideal-bookshelf/" target="_blank">http://fredbenenson.com/2012/12/05/the-data-behind-my-ideal-bookshelf/</a>
  </li>
  <li>
    Scroll down the page to the network graph.
  </li>
  <li>
    Take a few minutes to explore the visualisation: try holding the cursor over<br /> items, clicking, dragging, etc.
  </li>
  <li>
    In your Lab 7 post, write a brief analysis of this visualization. Is it clear what it&#8217;s for? Is it intuitive to use? What does &#8220;intuitive&#8221; mean in this case? Does interacting with the network graph give you more or less information than the other representations of the data further down on the same page? Does the visualization open up new questions about the data? More broadly, how might humanists utilize and/or re-imagine time series graphs to foreground humanistic, interpretive principles, as Drucker and Klein argue for?
  </li>
</ol>

5. Creating your own simple visualizations using Google Fusions: Google Fusions gives you lots of options for easily creating different kinds of visualizations with your own data.

<ol type="i">
  <li>
    Our class Box folder (in the &#8220;Lab 7&#8221; folder) contains a file called &#8220;Tate_artists_percountry.xlsx&#8221; based on data from the UK&#8217;s <a href="http://www.tate.org.uk/" target="_blank">Tate art museums</a>. Download this file and save it on your computer in some place that is easily accessible (like your Desktop).
  </li>
  <li>
    Go to <a href="https://drive.google.com/" target="_blank">https://drive.google.com/</a> and log into your Google account (contact me if you don&#8217;t have a Google account).
  </li>
  <li>
    Go to <a href="http://bit.ly/Xw0zNJ" target="_blank">http://bit.ly/Xw0zNJ</a> (or<br /> <a href="https://www.google.com/fusiontables/data?dsrcid=implicit" target="_blank">https://www.google.com/fusiontables/data?dsrcid=implicit</a>) to access Fusion<br /> Tables from your account.
  </li>
  <li>
    You should see a screen &#8220;Import new table&#8221; with the option called &#8220;From this<br /> computer&#8221; highlighted .
  </li>
  <li>
    Click &#8220;Choose file&#8221; and select Tate_artists_percountry.xlsx. Click &#8220;Next.&#8221;
  </li>
  <li>
    Click &#8220;Next&#8221; on the next screen, then click &#8220;Finish&#8221; on the following screen. <ol>
      <li>
        If you want to fill in the options on the Import screen you can update them as follows: untick &#8220;Allow export.&#8221; For &#8220;Attribute data to&#8221; put &#8220;Tate&#8221; and for Attribution page link put<br /> <a href="http://www.tate.org.uk/about/our-work/digital/collection-data" target="_blank">http://www.tate.org.uk/about/our-work/digital/collection-data</a>.
      </li>
    </ol>
  </li>
  
  <li>
    The screen should load in &#8220;Row&#8221; view, which looks something like a spreadsheet<br /> with two columns.
  </li>
  <li>
    At the end of the row of menu options, there should be a red box with a plus sign<br /> in it. Click that, then select &#8220;Add chart.&#8221;
  </li>
  <li>
    Scroll down the left-hand side to find the Pie Chart option. Click the Pie Chart<br /> image.
  </li>
  <li>
    On the &#8220;Configure pie chart screen,&#8221; check that the Category is set to<br /> CountryOfBirth and Value is set to Number of artists.
  </li>
  <li>
    Change &#8220;Maximum slices&#8221; to 80.
  </li>
  <li>
    Click &#8220;Done'&#8221;(over on the right-hand side), you should have a pie chart of your data!
  </li>
  <li>
    Take a screenshot of this pie chart and upload it to your Lab 7 post. Include a brief description of what information this visualization is displaying. Explore some of the other chart and graph options Google Fusions gives you, and then write up a brief analysis of how we could use Google Fusions in our final class project. What kind(s) of data could we visualize using this tool? More importantly, why might we want to do it? And more broadly, is there a way to use Google Fusions to foreground humanistic, interpretive principles, as Drucker and Klein argue for?
  </li>
</ol>