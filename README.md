# Financial Services Product Case Study
A case study done for a fictional brand with a generated dataset to work on product management recommendations and machine learning skills. Note: the dataset used is too large to upload to GitHub. It can be made available upon request.

## Skills

### Languages

- Python

### Tools/Frameworks

- Scikit-Learn
- Pandas
- NumPy
- Seaborn/Matplotlib

### Other Skills

- Data-driven product recommendations
- Product case study analysis
- Machine Learning Modeling
- Logistic Regression and Random Forest Regression for classification purposes
- Model Interpretation
- Feature Selection

## Case Study Outline

Financial Services stands out as the premier financial authority. When you visit 
Financialservices.com, the reviews, guides, and educational content have been 
developed by leading personal finance experts. Financial Services’ product comparison 
tools, calculators and educational content help over 100 million consumers make 
smarter financial decisions each year. No matter where you are in your financial 
journey, Financial Services can help you reach your goals.  

One particular area in which Financial Services places a strong emphasis is mortgages, 
with the goal of advancing the visitor's decision-making journey and ultimately guiding 
them toward applying for and securing a mortgage. The mortgage team’s goal is to 
maximize revenue generated from users on our website by getting them to schedule an 
appointment with one of Financial Services’ mortgage partners. Once the appointment 
is scheduled, Financial Services gets paid a bounty (revenue). The amount depends on 
the variation of mortgage chosen for the appointment. For the purpose of this case, 
there are 4 variations (A, B, C, D), each with their own bounty associated with them.  
The customer journey is straightforward. A user visits a page on the website. Once on 
the page, they have the option to click on a banner that takes them to a form that they 
can fill out to schedule an appointment with a mortgage lender. They have the option to 
choose from four mortgage types when they schedule the appointment. 

To support this goal, the mortgage team conducted a split test, also called A/B testing, 
on various mortgage pages. This testing allows the team to compare the performance of 
website creative variations to see which one appeals more to visitors to maximize a 
targeted metric. The objective of this test was to learn which banner’s call-to-action 
(CTA) title copy and on-page placement combination will best entice visitors to click and 
enter the scheduling form in hope of increasing appointments and overall revenue.

The test has concluded and we have a data set of 100,000 decisions (rows) of the 
combination of CTA Copy and CTA placement being served randomly to users coming 
to the website. To help increase revenue per decision, we want to analyze the data for 
two purposes. One, we want to see if we have an outright winner in the split test to 
understand if we should have a new CTA combination that we show everyone. 
However, the team believes that certain groups of people may have performed 
differently based on the CTA copy and placement. If proven true and there are patterns 
in the data, we can use an algorithm to predict in real-time what CTA combination would 
be best to show to a future user to maximize the key metric. 
