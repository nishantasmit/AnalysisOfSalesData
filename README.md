# AnalysisOfSalesData

This project covers data cleaning, data analysis and data visualization process using Microsoft excel, and this is the project’s documentation.

The major aim of this project is to communicate insights via an interactive dashboard determining the demographic factors that influences bike purchases. I will be using bicycle buyers’ different demographics to gather my insights and give recommendations.

Data Collection
The dataset was downloaded from GitHub. The link to the dataset was provided by Alex the Analyst, a mentor in the data community. The dataset was downloaded and converted to excel sheet.
Data Cleaning and Processing
Data cleaning is one of the most important aspect of data processing and is very important to avoid any mistake that could trigger Data bias which can cause errors in the analysis.

I imported the dataset into Microsoft excel then i copied and pasted into a new sheet. The purpose of copying into a new sheet is in case of an error so it can be traced back to the original sheet.

Here are the steps i took to clean the data.

1,I removed the duplicated values by selecting the table, going to data to select remove duplicates, select all columns then press ok. 26 duplicates were removed in total leaving only the unique values.
2.The Marital Status column values were replaced and denoted as follows; M=Married and S=Single. This was done by pressing CTRL +H which opens the Replace Menu that allows all values to be replaced at a go.
The same formular used to replace and denote Marital column was used for gender column.

4. The data type of the Income column was changed from general to currency.
5. A new column (Age Bracket) was created to group the ages in ranges, Adolescent, Middle Age and Old using the Nested IF function.

Data Analysis
Analysis was done using PIVOT TABLE and PIVOT CHARTS in Excel. Following the tutorial video used for this analysis, three tables were originally created to summarize my data, make it easier to understand and give answers to the shown metrics.

Data Visualization
A simple interactive dashboard report was created using PIVOT CHARTS, then I inserted slicers to filter the dashboard by Education, Occupation and Children.

Insights
Male Bike buyers with higher income purchased more bikes compared to females with slightly lower income who did not purchase.
Customers with the least commute (1 mile) own more bikes.

Middle aged people between 31–54 own more bikes than others.

North America has more customers purchase compared to Pacific and Europe region.

Married people purchased 7% more bikes than single people.

Recommendations
Based on the insights above, I would recommend that bike manufacturers and retailers focus their marketing efforts on male customers with higher income, as they are more likely to purchase bikes. Additionally, middle-aged people between 31–54 should also be targeted as they own more bikes compared to other age groups. Manufacturers and retailers should also consider the commuting distance of potential customers, as those with shorter commutes are more likely to own multiple bikes. Furthermore, the North American market should be a priority as it has more customers purchasing bikes compared to the Pacific and Europe regions. Finally, it is worth noting that married people purchased more bikes than single people, suggesting that family-oriented marketing strategies may be effective.

However, to increase sales, efforts should be made by applying SMART (specific, measurable, achievable, relevant and time-bound) objectives and marketing strategies to convert those who didn’t purchase bikes into customers, especially in the Pacific and Europe regions.
