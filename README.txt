This replication package contains data used in the submission: "A Large-Scale Empirical Study on Code-Comment Inconsistencies".

The rq1 folder contains:
    |
    |__systems.csv: This csv file contains the list of 1,500 GitHub projects mined in RQ1.

    |
    |__ statistical-analysis-method-comments.csv: This csv file reports the results of the statistical analysis (Fisher test and OR) when comparing the chances of  different categories of code changes to trigger methods' comments updates. The 1st column reports the two compared categories, the 2nd the p-value, the 3rd the OR, the 4th the lower bound of the 95% confidence interval for the OR, and the 5th the upper bound of the 95% confidence interval for the OR.

    |
    |__ statistical-analysis-class-comments.csv: This csv file reports the results of the statistical analysis (Fisher test and OR) when comparing the chances of  different categories of code changes to trigger class's comments updates. The 1st column reports the two compared categories, the 2nd the p-value, the 3rd the OR, the 4th the lower bound of the 95% confidence interval for the OR, and the 5th the upper bound of the 95% confidence interval for the OR.

    |
    |__ast-level-changes.txt: Instructions on how to get our database containing the 1.3 Billion AST-level changes extracted with GumTreeDiff.


The rq2 folder contains:
    |
    |__keywords-metching-analysis.txt: explaining how we defined the lexical pattern used to identify commits likely fixing code-comment inconsistencies (i.e., those used in RQ2).

    |
    |__tagged-commits.csv: The list of 500 tagged commits.
