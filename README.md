<center><h1>Welcome!</h1></center>

<center>![Jane Austen](https://upload.wikimedia.org/wikipedia/commons/f/f9/Jane_Austen_1870_cropped.jpg)</center>


This project applies tools from the digital text-mining platform Voyant to four Jane Austen novels, and critiques the effectiveness, accessibility, and scholarly potential of these applications. In doing so, I experiment with what N. Katherine Hayles called the “porous boundaries” of human interpretation and machine pattern recognition (73) by analyzing patterns of romance in the novels. Nineteenth-century texts are often available for free download and are rich resources for experimenting with text mining tools, and Jane Austen’s status as a literary giant within the canon means that she is a useful resource upon which to experiment with new methodologies. In this analysis, I ask: does this visualization contribute anything to Austen scholarship and, if so, could this research be used for pedagogical purposes? Is this experiment an example of an Austen scholar becoming more “digitally literate,” or does it detract from traditional methods of close reading and analysis?

<h2>Methods</h2>

[Voyant, an open-access program directed by Stéfan Sinclair and Geoffrey Rockwell](http://docs.voyant-tools.org/tools/), comprises of several text mining and visualization tools. When conceptualizing this experiment, I built on a [previous project](https://jennaherdman.gitbooks.io/a-digital-humanities-primer-for-english-students/content/Text%20Analysis%20Assignment.html) in which I used Voyant’s Terms, Knots, and Bubblelines tools to trace the recurring appearances of minor characters in Charles Dickens’s David Copperfield. Though these results were experimental and not conclusive, I argued that the tools offered a useful way of manipulating the text and of visualizing research questions. Here, I apply this method to Austen novels <i>Pride and Prejudice</i>, <i>Sense and Sensibility</i>, <i>Northanger Abbey</i>, and <i>Mansfield Park</i> by producing term frequency charts which represent the romantic heroes and rivals of each novel. Austen’s romances rely on the protagonist rejecting the “wrong” suitor in favour of the “right” man: for example, in <i>Pride and Prejudice</i> and <i>Sense and Sensibility</i>, the heroine can only recognize the worthiness of her future husband when he has demonstrated the immoral nature of his rival. In <i>Northanger Abbey</i> and <i>Mansfield Park</i>, the wrong suitor is never a real contender for the heroine’s hand, though he must be revealed to be inferior in order for the heroine to go on to marry the hero. I predicted that there would be similar patterns in each of these two pairs of novels based on their similar plot lines, and that the hero would be more dominant than his rival in each graph.

In order to graph the romantic rivalries, I used the Terms tool to look at the frequencies of each male competitor’s name, going on the assumption that a high frequency of the character’s name signifies his importance to the protagonist or the text. Using term frequencies to track plot development in Austen is challenging, however, because it requires a close knowledge of the names that the author uses to refer to each character. The suitor’s name might appear not even when he is absent if the characters are talking about him. Consider, for example, how Mrs. Bennet talks a great deal about Mr. Bingley’s arrival in Meryton before he even appears as a character. When using these tools, then, a mention of the suitor’s name has equal weight in the graph as do his actual actions. Thus, this method requires thinking about each mention of the character as a sign of his importance to the text. Furthermore, the algorithms to measure these text frequencies require pre-existing knowledge of the text’s semantics. For example, in <i>Pride and Prejudice</i>, Darcy is usually referred to as “Mr. Darcy,” as opposed to his first name. Also his sister is called “Miss Darcy” in the novel, and simply searching for their last name would skew the results. Likewise, in Mansfield Park, Fanny’s main love interest, Edmund Bertram, is her cousin, and thus is usually called by his first name, while his brother Tom is more commonly called “Mr. Bertram: searching for the term frequency of “Mr. Bertram” would thus not represent Edmund at all.

<h2>I. Romantic Rivalries in Jane Austen: Pride and Prejudice and Sense and Sensibility</h2>

<h3>Pride and Prejudice</h3>

In my graph of Pride and Prejudice, I mapped the frequency of “Mr. Darcy” against mentions of “Wickham.” The x-axis represents the text of the novel divided into 10 equal segments.  I found that Darcy prevails in importance throughout most of the novel, though I was surprised to see mentions of his name decline somewhat in the second half. I was surprised to see Wickham’s importance consistently rise throughout the novel. It is curious how, as Elizabeth’s affection grows for Darcy, the frequency of his name decreases slightly. Is Darcy so important in the first half because Elizabeth focuses on hating him, while in the second half, she spends more time thinking about her family and less about her dislike for Darcy? Does Wickham rise in importance for the third time in Segments 8-9 when he runs away with Lydia – and thus comes to represent a greater threat that dominates that moment? However, as predicted, the end of the novel sees Darcy rising at the end, and overall, his name frequency is more dominant than his rival’s. 

![Pride and Prejudice](https://github.com/jennaherdman/Austen-text-mining/blob/master/p%20and%20p%20terms.jpeg?raw=true)

Romantic rivals in Pride and Prejudice. This graph compares the term frequencies of the hero Mr. Darcy (total frequency=272) and the immoral rival, Wickham (total frequency=194).  Made using the “Terms” tool on Voyant.

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=aa5342d4d854354fea80232f149ecf5e&query=wickham*&query=mr%20darcy&withDistributions=raw&docIndex=0&mode=document&view=Trends) 

<h3>Sense and Sensibility</h3>

A second graph (see Fig. 2) looks at the frequency trends of “Willoughby” and “Colonel,” Brandon, the two contenders for Marianne Dashwood’s heart in Sense and Sensibility. I made the choice to use the frequencies of the word “Colonel” instead of “Brandon” in the graph, as this reflects the title that is used in the novel. Like Wickham, Willoughby appears as a handsome, dashing hero, who turns out to have a dark past and to be pursuing a wealthy wife. Colonel Brandon is initially ignored by Marianne, but she eventually comes around and marries him after he exposes Willoughby’s treachery. What is notable about this graph is how the two suitors seem to oppose one another: in the first two-thirds of the novel, Willoughby is of the upmost importance, while Brandon is kept in the background. At Segment 8, Brandon triumphs for the first time in importance, entering the lives of the sisters and suggesting that he is there to stay, while Willoughby fades into Brandon’s initial place of reduced importance. 

![Sense and Sensibility](https://github.com/jennaherdman/Austen-text-mining/blob/master/sense-trends.jpeg?raw=true)

Romantic rivals in Sense and Sensibility. This graph compares the term frequencies of Marianne’s eventual husband, Colonel Brandon (total frequency =176) and his rival for her love, the treacherous Mr. Willoughby (total frequency = 219).  Made using the “Terms” tool on Voyant.

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=b521a70350c06325e841ed66af5c4e29&query=colonel&query=willoughby*&withDistributions=raw&mode=document&view=Trends).

<h3>Comparisons</h3> 

Both Fig. 1 and Fig. 2 show the triumph of the chosen husband at the end (unsurprisingly). Though Wickham’s importance is more consistent than Willoughby’s, the contrast between Willoughby’s and the Colonel’s trends in Fig. 2 is far more dramatic than the contrast between Darcy and Wickham in Fig. 1. Indeed, though Brandon is the one who marries Marianne, Darcy and Willoughby’s trends are similar. Does this pattern suggest that Willoughby is the true romantic hero of Sense and Sensibility, despite his flaws and his betrayal of Marianne? Should my future analyses of Willoughby be to treat him more like Darcy, the romantic hero, than like Wickham, the immoral antagonist? In this sense, the graphs contradict my initial hypothesis that the husband’s trend would prove more dominant.

<h2>Northanger Abbey and Mansfield Park</h2>

In comparison to the patterns in <i>Pride and Prejudice</i> and <i>Sense and Sensibility</i>, the graphs of romantic rivalries in Northanger Abbey and Mansfield Park show a more linear and less fluctuating trend for the romantic suitors in each of the novels. Instead of rapidly moving from high to low frequencies, they are more steady and consistent throughout the novels. This trend could reflect a structural element of the texts, or demonstrate how the suitors in both Northanger Abbey and Mansfield Park are more consistently present. This pattern makes sense, as the heroines are guests in the homes of the men they eventually marry - Henry Tilney is the son of the owner of Northanger Abbey, while Edmund is the son of the master of Mansfield Park. It is also interesting how in Fig. 3, from Segment 4 on there is a consistent correlation between the trends of Tilney and Thorpe. In Northanger Abbey, the romantic hero appears at a higher frequency for most of the novel, while in Mansfield Park, I was surprised to see that Henry Crawford maintains a consistently higher frequency than Edmund. Due to my findings in Figs. 1, 2, and 3, where the hero and the rival are either closely matched or the hero triumphs, this trend in Fig. 4 makes me suspicious that there is an error in the way I modeled this graph. This inconsistency speaks to the difficulties of trusting these kinds of experiments when using a tool like Voyant, which can only really scratch the surface of text mining potentialities.

![Northanger Abbey](https://github.com/jennaherdman/Austen-text-mining/blob/master/northanger-trends.png?raw=true)

Romantic rivals in Northanger Abbey. This graph compares the term frequencies of the romantic hero and Catherine’s eventual husband, Henry Tilney (total frequency=514), with a rival for her affection, John Thorpe (total frequency=372). Made using the “Terms” tool on Voyant.

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=e218ddd3ea097161c163a80f75c38f85&query=john|mr.%20thorpe*&query=henry|mr.%20tilney&withDistributions=raw&docIndex=0&mode=document&view=Trends).

![Mansfield Park](https://github.com/jennaherdman/Austen-text-mining/blob/master/mansfield.png?raw=true)

Romantic rivals in Mansfield Park. This graph compares the term frequencies of Fanny Price’s cousin, Edmund (total frequency=364), whom she loves and marries, and Henry Crawford (frequency=1148), who falls in love with and proposes to Fanny only to be rejected. Made using the “Terms” tool on Voyant.

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=a99f30c20fdc2d887c74f9bc78c2eddf&query=edmund&query=henry|mr.%20crawford&withDistributions=raw&docIndex=0&mode=document&view=Trends).

<h2>II. Links - Collocation terms in *Sense and Sensibility*</h2>

Though this project has focused on looking at the frequencies of names to study romance plots, there are many other tools that might be useful for creatively manipulating texts like Austen’s. For example, one experiment that I did in the process of this research was to use the Links tool to visualize a map of collocates in Sense and Sensibility (see Fig. 5). The results of this map demonstrate an interesting distinction between the collocates of “Marianne” and “Marianne’s.” Why should there be a difference between the noun and the possessive? My hypothesis is that the possessive “Marianne’s” appears most commonly in the voice of the narrator when they are commenting on Marianne and who condemns Marianne’s excessive sensibility – her tendency to display her “feelings,” and to feel great “affection” with her “heart.” In contrast, the word “Marianne” is perhaps used more often when Marianne herself is partaking in an action, or when the other characters are speaking to or about her. The link between “Marianne” and “Willoughby” is far stronger than the one between “Marianne” and “Colonel Brandon,” her eventual husband, reinforcing my hypothesis from looking at Fig. 2 that perhaps Willoughby is far more important than Marianne’s future husband to the plot of the novel. 

However, this graph is incomplete and was specifically curated. It relies greatly on my own intuition about relevant words, and from my premeditated decision about what kind of graph would make an interesting analysis. I deleted collocates that did not seem useful, and requested other terms to see if they would link up to the existing map. In this sense, human intuition and machine reading work together. Furthermore, I argue that the act of creating this map requires the skills of close reading as well as a pre-existing knowledge about the text. Organizing the map required a great deal of interpretation and choices on my part, and was explicitly interactive. I did not simply plug in a text and wait passively for the results, but actively played with the results in order to produce a framework for analysis. 

![S&S links](https://github.com/jennaherdman/Austen-text-mining/blob/master/sense-collocation.jpeg?raw=true) 

Collocate linked map in Sense and Sensibility. Made using the Links tool in Voyant.

[Follow this link for an interactive version of this graph](http://voyant-tools.org/?corpus=b521a70350c06325e841ed66af5c4e29&mode=corpus&view=CollocatesGraph).


<h2>Conclusions</h2>

Stephen Ramsay speaks optimistically of the following: 
we can envision machines that assist the literary critical scholar at the stage at which all truly illuminating engagements begin: that point when the reading of the text becomes a re-creation (perhaps even a recreation) of the text according to new rules – a playful quest for the patterns that the critic will hold up as illustrative of an un-recreated original (171). 
A key word here is playful: by playfully experimenting with the text of Austen’s novels, Voyant has allowed me to apply new methods of reading the texts. Though perhaps my graphs are inconclusive, the act of conceptualizing, generating, and analyzing them is a method of analysis. The act of creating a new graph becomes important here as involves a playful defamiliarization of a text’s form in order to approach it and understand it in a new way. This playful experience is, I think, the main value of Voyant for my scholarship: whether or not the results of the graphs are valid, the act of using the tool myself is a useful form of engagement. Accordingly, I am not convinced that simply reading these graphs and my analysis is a sufficient form of scholarship for a reader. What I propose instead is the implementation of this kind of network visualization as an informative supplementary resource. Thus, the process of playing with these tools can offer new reading strategies and forms of digital literacy that enhance our readings of traditionally print texts. Perhaps undergraduate English classes whose students are not fully grasping the nuances and pleasures of reading Austen could benefit from this kind of play. 
However, I think there are more sophisticated uses for text mining and visualization technologies with respect to Austen’s novels. Were I to continue this research, I could follow Julia Silge’s strategy of sentiment analysis in Austen’s novels. Instead of relying on text frequencies, Silge looks at units of text and identifies individual chapters as “sentimental” or “non-sentimental” based on their language, and graphs them as such, instead of relying on single words or names (unigrams). This approach requires more individual coding of sentences and more complex tools than my current knowledge of Voyant can offer, but could lead to more precise results. For instance, is Darcy spoken of more positively, or negatively? Can Elizabeth’s feelings towards Darcy be quantified, and how does this relationship measure up between the romantic heroes in the various Austen novels? 

On that note, I am also concerned with Voyant’s glitches and resulting inaccessibility. When working on Fig. 5, the Links tool required keen hand-eye coordination, as clicking too frequently led to a glitch where a new window would open and skew the results of the previous map. I imagine that for a student with limited mobility or low control of hand movements, this tool would be very difficult to use. Perhaps we will see further versions of Voyant smooth out these issues and become more user-friendly: I can imagine future versions of text mining that use eye tracking machines to build and play with interactive visualizations. I look forward to continuing to experiment with Voyant in the future, and to see accessible and open-access text mining tools continue to be developed. 


<h2>Something extra: Google Ngram graph</h2>

Google Ngrams is a tool created for mining the Google Books corpus for linguistic data. Basically, you can search for a word, or several words, in Google Ngrams, and it will show you the frequencies of that word across the entire digitized corpus. Arguably, this tool can be used to trace the evolution of language, such as the popularity of certain words. Though this graph does not pertain directly to the work with Voyant, I included it for those interested in critiquing Google's interfaces and in looking at Austen's popularity more generally. 

![Fig. 1: Austen Trends](https://github.com/jennaherdman/Austen-text-mining/blob/master/unspecified.jpeg?raw=true)

[Follow this link for an interactive version of this graph](https://books.google.com/ngrams/graph?content=Northanger+Abbey%2CPride+and+Prejudice%2CSense+and+Sensibility%2CMansfield+Park&year_start=1800&year_end=2010&corpus=15&smoothing=3&share=&direct_url=t1%3B%2CNorthanger%20Abbey%3B%2Cc0%3B.t1%3B%2CPride%20and%20Prejudice%3B%2Cc0%3B.t1%3B%2CSense%20and%20Sensibility%3B%2Cc0%3B.t1%3B%2CMansfield%20Park%3B%2Cc0). 

<h3>Findings</h3>

* opted out of using *Emma* or *Persuasion* as I thought the titles were too generic to return accurate results 
* *Pride and Prejudice* is always the most popular 
* all of the trends are somewhat similar: when one rises in popularity, so do the other ones 
* *Northanger Abbey* is always the least popular - interesting because both NA and P&P were originally written in the late 1790’s, but were revised for publication several years later 
* what books are contained in this codex? Are there several reprints of certain books? 

An article entitled “The Pitfalls of Using Google Ngram to Study Language” from *The Wire* in 2015 points to despite the optimistic claims of how Google NGrams will enable the study of language, errors in OCR (i.e. the long S), the skewed corpus (due to an overabundance of scientific literature), and the large variety of genres and kinds of books in the twentieth century, and crappy metadata – which is automated and prone to error in the dates of publication. The article claims that while errors in Google Books are updated, this data was only updated on Ngram viewer once in the past three years. Furthermore, the metadata – the information about the scanned book like author, genre, etc., is largely automated and unreliable. Furthermore, Google Ngrams relies on the printed word in the book form as authoritative when it comes to the prevalence of language and ideas. What about print culture, oral history, the development of spoken language? Why, in the “digital revolution,” should we limit this kind of mining of information to the confines of what happened to be printed in book form? Is this to Google’s advantage, or to our advantage, or just its convenience? Though I concur that Google Ngram is a powerful tool, a good use of it cannot be done without asking these questions and keeping them in mind while analyzing the graph. 

<h1>Thank you!</h1>

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
