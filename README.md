# Project Name
> Lending Clud Case Study

## Group Members:

1. Sameep Mishra (Group Facilitator) 2. Saurav Ujjain (Group Member)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information


- Analysis of the data provided by Lending Club to identify risk & opportunity areas for the organization.

- Lending Club is a money lending provider and an Analysis of the Loan Distribution is performed to minimize the financial loss & increase profitability.

- We are trying to figure below scopes
1. Find the risk area, and minimize the risk by reducing loan distribution in future.
2. Find the opportunity area, increase the growth in areas with low-risk possibilities

- Loan Distribution Data set including historical & current data sets.

### Analysis Approach

1. Data Understanding - Identify quality issues , Interpret the correct meaning of vairables (Columns)
2. Data Cleaning and Manipulation - Data (like strings and dates) are corrected to the right type to facilitate analysis , Empty (Null) value columns and variables are removed

3. Data Analysis -

a. Use univariate and Segmented Univariate analysis to identify atleast 5 drivers (Indicators) of defaults

b. Create new Derrived metrics wherever needed (whether business driven, Type driven or Data driven) to get new maningful business insights

c.Bivariate and Multivariate analysis are done to understand combination of loan default and loan success drivers which makes business sense.

Also Plot appropriate graphs with to present the results of the above types of analysis and to make it easy to draw clear insights.

4. Presentation and Recommendations - A summary of the full analysis is created in a presentation format , explaining the insgihts drawn towards the default drivers and busines loss drivers with clear actionable suggestions for improvement in default reduction and slection of better loan canditates.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The risk distribution balance can be seen in "Verification Status", the distribution has a close to 1:3 ratio on "Not Verified" & "Verified" respectively.
- The percentage of "Not Verified" should be reduced by doing more "Verified" which should help directly help in reducing approval of high-risk applications.

- In "Home_Ownership" in the "Current" data set, the loan distribution is high for people with "Mortgage".
- Customer with existing obligation(Mortage), puts an additional burden on the customer during repayment. High chance of default during the economic downfall.
- Instead, we see there is a huge opportunity space available for people with their “OWN” property. They are always traceable property state is stable.

- Geo Distribution of loans, shows the majority of loans were distributed in CA state and others states should be considered as an opportunity for expansion.
- While further analysing the above point, we provisioned the Income Vs States chart. It indicates people from other states have close to the same income as CA state.

- In "Loan Distribution Vs Purpose", it is visible the highest distribution is with "Renewal_Energy" which is fair as it provides reoccurring savings to the user so changes of default are less.
- Loan for Car should be increased as it very less risky investment since the car would be collateral.
- CreditCard & DebtConsolidation, it should consider high risk as it indicates poor financial handling of the customer.
- House should targeted as high as RenewalEnergy as collateral would be there.
- Wedding & Medical should be considered high risk as there is no collateral in both and In Medical, if customer is taking treatment for self, there is high possibility of delay\drop in repay.

- The "Income Groups Box Plot" chart indicates the majority of customers are under income bucket of less than $100000.

- In "Loan Amount Vs Amount Status", it helps us comparing the historial data with current.
- It is visible the Club has expanded distribution compared to historical loan data.

- In "Home Ownership Vs loan Status", comparison of HomeOwnership effects on Loan Status.
- People with Own homes like to default very less.
- People with Rent are high on risk.
- Sales focus should be more on people with Property own followed by Mortages.
- Multiple sales techniques like lower interest rate should be used for people with own property to increase the loan distrubution in this section.

- With "Employment Length Vs Loan Status" Chart, it compares the impact of Work Experience on Loan Status.
- It indicates the default percentage ranges betweek 13-15% in all experience buckets starting 0.5 to 10+ years of experience.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python            - version 3.8.3
- IPython(Jupyter)  - version 8.2.0
- Pandas            - version 1.4.2
- NumPy             - version 1.21.5
- SeaBorn           - version 0.11.2
- matplotlib        - version 3.5.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@sameepmishra and @sauravujjain] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->