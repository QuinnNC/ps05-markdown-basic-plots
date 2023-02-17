# ps05-markdown-basic-plots
problem set 5 repo - markdown and basic plots

## Instructions

This is a problem set about rmarkdown and plotting (using ggplot). Unlike the previous problem
sets, this one does not give you a ready-made GH repo with a code file–it is now your taks to create
a repo and include your rmarkdown file in there.
You should answer the questions below in that file, knit it, and submit both the compiled html
and link to your repo on canvas.
- This problem sets asks you to write extensively when commenting your results. Please write
clearly! Answer questions in a way that if the code chunks are hidden then the result is still
readable!
  - All substantial questions need explanations. You do not have to explain the simple things
like “how many rows are there in data”, but if you make a plot of life expectancy, then
you should explain what does the plot tell you.
  – Write explanations as markdown and use the styles like bold and italic as appropriate.
- Do not print too much results. It is all well to print a few lines of data for evaluaton/demonstration purposes. But do not print dozens (or thousands!) of lines–no one bothers to look
at that many numbers. You will lose points for annoying others (here your graders, but later
potentially your boss).
- Do not make code lines too long. 80-100 characters is a good choice. Your grader may not
be able to follow all the code if the line is too long–most of us are using small laptop screens!
(And again–you want to keep your graders happy!)

## Gapminder data

We use gapminder dataset, downloaded from https://www.gapminder.org/data/, however, the data structure there is quire complex, please use the dataset provided on canvas (in files/data).

The variables are:
**name** country name
**iso3** 3-letter country code
**iso2** 2-letter country code
**region** broad geographic region
**sub-region** more precise region
**intermediate-region**
**time** year
