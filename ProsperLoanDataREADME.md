# Prosper Loan Data Exploration
## by Nicole Wambui


## Dataset

The dataset was information on 113,937 loans including information about the loans and different borrower metrics like employment, income etc. There are 81 variables discussed in total. The the entire dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000) and the explanation of the different variables can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing).

## Summary of Findings

Throughout the exporation, it was clear that income was a great predictor in the loan amount disbursed to the borrower. There were statistics on monthly income and yearly income which indicated those with higher earning were able to receive higher loan limits and amounts. It was interesting to see that there were a number of borrowers (although it was a small subset of the data) that were able to secure loans without having verfiable income. Across the board, this category of borrowers (regardless of their stated income range) received lower loan limits for each listing category apart from where the reason for loan application was not specified. This seems to indicate a loopole where borrowers with no verifiable income are able to secure loans by not stating the reason for loan application.

Borrowers between the income range of $50,000 and $74,999 applied the most for loans. Across all income ranges, the largest reason for loan application was debt consolidation. This presents an interesting discovery, as the borrowers are acquirin more debt to secure other debts. I would have assumed that such borrowers would be much less likely to be able to secure loans but it could be that htis is part of the organisation's business model and they have a way of ensuring that their business remains profitable.


## Key Insights for Presentation

- The key insights I would like to go into are how borrowers with nonverifiable income are able to secure loans and what categories they are able to secure loans for. I would like to zoom in on the "Not available" loan category and figure out how many delinquency rates and amounts fall under this category.

- It was interesting to note that people with non-verfiiable income were more likely to make payments on time and less likely to default than those with verifiable incoem, even after accounting for proportion. I would like to delve deeper into this and figure out why this would be so.

- Apart from income, the listing category seems to be a key metric used to determine the borrowers' creditworthiness. I would also like to go into listing category 8, 9, and 0 ("Baby & Adoption", Boat" and "Not Available", respectively) to figure out the delinquent amounts and  see why there is a difference between the income groups (verifiable and non-verifiable) and why that could be.

- I will be using the same visualisations as used previously but my explanatory analysis will be focused on delinquent amounts, loan amounts, income groups (verifiable and non verifiable) and the listing category. These metrics seem to have provided the most interesting insights throughout the exploration and will be discussed further in teh next part of the presentation.