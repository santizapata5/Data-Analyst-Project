## Data Analysis project

For the present project, a complete analysis of Internet access behavior in Argentina was carried out, thanks to open data from ***ENACOM***. 

A total of 11 datasets provided by ***ENACOM*** were used. They were grouped into two categories: general and provinces, depending on whether they corresponded to the general information of the country or to the breakdown of the provinces.

The datasets of the 'general' category are:

1. Average downstream speed.
2. Distribution of technologies between Broadband and Dial Up.
3. Revenues in thousands of Argentine pesos.
4. Access per 100 households and per 100 inhabitants.
5. Average download speed, broken down by 7 ranges.
6. Technologies that are part of Broadband and Dial Up such as ADSL, Cablemodem, optical fiber, Wireless, among others.

The remaining datasets are from the category 'provinces':

1. Average download speed per province.
2. Broadband and dial up by province.
3. Access per 100 households and inhabitants per province.
4. Average download speed ranges by province.
5. Technologies (ADSL, Cablemodem, fiber, etc).

These data sets were joined according to common columns such as "Year", "Quarter", "Period", etc, in order to optimize the process of data cleaning, analysis and loading to the online visualization tool used (Looker Studio).

In the Jupyter notebooks called ***'ETL & EDA General'*** and ***'ETL & EDA Provincias'*** I use numpy, pandas and matplotlib to perform the necessary transformation, cleaning, analysis, exploration and visualization.

Subsequently the analysis report was made, with its respective dashboard and the suggested KPIs using Google's ***Looker Studio***. In the same report you can find more information about the context of the entity and the conclusions.

Link to the [***Dashboard***](https://lookerstudio.google.com/reporting/c01cc39d-e52d-4020-8b2e-668304889813)
