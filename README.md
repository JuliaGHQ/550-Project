Project Goals:
In this project I want to develop a topic that discusses the relationship between the trend of online shopping(especially during pandemic) and other factors like household incomes and the frequency people view social medias. My major is Communication Data Science, so the part of online shopping really attracts me. The project I start with looking into the dataset that shows the whole e-commerce sales in US. Then slowly limited it to Los Angeles of California. You can see that from my last two datasets. Therefore, the whole project is really related to our daily life.  

Data Sources:
1.Quarterly Retail E-Commerce Sales in the USA (2011-2021)
URL: https://www.census.gov/retail/index.html

This is a government website that provides data of e-commerce sales in the USA from 2011 to 2021. The data it gives to us is in an Excel format. It is very easy to be converted to CSV file. I transform it to the dataframe format called "tsadjustedsales.csv" file. Summarize the data into 10 years, and draw graphs to see whether the trend of the e-commerce sales change during the 10 years. 

2.The Sample Income of People in 2021 in California (Los Angeles) (Scrape data)
URL: https://www.ffiec.gov/census/report.aspx?year=2021&county=037&state=06&report=demographic

This data from this government website requires scrapping. It came out like a table in the website and we need to take it from the website. Therefore web scrapping is used here to get the table. The table was taken down by the python script and reorganized with pandas to "my data.csv".

3.The number of Confirmed Covid cases in different parts of the USA（API）
API URL: https://view.inews.qq.com/g2/getOnsInfo?name=disease_foreign

To see the contagiousness and the danger of the virus through the spread of the virus in the USA. From this data to analyze how people tend to stay at home during the pandemic years. Therefore we can link to the other two data to summarize and get to the conclusion of whether people tend to use online shopping during the pandemic years.
