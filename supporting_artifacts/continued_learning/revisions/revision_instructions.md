

For the revisions included in your Portfolio, to help me understand the nature
of your revisions, please denote somehow the feedback I provided you (e.g.,
boldface, italics, colored text) before your revisions.

Lab 3 Revisions  

<span style="color: red;">We frequently use the distinct() function in this class, but this will work as well. However, I specifically requested an output that summarizes how many words, not the actual words. Consider the nature of the data when plotting. Is every participant on one row? If not, what should you do with the data before plotting it? Look at your y-axis values? Do those make sense?</span>

Reflection: In my previous attempt, I had printed out each unique word in the dataset rather than just getting a count. I resolved this issue by finding the necessary function during office hours. Additionally, my graphs had 4000 as a count for age which made no sense for the dataset because there were only 168 people. I resolved this with the distinct function to remove all repeated rows only keeping unique observations to set my graph up in a way that made sense in regards to the dataset.  

I chose this revisions because it showed the importance of using functions that are related with getting unique observations, as the dataset in this lab had repeated entries but there were only 168 subjects. This fact made it hard to create graphs and work with the data without first removing all the repeated data which is why I included this revision because it was a good lesson to remember to check my datasets twice and look for any discrepancies.   

Challenge 4 Revisions  

<span style = "color: red;">We use boxplots to plot the relationship between one numerical variable and one categorical variable. What type of plot is more suitable for two numerical variables? Having clear axis labels is an absolute must for every plot we make. If you transformed a variable (like taking the log) your axis should clearly state what transformation you used. Additionally, this seems like a great place for some annotations instead of a legend! Or, you could play with the location of your legend!</span>

Reflection: My first attempt I believed a boxplot would be better suited because I wanted to plot regions and how the total avocado sales would vary based on price, but a boxplot does not a do a very good job of plotting 2 quantitative variables. A scatterplot would be best suited for this because it can graph 2 quant variables, but also it is easier to compare total avocado sales by size and type with this type of graph as opposed to a boxplot.My earlier graph was messy to look at and understand because I had not specified my scaling even though I did use a scale of log10. I have learned now that labeling is a very important aspect of visualizations otherwise people will be confused at what they're looking at Additionally, my legend made the graph a little dizzying to look at. I used annotations to fix this issue so my graph is clearer to look at.  

I chose lab 4 revision because it showed me the importance of selecting which graph to use based on the data given and also to use clear labels when scaling your data for the graph, otherwise it may confuse readers. I chose to use this revision because my revision showed understanding of various graph types with respect to the data used and also how to make graphs/tables more clear by utilizing descriptive titles and including any other processes that may have affected the graph whether it was scaling, graphing averages, removing outliers, etc.  

Challenge 7 Revisions  

<span style = "color: red;">There’s something going on with these lines! geom_line() expects for there to be one observation for each year. Is that the case? If not, what can you do to make this the case?</span>

Reflection: In my previous response I had a line chart with many lines that were overlapping and messy to look at, this was because the data I was plotting had many observations for a single year but the geom_line is not able to plot that. I resolved this by finding a summary statistic for each year based on species and river type resulting in only 2 lines for each of my graphs.  

My challenge 7 revisions showed the purpose of the geom_line() function and how to use it to plot descriptive statistics. The dataset had multiple observations per year, so the best way to plot these observations would be an average or some type of summary statistic per year which would only have one point per year which would prevent the graph from looking like multiple lines. I chose this revision because it was a big teaching moment to me when it comes to plotting observations and being aware if I am plotting multiple observations or if I need to adjust the graph to plotting only one observation per year and what neccesary steps I need to take in order to accomplish that task. 
