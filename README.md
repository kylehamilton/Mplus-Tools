# Mplus-Tools
Mplus is a popular statistics program which I use frequently in my work as an academic and data analyst. While very powerful, it comes with a few annoyances for its users. One is that it doesn’t have any data editing facility, as SPSS and other statistical programs have.

Another is that data files are not allowed to have variable headings, and that variable names must be manually added to the syntax file. As well as being a nuisance, this can be plain dangerous if the variables in this list are mislabelled or accidentally omitted.

Mplus also formats most of its output as a text file. Transforming the output to a usable format, such as a journal article or or other publication, can be quite time consuming.

Based on these concerns, I created a series of Excel macros, which I refer to as Mplus Tools. Mplus Tools can automate many of the time consuming processes associated with data preparation and reporting. In particular, Mplus tools can:

* Create an Mplus input file from an Excel worksheet, using the first row as variable names
* Format certain types of Mplus output, including correlation tables, confirmatory factor analysis tables, regression tables, residual correlation matrices, and fit statistics, which can be easily copied into Microsoft Word
* Generate simulated datasets for Monte Carlo studies, including an Mplus input file to load the data. It can also generate batches of syntax files for use with multiple generated datasets.
* Calculate additional statistics, including composite reliability and average variance extracted
* Perform chi-square difference tests, including the variations on the formula for the MLR, MLM and WLSM estimators
* Generate interaction graphs for moderated regression, including the interaction graph proposed by Preacher, Rucker and Hayes (2007)

A couple of caveats. The set of macros very much reflect the types of analysis I have been heavily involved with, namely, confirmatory factor analysis and structural models. The code works less well for multilevel analyses, and I have not even attempted to write any code to format the output of mixture models.

The code still has a number of bugs in it, which I will attempt to iron out. The software comes with no guarantees, and I would urge you to check any formatted output with the original output produced by Mplus.
