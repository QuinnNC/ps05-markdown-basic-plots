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
- **name** country name
- **iso3** 3-letter country code
- **iso2** 2-letter country code
- **region** broad geographic region
- **sub-region** more precise region
- **intermediate-region**
- **time** year
- **totalPopulation** total population
- **GDP_PC** GDP per capita (constant 2010 US$)
- **accessElectricity** Access to electricity (% of population)
- **agriculturalLand** Agricultural land (sq. km)
- **agricultureTractors** Agricultural machinery, tractors (count)
- **cerealProduction** Cereal production (metric tons)
- **feritilizerHa** Fertilizer consumption (kilograms per hectare of arable land)
- **fertilityRate** total fertility rate (births per woman)
- **lifeExpectancy** Life expectancy at birth, total (years)
- **childMortality** Mortality rate, under-5 (per 1,000 live births)
- **youthFemaleLiteracy** Literacy rate, youth female (% of females ages 15-24)
- **youthMaleLiteracy** Literacy rate, youth male (% of males ages 15-24)
- **adultLiteracy** Literacy rate, adult total (% of people ages 15 and above)
- **co2** CO2 emissions (kt)
- **greenhouseGases** Total greenhouse gas emissions (kt of CO2 equivalent)
- **co2_PC** CO2 emissions (metric tons per capita)
- **pm2.5_35** PM2.5 pollution, population exposed to levels exceeding WHO Interim Target-1 value 36ug/m3 
- **battleDeaths** Battle-related deaths (number of people)

## 1 Load and check data (5pt)

You first task is to do a very simple data check:
1. (1pt) For solving the problems, and answering the questions, create a new rmarkdown document with an appropriate title. See https://faculty.washington.edu/otoomet/info201-book/r-markdown.html#r-markdown-rstudio-creating.
2. (2pt) Load data. How many rows/columns do we have?
3. (2pt) Print a small sample of data. Does it look OK?

## Descriptive statistics (15pt)

1. (3pt) How many countries are there in the dataset? Analyze all three: iso3, iso2 and name.
2. If you did this correctly, you saw that there are more names than iso-2 codes, and there are
even more iso3 -codes. What is going on? Can you find it out?
(a) (5pt) Find how many names are there for each iso-2 code. Are there any iso-2 codes that
correspond to more than one name? What are these countries?
(b) (5pt) Now repeat the same for name and iso3-code. Are there country names that have
more than one iso3-code? What are these countries?
Hint: two of these entitites are CHANISL and NLD CURACAO.
3. (2pt) What is the minimum and maximum year in these data?

