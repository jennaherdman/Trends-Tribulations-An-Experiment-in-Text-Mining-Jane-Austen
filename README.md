<h1>Welcome!</h1> 


This project applies tools from the digital text-mining platform Voyant to four Jane Austen novels, and critiques the effectiveness, accessibility, and scholarly potential of these applications. In doing so, I experiment with what N. Katherine Hayles called the “porous boundaries” of human interpretation and machine pattern recognition (73) by analyzing patterns of romance in the novels. Nineteenth-century texts are often available for free download and are rich resources for experimenting with text mining tools, and Jane Austen’s status as a literary giant within the canon means that she is a useful resource upon which to experiment with new methodologies. In this analysis, I ask: does this visualization contribute anything to Austen scholarship and, if so, could this research be used for pedagogical purposes? Is this experiment an example of an Austen scholar becoming more “digitally literate,” or does it detract from traditional methods of close reading and analysis?


<h2>Why Text Mine Austen?</h2>

tldr;

* well-known, canonical works
* texts freely available for download and manipulation using Project Gutenberg 
* scholarly and pedagogical importance - how can we keep students interested in reading and analyzing Austen? 

[Voyant, an open-access program directed by Stéfan Sinclair and Geoffrey Rockwell](http://docs.voyant-tools.org/tools/), comprises of several text mining and visualization tools. When conceptualizing this experiment, I built on a previous project in which I used Voyant’s Terms, Knots, and Bubblelines tools to trace the recurring appearances of minor characters in Charles Dickens’s David Copperfield ([Herdman “Text-mining”](https://jennaherdman.gitbooks.io/a-digital-humanities-primer-for-english-students/
content/Text%20Analysis%20Assignment.html)). Though these results were experimental and not conclusive, I argued that the tools offered a useful way of manipulating the text and of visualizing research questions. Here, I apply this method to Austen novels <i>Pride and Prejudice</i>, <i>Sense and Sensibility</i>, <i>Northanger Abbey</i>, and <i>Mansfield Park</i> by producing term frequency charts which represent the romantic heroes and rivals of each novel. Austen’s romances rely on the protagonist rejecting the “wrong” suitor in favour of the “right” man: for example, in <i>Pride and Prejudice</i> and <i>Sense and Sensibility</i>, the heroine can only recognize the worthiness of her future husband when he has demonstrated the immoral nature of his rival. In <i>Northanger Abbey</i> and <i>Mansfield Park</i>, the wrong suitor is never a real contender for the heroine’s hand, though he must be revealed to be inferior in order for the heroine to go on to marry the hero. I predicted that there would be similar patterns in each of these two pairs of novels based on their similar plot lines, and that the hero would be more dominant than his rival in each graph.

In order to graph the romantic rivalries, I used the Terms tool to look at the frequencies of each male competitor’s name, going on the assumption that a high frequency of the character’s name signifies his importance to the protagonist or the text. Using term frequencies to track plot development in Austen is challenging, however, because it requires a close knowledge of the names that the author uses to refer to each character. The suitor’s name might appear not even when he is absent if the characters are talking about him. Consider, for example, how Mrs. Bennet talks a great deal about Mr. Bingley’s arrival in Meryton before he even appears as a character. When using these tools, then, a mention of the suitor’s name has equal weight in the graph as do his actual actions. Thus, this method requires thinking about each mention of the character as a sign of his importance to the text. Furthermore, the algorithms to measure these text frequencies require pre-existing knowledge of the text’s semantics. For example, in Pride and Prejudice, Darcy is usually referred to as “Mr. Darcy,” as opposed to his first name. Also his sister is called “Miss Darcy” in the novel, and simply searching for their last name would skew the results. Likewise, in Mansfield Park, Fanny’s main love interest, Edmund Bertram, is her cousin, and thus is usually called by his first name, while his brother Tom is more commonly called “Mr. Bertram: searching for the term frequency of “Mr. Bertram” would thus not represent Edmund at all.

<h2>Google Ngram graph</h2>

tldr;

* codex is mysterious: represents the relative frequencies of a term or a phrase in all of the books published that year and that are archived on Google books 
* we must interrogate the archive itself - what is excluded? 

Google Ngrams is a tool created for mining the Google Books corpus for linguistic data. Basically, you can search for a word, or several words, in Google Ngrams, and it will show you the frequencies of that word across the entire digitized corpus. Arguably, this tool can be used to trace the evolution of language, such as the popularity of certain words. 


![Fig. 1: Austen Trends](https://github.com/jennaherdman/Austen-text-mining/blob/master/unspecified.jpeg?raw=true)

[Follow this link for an interactive version of this graph](https://books.google.com/ngrams/graph?content=Northanger+Abbey%2CPride+and+Prejudice%2CSense+and+Sensibility%2CMansfield+Park&year_start=1800&year_end=2010&corpus=15&smoothing=3&share=&direct_url=t1%3B%2CNorthanger%20Abbey%3B%2Cc0%3B.t1%3B%2CPride%20and%20Prejudice%3B%2Cc0%3B.t1%3B%2CSense%20and%20Sensibility%3B%2Cc0%3B.t1%3B%2CMansfield%20Park%3B%2Cc0). 

<h3>Findings<h3>

* opted out of using *Emma* or *Persuasion* as I thought the titles were too generic to return accurate results 
* *Pride and Prejudice* is always the most popular 
* all of the trends are somewhat similar: when one rises in popularity, so do the other ones 
* *Northanger Abbey* is always the least popular - interesting because both NA and P&P were originally written in the late 1790’s, but were revised for publication several years later 
* what books are contained in this codex? Are there several reprints of certain books? 

An article entitled “The Pitfalls of Using Google Ngram to Study Language” from *The Wire* in 2015 points to despite the optimistic claims of how Google NGrams will enable the study of language, errors in OCR (i.e. the long S), the skewed corpus (due to an overabundance of scientific literature), and the large variety of genres and kinds of books in the twentieth century, and crappy metadata – which is automated and prone to error in the dates of publication. The article claims that while errors in Google Books are updated, this data was only updated on Ngram viewer once in the past three years. Furthermore, the metadata – the information about the scanned book like author, genre, etc., is largely automated and unreliable. Furthermore, Google Ngrams relies on the printed word in the book form as authoritative when it comes to the prevalence of language and ideas. What about print culture, oral history, the development of spoken language? Why, in the “digital revolution,” should we limit this kind of mining of information to the confines of what happened to be printed in book form? Is this to Google’s advantage, or to our advantage, or just its convenience? Though I concur that Google Ngram is a powerful tool, a good use of it cannot be done without asking these questions and keeping them in mind while analyzing the graph. 

<h2>Romantic Rivalries in Jane Austen</h2>

* used the Terms tool on *Voyant* to look at name frequencies of the romantic hero and rival in four Austen novels 
* challenging because need to know which name the author calls him by - i.e. just searching for “Darcy” is insufficient because it might refer to his sister, “Miss Darcy”
* puts a character talking about him on equal footing with an actual appearance  

<h3>*Pride and Prejudice*</h3>

![Pride and Prejudice](https://github.com/jennaherdman/Austen-text-mining/blob/master/p%20and%20p%20terms.jpeg?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=aa5342d4d854354fea80232f149ecf5e&query=wickham*&query=mr%20darcy&withDistributions=raw&docIndex=0&mode=document&view=Trends) 

<h3>Findings</h3>
* moments of intersection between the two men 
* Wickham disappears and reappears consistently - at the end, he becomes important not as a rival for Elizabeth’s heart, but because he elopes with her sister 
* Darcy triumphs at the end 

<h3>*Sense and Sensibility*</h3>

![Sense and Sensibility](https://github.com/jennaherdman/Austen-text-mining/blob/master/sense-trends.jpeg?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=b521a70350c06325e841ed66af5c4e29&query=colonel&query=willoughby*&withDistributions=raw&mode=document&view=Trends).

<h3>Findings</h3> 
* Willoughby appears far more important than Colonel Brandon, except for in the last few segments 
* Brandon is steady but not dramatic - the aesthetic quality of the graph reflects the drama of the novel 
* in comparison to P&P, Willougby’s trend more closely resembles Darcy’s 

<h3>*Northanger Abbey* and *Mansfield Park*</h3>

![Northanger Abbey](https://github.com/jennaherdman/Austen-text-mining/blob/master/northanger-trends.png?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=e218ddd3ea097161c163a80f75c38f85&query=john|mr.%20thorpe*&query=henry|mr.%20tilney&withDistributions=raw&docIndex=0&mode=document&view=Trends).

![Mansfield Park](https://github.com/jennaherdman/Austen-text-mining/blob/master/mansfield.png?raw=true)

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=a99f30c20fdc2d887c74f9bc78c2eddf&query=edmund&query=henry|mr.%20crawford&withDistributions=raw&docIndex=0&mode=document&view=Trends).

<h3>Findings</h3>

* far more similar to each other than to P&P and S&S 
* the trends in each graph seem to mirror one another in how they increase and decrease 
* *Northanger Abbey* sees the hero/husband be more prominent throughout, while in *Mansfield Park* the rival is far more prominent - is there a mistake in the final graph? 
* because the final graph is so different from the first three, I am suspicious about its authenticity

<h2>Links - Collocation terms in *Sense and Sensibility*</h2>

![S&S links](https://github.com/jennaherdman/Austen-text-mining/blob/master/sense-collocation.jpeg?raw=true) 

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=b521a70350c06325e841ed66af5c4e29&mode=corpus&view=CollocatesGraph).

* why such a discrepancy between “Marianne” and “Marianne’s”? 
* requires a lot of intuition/cultivation by the person using the tool, not simply generated 
* necessitates “playing” with the graph 

<h2>Conclusions</h2>

* some of Voyant’s tools are inaccessible, require a lot of concentration in clicking and hand-eye coordination 
* the act of creating the graph is a form of reading and analysis: making informed choices about how to structure and program each one 
* future studies could look at sentiment analysis by chapter - [see Julia Silge](http://juliasilge.com/blog/Life-Changing-Magic/). 
* useful for undergraduate classes: unpacking the text, looking for patterns, critiquing their results 

Stephen Ramsay speaks optimistically of the following: 
we can envision machines that assist the literary critical scholar at the stage at which all truly illuminating engagements begin: that point when the reading of the text becomes a re-creation (perhaps even a recreation) of the text according to new rules – a playful quest for the patterns that the critic will hold up as illustrative of an un-recreated original (171). 
A key word here is playful: by playfully experimenting with the text of Austen’s novels, Voyant has allowed me to apply new methods of reading the texts. Though perhaps my graphs are inconclusive, the act of conceptualizing, generating, and analyzing them is a method of analysis. The act of creating a new graph becomes important here as involves a playful defamiliarization of a text’s form in order to approach it and understand it in a new way. This playful experience is, I think, the main value of Voyant for my scholarship: whether or not the results of the graphs are valid, the act of using the tool myself is a useful form of engagement. Accordingly, I am not convinced that simply reading these graphs and my analysis is a sufficient form of scholarship for a reader. What I propose instead is the implementation of this kind of network visualization as an informative supplementary resource. Thus, the process of playing with these tools can offer new reading strategies and forms of digital literacy that enhance our readings of traditionally print texts. Perhaps undergraduate English classes whose students are not fully grasping the nuances and pleasures of reading Austen could benefit from this kind of play. 
However, I think there are more sophisticated uses for text mining and visualization technologies with respect to Austen’s novels. Were I to continue this research, I could follow Julia Silge’s strategy of sentiment analysis in Austen’s novels. Instead of relying on text frequencies, Silge looks at units of text and identifies individual chapters as “sentimental” or “non-sentimental” based on their language, and graphs them as such, instead of relying on single words or names (unigrams). This approach requires more individual coding of sentences and more complex tools than my current knowledge of Voyant can offer, but could lead to more precise results. For instance, is Darcy spoken of more positively, or negatively? Can Elizabeth’s feelings towards Darcy be quantified, and how does this relationship measure up between the romantic heroes in the various Austen novels? 

On that note, I am also concerned with Voyant’s glitches and resulting inaccessibility. When working on Fig. 5, the Links tool required keen hand-eye coordination, as clicking too frequently led to a glitch where a new window would open and skew the results of the previous map. I imagine that for a student with limited mobility or low control of hand movements, this tool would be very difficult to use. Perhaps we will see further versions of Voyant smooth out these issues and become more user-friendly: I can imagine future versions of text mining that use eye tracking machines to build and play with interactive visualizations. I look forward to continuing to experiment with Voyant in the future, and to see accessible and open-access text mining tools continue to be developed. 

##Thank you! 

<center><h2>Works Cited</center></h2>
Austen, Jane. Mansfield Park. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016. 

---. Northanger Abbey. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016.

---. Pride and Prejudice. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016.

---. Sense and Sensibility. n.p. n.d. Project Gutenberg. Web. 28 Oct. 2016.

Hayles, N. Katherine. “How We Read: Close, Hyper, Machine.” ADE Bulletin 150 (2010): 
62-79.

Ramsay, Stephen. “Toward an Algorithmic Criticism.” Literary and Linguistic Computing 18.2 (2003): 167-174. 

Herdman, Jenna. “Tool Tutorial: Text Analysis.” GitBook, 2016. Web. Accessed 28 Oct 2016. < https://jennaherdman.gitbooks.io/a-digital-humanities-primer-for-english-students/
content/Text%20Analysis%20Assignment.html>

Silge, Julia. “The Life-Changing Magic of Tidying Text.” data science ish. Web. 29 Apr. 2016. Accessed 27 Oct. 2016.

Sinclair, Stéfan and Geoffrey Rockwell. "About." Voyant Tools. 2016. Web. 31 Oct 2016. <http://voyant-tools.org>.

---. "Links." Voyant Tools. 2016. Web. 31 Oct 2016. <http://voyant-tools.org>.

---. "Trends." Voyant Tools. 2016. Web. 31 Oct 2016. <http://voyant-tools.org>.
