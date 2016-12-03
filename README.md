# Learning D3
## September 23, 2015

I started this project to learn D3. <a href="https://d3js.org/">D3.js</a> is a javascript library which can be used to manipulate documents with data. Here is the plot I created:

<a href="https://hmvantol.github.io/antibiotics/antibiotics.v3.html"><img src="https://github.com/hmvantol/antibiotics/blob/master/screenshot1.png"></a>
<i>Click on the plot to view graphic.</i>

In 1951 the graphic designer <a href="https://en.wikipedia.org/wiki/Will_Burtin">Will Burtin</a>, published a plot to visualize the efficacy of 3 antibiotics on 16 different bacteria. Antibiotic efficacy is measured by the minimum concentration required to inhibit bacterial growth.

<img src="http://www.americanscientist.org/Libraries/images/2009641416567334-2009-07MacroWainerFA.jpg">
This plot was admired for its simplicity in comparing the effects of different antibiotics. But it does not clearly show how the bacteria group together in their response. Different visualizations can emphasize different aspects of the data. (See article in <a href="http://www.americanscientist.org/issues/pub/thats-funny">American Scientist</a>).

I used Burtin’s data to create a simple bar plot that alternates between displays of different antibiotics. The plot more clearly shows that Gram positive bacteria are more resistant to streptomycin and neomycin while Gram negative bacteria are more resistant to penicillin. It also shows which bacteria do not follow the trend. Gram-staining uses violet and pink dyes to distinguish between different groups of bacteria by cell wall structure.

<b>Source material:</b>

<a href="http://chimera.labs.oreilly.com/books/1230000000345/index.html">Interactive Data Visualization for the Web</a> by Scott Murray
