Objective:
To track sales data and find insights for the sales team to make better decisions and reduce time by making process automate of gathering data for visualization.

What I've Learnt
AIMS Grid: Purpose, Stakeholder, success criteria, End result

Initial analysis in MySQL:

Is there any sales amount <= 0 or currency != 'INR'? (INR: Indian currency)
Importing data, data modeling, and data cleaning and building a Dashboard in Power BI


KPIs
Revenue: sum of the amount

image

Sales Quantity: sum of quantity

image

Total Profit Margin (TPM) = sum(profit margin)

image

Profit Margin % = TPM/Revenue then select "Percentage" data type

image

Profit Margin Contribution (PMC) = TPM/TPM(All sales products, all sales customers, all markets)

For e.g total of 50 bucks profit and out of it "Delhi" brings 10 bucks profit then PMC will be (10/50)*100= 20% profit
image

Top 5 customers and products

Revenue trend

