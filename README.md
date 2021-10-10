# Amazon_Vine_Analysis
## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to select a dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.

Results: 
How many Vine reviews and non-Vine reviews were there?
The image shows below that there are 613 Vine paid reviews and 64,968 unpaid reviews.
![image](https://user-images.githubusercontent.com/86024512/136711798-57de3a11-d16a-4c12-b04f-1d7d74ca79a0.png)


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were 302543 Vine 5 star reviews and 222 non-Vine 5 star reviews.
<img width="683" alt="Screen Shot 2021-10-10 at 4 20 01 PM" src="https://user-images.githubusercontent.com/86024512/136711897-13ddc746-4d62-4b4a-a508-49e65627f885.png">
<img width="634" alt="Screen Shot 2021-10-10 at 4 20 44 PM" src="https://user-images.githubusercontent.com/86024512/136711915-8c205904-9cee-4136-b71d-762c3289bd68.png">


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
47% of 5 star reviews were non-Vine whereas 36% of 5 star reviews were Vine reviews.
<img width="761" alt="Screen Shot 2021-10-10 at 4 23 51 PM" src="https://user-images.githubusercontent.com/86024512/136711992-44f2f39e-3025-4a0f-b0bc-436be4b8ab24.png">


Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
