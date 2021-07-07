# SUPERVISED-AND-UNSUPERVISED-WITH-R

2nd Work Link to Rpubs: [Link](https://rpubs.com/Raphael-Blaize/788830)


Instructions
During this week’s independent project, you will get to test the skills that you learned during this week’s sessions. Specifically, you will get the test your understanding of the following the learning outcomes of this week. 

Learning Outcomes

By the end of this week, you should be able to;

Understand and apply unsupervised learning algorithms to solving business problems.
Apply the process of dimensionality reduction to a dataset.
Deliverables

The deliverables for this week’s Independent project are as follows: 

Github repositiry containing your Markdown submission files for part 1 and part 2. 
Assessment
Part 1: Research Question

This section of the assessment covers unsupervised learning with R. 

We will revisit our last week's case study and using the learnings and the given datasets. We will be tasked to create a supervised learning model to help identify which individuals are most likely to click on the ads in the blog. 

Note that you will be required to include your last week's IP insights thus you can add a modeling section to your last week's submission submit it.  

Part 2: Research Question

This section of the assessment covers unsupervised learning with R. 

Kira Plastinina is a Russian brand that is sold through a defunct chain of retail stores in Russia, Ukraine, Kazakhstan, Belarus, China, Philippines, and Armenia. The brand’s Sales and Marketing team would like to understand their customer’s behavior from data that they have collected over the past year. More specifically, they would like to learn the characteristics of customer groups.

Perform clustering stating insights drawn from your analysis and visualizations.
Upon implementation, provide comparisons between the approaches learned this week i.e. K-Means clustering vs Hierarchical clustering highlighting the strengths and limitations of each approach in the context of your analysis. 
Your findings should help inform the team in formulating the marketing and sales strategies of the brand. 

You will create a Markdown which will comprise the following sections. 

Problem Definition
Data Sourcing
Check the Data
Perform Data Cleaning
Perform Exploratory Data Analysis  (Univariate, Bivariate & Multivariate)
Implement the Solution
Challenge the Solution
Follow up Questions
The dataset for this Independent project can be found here [http://bit.ly/EcommerceCustomersDataset].  

The dataset consists of 10 numerical and 8 categorical attributes. The 'Revenue' attribute can be used as the class label.
"Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represents the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action, e.g. moving from one page to another. 
The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 
The value of the "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. 
The value of the "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that was the last in the session.
The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 
The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 
The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.




