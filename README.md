# kickstarter-analysis

## Overview of Project
The main purpose of the analysis is to provide statistics to louise about theater outcomes based on their startup date and goal amounts from the crowdfunding datasheet. As she wants to start a fundraise of amount 12000 for her upcoming play called fever. The report will also uncover any hidden trends in the data.
## Analysis and Challenges
### Analysis
According to the analysis [theater category](https://drive.google.com/file/d/1d30cXQQSBEEe_8QyzBORpd8f8IoYwCWh/view?usp=sharing) has the higher success rate as compared to the rest of the categories.The datasheet analysis [based on launch dates](https://drive.google.com/file/d/137ka_v8zpgLqdGKaUsv7dfik7_-UvbHn/view?usp=sharing) shows that there is a spike in success rate in the month of May. After that for the upcoming months the number of successful startups tend to decline. In addition to this outcomes [based on goals](https://drive.google.com/file/d/1o-fatNsq-2W8j_e4vGpzOylLEPlCPBI1/view?usp=sharing) identify that startup projects with lower amount of expectation goals are higher in success.


### Challenges

- The first difficulty was faced in percentage funded column when I used the conditional formatting. Due to some outliers present in the datasheet the color looked  the same with a slightly difference. To correct this I edited the conditional formatting rule from maximum to percentile. 
- Second difficulty was in the average donation column when an error occurred where the value was zero to solve this is I used iferror() function. 
- Despite some of the difficulties and challenges the overall experience was good throughout the journey. 


## Results
### Conclusions Based on Launch Dates
- According to the launch dates the analysis shows that the fundraising started in May and June has higher success rate for startup projects.
- Where second outcome shows that December is the only month with least number of plays as compared with rest of the months.

### Conclusion Based on Goals
- The outcome based on project goals identify that higher success rate are for those startups which had their initial goal under 5000 following the lower tendency to fail. However projects between the amount of 5000 to 20000 has 50-50 chance of success and fail.
### Summary of the Limitations
- The limitations of the dataset are that it is to big to examine without the help of pivot table and charts and also there are some outliers which affects the conclusions.
- The recommendation for additional table is the plays outcomes based on number of backers. 
