## Call Centre Data Analytics -Power BI

---
![Github Logo](https://github.com/sheena-k/call_centre_powerbi/blob/main/callcentre.png)
--- 
The aim of the task is to create a dashboard using Microsoft Power BI tool that visualize all relevant Key Performance Indicators (KPIs) and Metrics in the dataset.The dashboard uncovers hidden trends of customers and call centre agents behavior which will help management to get insights on business stratergies.
---
### DATA ANALYSIS XPRESSION
---
#### Measures used in analysis
---
* **Total Calls = DISTINCTCOUNT(call_centre[Call Id])**

* **Answered Calls = CALCULATE(COUNTROWS(call_centre), call_centre[Answered (Y/N)] = "Y")**

* **Unanswered Calls = CALCULATE(COUNTROWS(call_centre), call_centre[Answered (Y/N)] = "N")**

* **Avg Speed of Answers = AVERAGE(call_centre[Speed of answer in seconds])**

* **Avg statisfaction rating = AVERAGE(call_centre[Satisfaction rating])**

* **Percentage Unresolved = [unresolved calls]/[Total Calls]**

* **Percentage resolved = [resolved calls]/[Total Calls]**

* **resolved calls = CALCULATE(COUNTROWS(call_centre), call_centre[Resolved]= "Y")**

***unresolved calls = CALCULATE(COUNTROWS(call_centre), call_centre[Resolved]= "N")**

