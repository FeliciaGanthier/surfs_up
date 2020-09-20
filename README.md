# **Surfs Up Analysis**

## **Overview of Project**

After a surfing trips to Hawaii, I have decided to move to Oahu and open a shop called Surf n’ Shake that will sell surfboards and ice cream to locals and tourists. Funding will come from savings and investor backing so I developed a business plan for W. Avy, a potential investor with a famous love for surfing. As a follow-up to a meeting with W. Avy, I am preparing an analysis for Oahu, the island where the shop will be located.
Using SQLite, Jupyter Notebook, VS Code and Git Hub, I will analyze the weather database W.Avy shared, starting with August 23, 2017- W.Avy’s first time surfing anniversary, that supports Oahu as the perfect location.   These tools will help me move through the analysis quickly and easily share the results. 
Since the analysis summary will also be used for a quarterly board meeting, we were careful to balance providing enough data with providing too much and Matplot Lib was used to create easy to interpret graphs that chronologically plot precipitation and temperatures so W.Avy can understand weather trends and feel good about his investment.
I ran two queries to make sure there was enough data to make an informed decision. 

•	Query 1: Determine number of stations (9)

•	Query 2: List stations from most to least active

I also used Flask to display results in a webpage so the board can easily access results with a URL. 
It is possible W.Avy will ask to duplicate the process to open other shops or if Oahu doesn’t turn out to be a good fit.  SQLite will be useful in this exercise since it is good for testing and prototyping and can be used on mobile apps.  However, the platform has some disadvantages such as fewer security features and access is limited to only the phone or computer it is stored on. 

### *Purpose of Analysis*

After the initial analysis, I was asked to narrow the focus to June and December to determine if the surf and ice cream shop business is sustainable year-round.

#### **Results**

As the charts below show:

•	The temperature in June typically is above 70 degrees with the average close to 75 degrees and highest recorded in our analysis being 85 degrees. 

•	In December, the average temperature was 71 degrees with most days recording temperatures in the mid to low 70s. The highest observed temperature in our analysis was 83 degrees. 

•	The December has recorded temperatures that may not be ideal for ice cream and surfing with a minimum of 56 degrees observed. 

![June Chart](https://github.com/FeliciaGanthier/surfs_up/blob/master/Deliverable%201.png)

![December Chart](https://github.com/FeliciaGanthier/surfs_up/blob/master/Deliverable%202.png)

##### **Summary**

I analyzed over 1500 pieces of data and determined the business is sustainable year-round, based on temperature. According to a Men’s Journal article about winter surfing, we should keep in mind ocean temperatures are often two months behind the air temperature, so the following analyses are recommended:

•	Air temperature in October, November, April and May

•	How many days the minimum temperatures were observed


