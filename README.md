# Global_food_price_inflation

This dataset sourced from Kaggle has data on Global food price inflation since 1/1/2007 to 1/10/2023.
There are two tables namely df1 and df2. We analysedd **df1** first as it provided a good oppurtunity to deduce a time-series analysis on all countries.
A time series analysis enablles us visualize patterns and trends invisible otherwise over a long period of time.
It has the following fields:

1. Open- the opening price of the food commodity that day

2. Close- closing price of the food that day

3. High- highest commodity price that day

4. Low- lowest commodity price that day

5. Inflation- the rate of increase in food prices over a given period of time.

The table had so many null values which we filled in using the mode number( most frequent) of each respective field.

ISO3 are three-letter country codes published by the International Organization for Standardization, to represent countries, dependent territories, and special areas of geographical interest.

We dropped the country field as ISO3 served us better due its short-formess.

We used the **plotly library** for visualization as it enables interactive visualization, an effect crucial to us as each day has 5 variables to focus on.

We also used **Tableau** for visualization. Tableau text file extension requires one to click on 'Raw' once you have clicked the file and then click on save to download it on your PC to view the plots.

**INSIGHTS FROM TIME SERIES ANALYSIS**

1. From 2020 majority of the countries have experienced sky rocketing food price inflation.
   Interestigly, in that period the world has experienced back to back events that have played a
   part in this. E.g., COVID-19, Ukraine-Russia war which has affected oil, wheat, urea & fertilizer prices all key determiners in final food price, Climate chage causing record droughts
   Civil wars e.g., Sudan and Afghanistan and the Debt crisis caused by increased interest rates by the US Federal Reserve for many of the countries in the dataset.

2. Inflation has eased for many nations since Dec 2022. This is from the increased interest rates hiked by USA's FDR and respective Central Banks and  increased taxes which minimized consumer spending.

3. A total of $5.12 million was spent on subsidies in 2022 by the Goverment of Somalia mainly on energy, this eased energy prices which trickle down to decreased food prices witnessed.

4. A number of measures to combat increase of food prices and inflation recurred upon research to support our analysis. These measures included;
   
    i. Creation of a 'soft landing' by Central Banks by strategically raising interest rates to minimize spending

   ii. Strategic subsidies to key inputs such as fertilizers and energy at large

  iii. Water catchment during rainfall to counter drought
  
   iv. Support of domestic cash crop farmers in planting food crops that are imported e.g., wheat and sunflower which have been badly hurt by Russia-Ukraine war.
  
   v. Increased and efficient use of budget allocation to the agriculture sector to support dry and cold storage facilities, reduce cost of inputs and spearhead irrigation schemes

   vi. Homegrown manufacturing of fertilizers and offering tax incentives to the sector so as to attract such ivestments which will cushion the country from international instabilitieslike the one in Ukraine.

   vii. Efforts in sourcing palm oil from other countries apart from Indonesia and investment in homegrown cultivation of palms will help. This is because cooking oil prices shot once Indonesia restricted palm oil exports to conserve its supplies for domestic use. Such erratic acts lead to uforeseen price hikes.

viii. Removal of VAT on food 

 As the world continues experiencing unforeseen events like Palestine-Israel war food prices will still hike due to disrupted supply chains.
 Only remedy is the goverment to take action on sustainable counter measures to cushion the country from food price inflation.
   
