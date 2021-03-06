---
title: "Problem set 1"
linktitle: "Problem set 1"
date: "2021-06-14"
due_date: "2021-06-14"
due_time: "11:59 PM"
menu:
  assignment:
    parent: Problem sets
    weight: 1
type: docs
toc: true
weight: 1
editor_options: 
  chunk_output_type: console
---

<style type="text/css">
table {
  display: table;
}
</style>



**Submit this as a PDF on iCollege.** Show your work when possible.

## 1

Download this dataset (Source: [Global Consumption and Income Project](https://jackblun.github.io/Globalinc/). All incomes expressed in 2005 USD PPP.)

- [<i class="fas fa-file-excel"></i> `gcip_raw.xlsx`](/files/gcip_raw.xlsx)

1. Choose five countries you are interested in. 
1. For each of these countries, calculate the 90/10 ratio for 1980, 1990, 2000, and 2014. Look at the [step-by-step instructions in ESPP](https://www.core-econ.org/espp/book/text/01.html#exercise-12-using-excel-income-data-and-the-richpoor-ratio).
1. Include a table of these ratios in your problem set. Try plotting all four ratios for all five countries at the same time too and include that graph.
1. Speculate about country- and time-based differences between these countries. **Answer in ≈50 words.**


## 2

Download this dataset (Source: ESPP. All numbers expressed in 1990 international USD (i.e. they're all real values; you don't need to adjust for inflation or anything)):

- [<i class="fas fa-file-excel"></i> `global_income_raw.xlsx`](/files/global_income_raw.xlsx)

1. Calculate the compound annual growth rate for China, Britain, Italy, and India for the years 1750–1850, 1851–1950, and 1951–2014.
1. Include a table of these growth rates and try to plot them somehow.
1. Explain why you need to calculate the compound annual growth rate. **Answer in a sentence.**
1. Discuss the results. Which countries grew the most in which 100-year periods? Speculate about why. **Answer in ≈75 words.** 


## 3

The following table shows the nominal GDP (in 2015 US dollars) and the population of Japan in 2013 and 2014 (Source: [The World Bank](https://data.worldbank.org/)):


| Measure    | 2013                  | 2014                  |
|:-----------|:----------------------|:----------------------|
| GDP        | $4,919,563,108,372.50 | $4,601,461,206,885.10 |
| Population | 127,338,621           | 127,131,800           |

Based on this information, which of the following statements regarding GDP per capita is correct? **Explain why or why not in a sentence for each**:

1. The GDP per capita in 2013 was $36,194.41.
1. The GDP per capita fell by 6.74% between 2013 and 2014.
1. The fall in the population was enough to offset the fall in the GDP for an overall growth in GDP per capita between 2013 and 2014.
1. The GDP per capita fell by 6.31% between 2013 and 2014.


## 4



1. The consumer price index (1982–84 = 100) in December 1980 was 86.4, and it was 247.963 in December 2017 (Source: [`CPIAUCSL` from FRED](https://fred.stlouisfed.org/series/CPIAUCSL)). How much inflation has there been between 1980 and 2017?
1. In December 1980 the average price of unleaded regular gasoline was <span>\$1.34</span>; in December 2017, it was <span>$2.48</span>. (Source: [Weekly U. S. Regular All Formulations Retail Gasoline Prices](https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=EMM_EPMR_PTE_NUS_DPG&f=W) from the US EIA.) Did the price of gasoline increase or decrease in real terms over this period? By what percentage has the price of gasoline changed (in real terms) over this period? What is the implied average annual rate of growth or decline in the real price over this period?
1. In 1980 the federal minimum wage was <span>$3.10</span> per hour; today it is <span>$7.25</span>. Has its real value increased or decreased over this period? What policy and managerial implications does this have?


## 5

Download this dataset:

- [<i class="fas fa-file-excel"></i> `fred_gdp.xlsx`](/files/fred_gdp.xlsx)

Following [the examples on this page here](/resource/inflation/), do the following with this data: 

1. Create a column that shows the nominal GDP per capita for the United States.
1. Create a column that shows the real GDP per capita for the United States in 2012 dollars. You shouldn't use the CPI here. The Fed and other national agencies have a special kind of CPI-like measure for GDP called the "GDP deflator", which is included in the dataset you downloaded. The reference year for this deflator is 2012.
1. Create a column that shows the real GDP per capita for the United States in 2018 dollars.
1. Create a plot showing three lines over time: nominal GDP per capita, real GDP per capita (2012 dollars), and real GDP per capita (2018 dollars).
1. Create a column that shows the percent change between each year for one of the real GDP columns. Which year saw the biggest growth rate? Which year saw the smallest growth rate? Plot the annual percent change if you're feeling adventurous.


## 6

James Madison, a leading figure in the debates about the US Constitution after the formerly British colonies in the United States of America won the war of independence, wrote in 1788:

> In framing a government which is to be administered by men over men, the great difficulty lies in this: you must first enable the government to control the governed; and in the next place oblige it to control itself.

How does democracy (including the rule of law) address Madison’s concerns to oblige the government to "control itself"? (**≈100 words**)


## 7

Thailand and Cambodia produce rice and trucks at constant rates of product transformation (their possibility frontiers are straight lines—they don't make more or less of the product depending on how much they're currently making). In one year, Thailand could produce 1,500 tons of rice and no trucks, 500 boatloads of trucks and no rice, or any combination in between. Cambodia can produce 1,000 tons of rice or 200 boatloads of trucks, or somewhere in between. **Answer the following**:

1. Draw the production possibility frontier for each country, labeling each curve and known points.
2. Thailand can produce more of both projects than Cambodia. Can Thailand gain anything by trading with Cambodia? **Explain in ≈30 words.**
3. If the answer to #2 is yes, which ratios of trucks to rice create advantages from trade? Which ratios of trucks to rice create disadvantages from trade?
