# Constructing_a_Manuscript
How to work through a project without getting overwhelmed by new topics and data analyses


## Step 1: Find initial paper

What you are aiming for: one or two key review papers

Before you start a paper on a new topic, I would recommend finding one or two key reviews of the topic and give them a quick read. This helps you find your bearing, however before you get into the actual analysis the details may go over your head, so don’t spend too much time at this stage. You can (and will) come back to read these later when you understand the topic better. While reading this paper try formulate an idea of what type of analysis you want to do. Take note of data papers heavily referenced, and pressing new directions that the review paper emphasizes. Use websites like connected papers if it helps. 

## Step 2: Find seminal papers.
What you are aiming for: as many data papers as you need to cover your initial data analysis plans.
Now you have an idea of what kind of questions you want to answer, time to find papers and programs that cover this. This bit is the most important for making your project run smoothly. You need to work out what type of analysis you want to run, in what order you should run them, and which programs are best suited for the job. Once you have settled on this, look up the program’s citation in google scholar and identify all the papers that have referenced it. Search through these until you have 1-3 papers that (1) had similar data to your own, (2) reports their methods clearly i.e. you know what program settings they used, (3) and if you are lucky have their code publicly available (though this last one is not essential). Note these papers down at the top of your code/analysis workbook, along with a link to the program manual. Repeat this for every separate analysis/program you plan to run (unless it is analysis you are already familiar with).

## Step 3: make some dummy plots

What you are aiming for: dummy versions of all your main figures and tables.

Now you know what programs you will use, and you have examples of how it was done from other papers, make some dummy plots (and tables!). The idea is to think about how your data will be summarized and visualized. Work out which plots belong together as a multi-panel figure. Start thinking about how the potential results will feed into one another and the story they will tell. Think about what other results will be needed to compliment/help interpret the main figures/results. At this stage I even start filling in the methods and results, including making subheadings for your methods and results. You don’t have any actual results, but look at how your seminal papers reported the data, and follow the formulas that work. This will help you work out whether the ordering of your analysis makes sense. You can even start adding points to your discussion about important contexts/caveats that you know you need to talk about.

-Everything up to this point can be done before/during data collection-

## Step 4: Start analysing

What you are aiming for: Produce plots with your actual data

For each program that you are new to, first run the test/example data, then run yours. Read the important bits of the manual and skim through the program publication to understand the settings you need to use. But don’t think you have to become an expert at the program straight away. If you have trouble running your data you may want to subset your data during troubleshooting (e.g. if working with genomic data, use just one scaffold from the assembly rather than the whole genome. Or Subset your SNP file to just SNPs from one scaffold. Or randomly subsample your data). Don’t spend too long making pretty plots or making your analysis ‘perfect’. You will likely rerun it many times after supervisor/coauthor/reviewer comments. Just get that plot and replace out the dummy plot from your slowly growing written manuscript. Every time you make a table or a plot that you think is important to validate the main paper findings stick these in a draft Supplementary Materials, but don’t spend a lot of time here as you can clean this up at the end. 

As you make these main and supplementary plots, start adding the relevant new information to the methods and results. As always if you think of an important discussion point just add it to the draft manuscript. You may find that once you have enough singular thoughts floating around in your draft discussion you can start grouping them a bit.
As you go, if you have uncertainties about analysis/plots/results/whatever, add these as a comment to the document. Things like “does it make sense to include linked SNPs for this analysis” or “I use mean here,  but maybe median is a better summary metric for this data”. Every time you have a thought that makes you feel uncertain or anxious about a step of project, note it as a comment on the manuscript document. You don’t have to quell all your uncertainties and know 100% how a program works from the moment you start using it. But you should keep track of these thoughts.

## Step 5: Iteration

What you are aiming for: iron out the details

Work through your questions with yourself, your supervisor, and colleagues. Iron out all those uncertainties. Never be too scared to go back and rerun everything from the top. If that is a painful thing to do, then that is a good sign you need to take better notes or make your code more automated. Every time you iterate back over your code/analysis notes clean it up and add more comments. And of course as you go you may change your initial plan: maybe some analysis didn’t work out, or you want to replace it with something more exciting that your stumbled across!
Combine your separate chunks of methods/results/discussion text into something cohesive, making sure again that everything is in an appropriate order given the order of the analysis and the story that the data tells. Another important step here is to re-read your initial paper closely (the review). The idea at this step is to see if you missed any important context or pitfalls. Continue filling in the discussion. I also like going back to the list of papers that have referenced your program’s initial publication. Have another look through some of these. Now you have run your programs a few times and understand more about how and why it works, you may notice more variation in how people used that program. Reconfirm that you have done it in the optimal way for your data. Also, take a look at their plots and continue to think about how best to make your figures.

## Step 6: Final clean up

What you are aiming for: make sure the workflow/analyses/story are clear

Read from top to bottom and make sure it makes sense. For those seminal papers that guided your methodology, try reference them where possible, either in your method if relevant, but if you basically ran the program on fairly default settings (and thus don’t need to reference some special method) then try include that paper in your manuscript somewhere, like the discussion. Also ask yourself: “why were these papers extra clear/helpful to me as someone new to the topic?”. And make sure that your manuscript is like that also!   


