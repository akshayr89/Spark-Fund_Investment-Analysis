# Spark-Fund_Investment-Analysis 
Project Brief
You work for Spark Funds, an asset management company. Spark Funds wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investments so that she can take the investment decisions effectively.

 

Business and Data Understanding
Spark Funds has two minor **constraints for investments:**

-  It wants to invest between 5 to 15 million USD per round of investment

-  It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in

For the analysis, consider a country to be English speaking only if English is one of the official languages in that country

Use the Countries_where_English_is_an_official_language.pdf for the list of countries where English is an official language.

 

Before getting to specific questions, let’s understand the problem and the data first.

 

1. What is the strategy?

Spark Funds wants to invest where most other investors are investing. This pattern is often observed among early stage startup investors.

 

2. Where did we get the data from? 

We have taken real investment data from crunchbase.com, so the insights may be incredibly useful. The data is divided into the following files:

Three main data tables for the entire analysis
 companies.txt
 mapping.csv
 rounds2.csv
 

3. What is Spark Funds’ business objective?

The business objectives and goals of data analysis are pretty straightforward.

**Business objective:** The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.
**Goals of data analysis:**  goals are divided into three sub-goals:
__Investment type analysis:__ Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Spark Funds can choose the type that is best suited for their strategy.
__Country analysis:__ Identifying the countries which have been the most heavily invested in the past. These will be Spark Funds’ favourites as well.
__Sector analysis:__ Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — companies and rounds2 — have numerous sub-sector names; hence, you will need to map each sub-sector to its main sector.)
 

4. How do you approach the analysis? What are the deliverables?

The entire assignment is divided into checkpoints to help you navigate. For each checkpoint, you are advised to fill in the tables into the spreadsheet AkshayRohankar_Investments.xlsx.

 

Important Note: All the code has been submitted in one Jupyter notebook. For every checkpoint, code is written in one well-commented Jupyter notebook which have been submited also.

 


