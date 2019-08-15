# Text Analysis With AntConc

This tutorial was written by <a href="https://www.grinnell.edu/users/waldenka">Katherine Walden</a>, Digital Liberal Arts Specialist at Grinnell College. The tutorial framework was created by Sarah Purcell (L.F. Parker Professor of History, Grinnell College) and Papa Ampim-Darko, a student research assistant at Grinnell College

This tutorial was reviewed by <a href="https://www.grinnell.edu/users/donovang">Gina Donovan</a> (Instructional Technologist. Grinnell College).

This tutorial is adapted from the Programming Historian’s <a href="https://programminghistorian.org/en/lessons/corpus-analysis-with-antconc">Corpus Analysis with AntConc tutorial</a>.

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
Text Analysis in AntConc is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

<hr />

Developed by Laurence Anthony, <a href="http://www.laurenceanthony.net/software/antconc/">AntConc</a> is a free, closed-source program that runs on Windows, OS, and Linux. At the most basic level, AntConc is a concordancer, or a program that constructs a concordance based on terms in a text or collection of texts. AntConc also allows users to visualize concordance calculations and generate word and keyword lists based on terms present in the text. AntConc also supports cluster and collocation analysis and visualization. With Voyant, we explored a graphical user interface option for conducting textual analysis. AntConc offers a somewhat more hands-on, customizable approach to analyzing a text.

<hr />

## Data

Download the Files compressed folder in this repository. Extract the contents to a folder on your Desktop.

<hr />

## Downloading AntConc

If you want to work with AntConc on your own computer, <a href="http://www.laurenceanthony.net/software/antconc/">select the appropriate version</a> for your operating system and following the installation instructions.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_1.PNG?raw=true"><img class="aligncenter size-full wp-image-583" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_1.PNG?raw=true" alt="" width="790" height="592" /></a></p>

1-<strong>Launch AntConc</strong> by double clicking on the Desktop icon or searching for the program in the Start menu.

<hr />

## Data

2-AntConc allows you to open <strong>single files</strong>, as well as open an entire <strong>file directory</strong>. For this tutorial, we will be working with a large number of S&amp;B text files, so opening the directory makes more sense than loading these files individually.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_2.PNG?raw=true"><img class="aligncenter size-full wp-image-584" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_2.PNG?raw=true" alt="" width="790" height="594" /></a></p>

3-Select <strong>File-&gt;Open Dir</strong> and navigate the Desktop folder where you put the S&B files.  Click <strong>OK</strong>.

4-The loaded files will be listed on the left-hand window in AntConc, and the total number of files will display at the bottom of that window.

<hr />

## AntConc’s Functionality

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_3.PNG?raw=true"><img class="aligncenter size-full wp-image-585" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_3.PNG?raw=true" alt="" width="551" height="35" /></a></p>

5-The main AntConc screen gives you access to seven different textual analysis tools.

<ul>
 	<li>Concordance searches for and displays keywords in context (KWIC).</li>
 	<li>Concordance Plot presents a preliminary, basic visualization of a KWIC search.</li>
 	<li>File View is like the Reader panel in Voyant—it shows you a full file view to see a search result in the larger context of a text.</li>
 	<li>Clusters highlights terms that appear together frequently in the text.</li>
 	<li>Collocates calculates the statistical likelihood of terms appearing together in the text. Clusters looks for term patterns as they are represented in the text. Collocates looks at the likelihood of terms appearing together in the text.</li>
 	<li>Word List calculates how frequency words appear in your text.</li>
 	<li>Keyword List compares keywords from two text sources (a reference text and an analysis text).</li>
</ul>

<hr />

### Searching Keywords in Context

6-AntConc (and other computing tools) excel at identifying patterns in language that are not always detected by the average reader. For example, function words like <em>a, an, the, he, she, I,</em> etc. (often called stopwords in textual analysis) don’t frequently catch our attention as readers. A computational tool focuses on analyzing the words as term objects, rather than interpreting them based on meaning, context, or function.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_4.PNG?raw=true"><img class="aligncenter size-full wp-image-586" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_4.PNG?raw=true" alt="" width="789" height="593" /></a></p>

7-<strong>Type “the” in the Search Term box</strong> at the bottom of the <strong>Concordance </strong>window and click <strong>Start</strong>.

8-The <strong>Concordance tab</strong> shows key words in context (KWIC), with the search term highlighted.

9-The <strong>Kwic Sort</strong> options allow you to change how AntConc displays or sorts the context for your search term. 1R includes the term immediately to the right of your search term, 2R includes the second term to the right from your search term, etc. 1L includes the term immediately to the left of your search term, 2L includes the second term to the left from your search term, etc.

10-<strong>Change the Kwic Sort options</strong>, and click on the <strong>Sort icon</strong>. How did your search results change? What happens if you continue to customize or edit the Kwic Sort options? How do you understand a key word differently based on how you tell the program to calculate context?

<hr />

### Visualizing Keywords in Context

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_5.PNG?raw=true"><img class="aligncenter size-full wp-image-576" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_5.PNG?raw=true" alt="" width="790" height="595" /></a></p>

11-Search for a <strong>"ball"</strong> in the <strong>Concordance Tab</strong>.

12-Once your search has loaded, click on the <strong>Concordance Plot tab</strong> to visualize your search results.

13-Each instance of the keyword is represented as a vertical black line. AntConc visualizes how keyword appearances are distributed across each file in the Corpus Files.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_6.PNG?raw=true"><img class="aligncenter size-full wp-image-577" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_6.PNG?raw=true" alt="" width="791" height="598" /></a></p>

14-Clicking on a specific line takes you to that passage of the text in <strong>File View.</strong>

15-How useful do you find these preliminary visualizations? How do they compare to the types of visualizations generated on Voyant? How do these visualizations impact your understanding of the text? What questions do you have based on these visualizations?

<hr />

### Search Operators

16-If you’re familiar with Boolean searching, you know symbols can be used in a search to customize or focus your search results. AntConc uses a series of wildcard operators to allow you to further customize your search.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_7.PNG?raw=true"><img class="aligncenter size-full wp-image-578" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_7.PNG?raw=true" alt="" width="788" height="579" /></a></p>

17-Go to <strong>Global Settings-&gt; Wildcard Settings</strong> to view or edit the full list of available wildcard operators.

18-Search for m?n and wom?n and compare your results.
<blockquote>Note on operators:

The * operator is often used in Boolean searching. The ? operator is more specific because it stands in for only one character. For example, searching m*n will bring back results that include men, mean, mellon, etc. Searching m?n  will return men, man, and min. Similarly, wom?n will return woman and women.</blockquote>

<hr />

### Clusters and N-Grams

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_8.PNG?raw=true"><img class="aligncenter size-full wp-image-579" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_8.PNG?raw=true" alt="" width="791" height="597" /></a></p>

19-Click on the <strong>Clusters/N-Grams tab</strong> and search for sport.

20-AntConc ranks your search results, calculates frequency, and range (number of files in which the cluster appears), while also displaying the text in the cluster.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_9.PNG?raw=true"><img class="aligncenter size-full wp-image-580" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_9.PNG?raw=true" alt="" width="790" height="595" /></a></p>

21-The default <strong>Search Term Position</strong> places the search term on the left side of the cluster. <strong>Change the Search Term Position</strong> selection to <strong>On Right</strong> and click <strong>Start</strong> to re-run the search. How did your search results change?

22-<strong>Cluster Size</strong> determines the range for the number of terms AntConc searches and displays. How are your search results different when you change this range?

<hr />

## Exporting in AntConc

23-After you are satisfied with a search result, click <strong>File-&gt;Save Output</strong> to save the search result as a text file (*.txt).

24-Save the file as [SEARCH TERM]_cluster_search or another descriptive name.

25-<strong>Conduct another Cluster search</strong> for study, customize your results, and export as a text file.

26-<strong>Right click</strong> on the exported text files and <strong>open</strong> in Notepad or Notepad++ to compare search results.

<hr />

## Collocates and Word Lists

27-As mentioned earlier in the tutorial, <strong>Clusters</strong> analyzes what words appear most frequently alongside your search term.

28-<strong>Collocates</strong> calculates what terms are statistically probable to appear near your search term. <strong>Freq</strong> calculates overall frequency, <strong>Freq(L)</strong> looks at frequency for terms to the left of your search term, and <strong>Freq(R)</strong> calculates frequency for terms to the right of your search term. <strong>Stat</strong> uses the Mutual Information (MI) and T-score calculations outlined in Stubbs (1995) to calculate the statistical probability of term collocation.

<p align="center"><a href="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_11.PNG?raw=true"><img class="aligncenter size-full wp-image-582" src="https://github.com/kwaldenphd/AntConc-tutorial/blob/master/screenshots/Capture_11.PNG?raw=true" alt="" width="791" height="597" /></a></p>

29-Use the name of a historic campus building as your search term.

30-AntConc will display a pop-up window message about needing to generate a Word List. <strong>Click OK</strong> to have AntConc generate that list automatically.

31-What terms are statistically likely to appear in proximity to your search term? What happens when you change the <strong>Window Span</strong> (number of words to the right and left of your search term AntConc will include in the analysis)?

<hr />

# Reflection Questions:

<ul>
 	<li>What do you notice is similar about Voyant Tools and AntConc as digital tools for textual analysis? What are the differences?</li>
 	<li>Which did you prefer working with? Why?</li>
 	<li>How was your understanding of the text impacted by the analysis we did in AntConc? What questions do you still have?</li>
 	<li>What would be your next step in continuing the textual analysis of S&amp;B issues, using Voyant or AntConc?</li>
 	<li>What types of historical research questions can you see textual analysis being useful to answer or respond to?</li>
</ul>
