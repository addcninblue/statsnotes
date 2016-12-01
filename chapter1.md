CHAPTER 1 - EXPLORING DATA
==========================


INTRODUCTION - DATA ANALYSIS: MAKING SENSE OF DATA
--------------------------------------------------

- **Individuals** = objects described by set of data. May be people, animals, things.
- **Variables** = characteristic of an individual. Can take different values for different individuals.
- **Categorical Variable** = places individual into one of several groups or categories
- **Quantitative Variable** = takes numerical values for which it makes sense to find an 
- average
    - *Not every variable that takes number values is quantitative.*
- A variable generally takes values that vary.
- Categorical variables sometimes have similar counts in each category, sometimes don’t. Quantitative variables may take values that are very close together or values that are quite spread out. We call this pattern of variation of a variable a distribution.
- **Distribution** = tells us what values the variable takes and how often it takes these values.


HOW TO EXPLORE DATA
-------------------
1. Begin by examining each variable by itself. Then move on to study relationships among the variables.
2. Start with a graph(s). Then add numerical summaries.

**Inference** = drawing conclusions that go beyond data at hand

SECTION 1.1 - ANALYZING CATEGORICAL DATA
----------------------------------------
<table>
  <tr>
    <td>One</td>
    <td>Two</td>
  </tr>
  <tr>
    <td colspan="2">Three</td>
  </tr>
</table>| Frequency Table | Relative Frequency Table |
| --- | --- |

<table>
Frequency Table
Relative Frequency Table
Format
Count of Stations
Format
Percent of Stations
Adult Contemp.
1556
Adult Contemp.
11.2
Adult standards
1196
Adult standards
8.6
Contemp. hit
569
Contemp. hit
4.1
Country
2066
Country
14.9
News/Talk/Info
2179
News/Talk/Info
15.7
Oldies
1060
Oldies
7.7
Religious
2014
Religious
14.6

| Format | Count of Stations | Format | Percent of Stations |
| --- | --- | --- | --- |
| Adult Contemp. | 1556 | Adult Contemp. | 11.2 |
| Adult standards | 1196 | Adult standards | 8.6 |
| Contemp. hit | 569 | Contemp. hit | 4.1 |
| Country | 2066 | Country | 14.9 |
| News/Talk/Info | 2179 | News/Talk/Info | 15.7 |
| Oldies | 1060 | Oldies | 7.7 |
| Religious | 2014 | Religious | 14.6 |
| Rock | 869 | Rock | 6.3 |
| Spanish | 750 | Spanish | 5.4 |
| Other | 1579 | Other | 11.4 |
| Total | 13838 | Total | 99.9 |


In this case:
Individuals = radio stations
Variable = kind of programming that each station broadcasts
Frequency Table = displays counts (frequencies) of stations in each format category
Relative Frequency Table = shows percentages (relative frequencies) of stations in each format category
Check for consistency. Counts should add up to 13838. Percents should add up to 100%.
In this case, total adds up to 99.9%. This is called roundoff error.
INSERT BAR GRAPHS AND PIE CHARTS HERE - 
Bar graphs = more flexible than pie charts, can compare any set of quantities that are measured in the same units


YOUNG ADULTS BY GENDER AND CHANCE OF GETTING RICH


Gender


Opinion
Female
Male
Total
Almost no chance 
96
98
194
Some chance, prob. not
426
286
712
50/50 chance
696
720
712
A good chance
663
758
1416
Almost certain
486
597
1083
Total
2367
2459
4826


This is a two-way table because it describes 2 categorical variables, gender and opinion on getting rich. Opinion is the row variable because each row describes young adults who held one of the five opinions about their chances. Gender is the column variable. 
Marginal Distribution = distribution of values of that variable among all individuals described by the table.
Use percents, more informative than counts esp. when comparing groups of diff. sizes 
Marginal Dists. tell us NOTHING about relationship between two variables.
Conditional Distribution = describes the values of that variable among individuals who have a specific value of another variable. There is a separate conditional distribution for each value of the other variable.
PAGE 16 TECH CORNER: KNOW HOW TO ANALYZE MINITAB SHIT - 


HOW TO ORGANIZE A STATISTICAL PROBLEM: A FOUR-STEP PROCESS
State: What’s the question you’re trying to solve?
Plan: How will you go about answering the question? What statistical techniques are you using?
Do: Do it.
Conclude: Give your practical conclusion in the context of the problem.


Association = one variable tends to occur in common with specific values of the other
Even a strong association between two categorical variables can be influenced by other variables lurking in the background.
Simpson’s Paradox = reversal; An association between 2 variables that holds for each individual value of a third variable can be changed or even reversed when the data for all values of the third variable are combined.


SECTION 1.2 - DISPLAYING QUANTITATIVE DATA WITH GRAPHS
HOW TO EXAMINE THE DISTRIBUTION OF A QUANTITATIVE VARIABLE
Look for overall pattern and for striking departures from that pattern.
Shape, Center, Spread, Outliers (aka SOCS)


DESCRIBING SHAPE
Symmetric = R/L sides approximately mirror one another
Right-skewed = right side longer than left side
Left-skewed = left side longer than right side
The direction of skewness is in direction of long tail, not direction where most observations are clustered.
Unimodal, bimodal, multimodal


COMPARING DISTRIBUTIONS
Dot plot = displays individual values on number line
Stem plot = separate each observation into a stem + 1-digit leaf
Histogram = plot the counts (frequencies) or percents (relative frequencies) of values in equal-width classes
DO NOT CONFUSE HISTOGRAMS WITH BAR GRAPHS. 
Histograms display distribution of quantitative variable.
Bar graphs display distribution of categorical variable/compare sizes of different quantities. 
DO NOT USE COUNTS (in a freq. table) OR PERCENTS (in rel. freq. table) AS DATA.
USE PERCENTS, NOT COUNTS, ON VERTICAL AXIS WHEN COMPARING DISTS. WITH DIFF. NUMBERS OF OBSERVATIONS.


SECTION 1.3 - DESCRIBING QUANTITATIVE DATA WITH NUMBERS
MEASURING CENTER: THE MEAN
To find the mean x̄ for a set of observations, add their values and divide by the number of observations. If the n observations are x1, x2, … xn, their mean is


x̄ = sum of observations / n = x1 + x2 + … + xn / n


Or, in more compact notation,
x̄ = Σ xi / n


x̄ refers to the mean of a sample. μ refers to population mean. 
Mean extremely sensitive to influence of extreme observations = nonresistant measure of center


MEASURING CENTER: THE MEDIAN M
The median M is the midpoint of a distribution, the number such that half the observations are smaller and the other half are larger. To find the median of a distribution:
Arrange all observations in order of size, from smallest to largest.
If the number of observations n is odd, the median M  is the center of the observation in the ordered list.
If the number of observations n is even, the median M is the average of the two center observations in the ordered list.


COMPARING THE MEAN AND MEDIAN
The mean and median of a roughly symmetric distribution are close together. If the distribution is exactly symmetric, the mean and median are exactly the same. In a skewed distribution, the mean is usually farther out in the long tail than is the median.


MEASURING SPREAD: THE INTERQUARTILE RANGE (IQR)
A useful numerical description of a distribution requires both a measure of center and a spread.
First quartile (Q1) lies one-quarter of the way up a list of values (smallest → largest)
Third quartile lies ¾ of the way up the list. 
IQR measures range of the middle 50% of the data.
IQR = Q3 - Q1 


IDENTIFYING OUTLIERS = 1.5 x IQR 
Call an observation an outlier if it falls more than 1.5 x IQR above the third quartile or below the first quartile.


THE FIVE-NUMBER SUMMARY
Minimum
Q1
M
Q3
Maximum




HOW TO MAKE A BOXPLOT
A central box is drawn from the first quartile to the third.
A line in the box marks the median.
Lines (whiskers) extend from the box out to the smallest and largest observations that are not outliers.




STANDARD DEVIATION (SD) Sx AND VARIANCE S2x
Standard deviation measures the average distance of the observations from the mean. Calculated by finding an average of the squared distances and then taking the square root. This average squared distance is called the variance.


Formula: (1 / n - 1) Σ(xi - x̄)2


To find SD:
Find distances of each observation from the mean and square each.
Average these distances by dividing their sum by n - 1.
The SD is the square root of this average squared distance.


SD measures spread about the mean. ONLY USE WHEN MEAN IS MEASURE OF CENTER.
SD ALWAYS GREATER THAN OR = 0. SD = 0 ONLY WHEN THERE IS NO VARIABILITY.
SD HAS SAME UNITS OF MEASUREMENT AS ORIGINAL OBSERVATIONS.
SD NONRESISTANT.
The use of SD makes SD even more sensitive to x-bar to a few extreme observations.
- PS. YOU CAN DO THIS ON UR CALCULATOR. SEE PAGE 65 - 


CHOOSING MEASURES OF CENTER AND SPREAD
The median and IQR are usually better than the mean and SD for describing a skewed distribution or a distribution with strong outliers. Use x-bar and SD only for reasonably symmetric distributions that don’t have outliers.


Remember that a graph gives best overall picture of a distribution. Numerical measures of center and spread report specific facts about a distribution, but they do not describe its entire shape. Always plot your data.






