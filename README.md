# Mplus-Tools
Mplus is a popular statistics program which I use frequently in my work as an academic and data scientist. Mplus Tools is an Excel add-on which is designed to automate many of the time-consuming processes associated with data preparation and reporting.

In particular, Mplus Tools can:
* Create an Mplus input file from an Excel worksheet, using the first row as variable names and the second row as variable labels.
* Create an R syntax file for use with the MplusAutomation package
* Format certain types of Mplus output, including correlation tables, confirmatory factor analysis tables, regression tables, residual correlation matrices, and fit statistics, which can be easily copied into Microsoft Word
* Generate simulated datasets for Monte Carlo studies, including an Mplus input file to load the data. It can also generate batches of syntax files for use with multiple generated datasets
* Calculate additional statistics, including composite reliability and average variance extracted
* Perform chi-square difference tests, including the variations on the formula for the MLR, MLM and WLSM estimators
* Generate interaction graphs for moderated regression, including the interaction graph proposed by Preacher, Rucker and Hayes (2007)

A couple of caveats. The set of macros very much reflect the types of analysis I have been heavily involved with, namely, confirmatory factor analysis and structural models. There is limited support for multilevel analysis. Multiple group and mixture models are not yet supported.

The software comes with no guarantees. I would urge you to check any formatted output with the original output produced by Mplus.
