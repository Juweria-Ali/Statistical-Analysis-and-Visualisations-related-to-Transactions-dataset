# Statistical-Analysis-and-Visualisations-related-to-Transactions-dataset
transactions.csv contains synthetic data relating to a hypothetical research analysis on a set of
online banking transactions. The dataset has 600 instances (rows) and 8 attributes (columns).

**Attribute Description**
**id:** id is a unique transaction identifier and will play no role in the statistical analysis.

**status:** status is a categorical variable, indicating whether the transaction is the first one
made by the account holder to a given recipient.
It has 2 possible values: New or Existing

**device:** device is a categorical variable, indicating the type of computing device used by
the account holder to make the online transaction.
It has 3 possible values: PC, mobile or tablet.

**recipient:** recipient is a categorical variable, indicating the type of transaction in terms of
who the online payment was made to.
It has 4 possible values: bill, purchase, self or transfer.

**value:** value is a numerical variable representing the amount of pounds that way paid
during the online transaction.

**time:** time is a numerical variable representing the total log-in time in seconds taken to
complete the online transaction.

**model1:** model1 is a numerical variable on the scale 0-100 representing the accuracy with
which a benchmark machine learning algorithm can identify the online
transaction as being genuine or fraudulent.

**model2:** model2 is a numerical variable on the scale 0-100 representing the accuracy with
which a new machine learning algorithm can identify the online transaction as being genuine or fraudulent.

The purpose of the study for which the data has been gathered is to evaluate the effectiveness of
the new algorithm, whose accuracies are given by variable model2, relative to the performance of
the benchmark algorithm, whose accuracies are given by variable model1.
