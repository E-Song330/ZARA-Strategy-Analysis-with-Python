# ZARA Strategy Analysis Results

<br/>
<br/>


<img width="794" alt="스크린샷 2021-06-24 02 32 33" src="https://user-images.githubusercontent.com/85876717/123188676-b87b3100-d49c-11eb-91f0-781101d4ee3b.png">
<br/>

Map of Zara store with population choropleth
 - You can see the stores of each brand filtering it on the control box
 - Provinces with large population like Madrid, Barcelon have many stores, 
   but it seems like there is no meaningful relation in the provinces with less population (North and West province)
 - There are some inland provinces that have no zara store, while having other brands store(Kiddy's class, lefties)
  
<br/>
<br/>

<img width="767" alt="스크린샷 2021-06-24 02 34 24" src="https://user-images.githubusercontent.com/85876717/123188680-ba44f480-d49c-11eb-9ecb-5bafb69801ca.png">
<br/>

Map of GDP choropleth
  - Doesn't seem like having relation with total number of store neither (Difference in South part)

<br/>
<br/>
<img width="437" alt="스크린샷 2021-06-24 03 47 20" src="https://user-images.githubusercontent.com/85876717/123190129-4d7f2980-d49f-11eb-988d-e73a60171db5.png">

<br/>
Head rows of table 'Number of Store, #of store per 10,000 people, GDP per capita by province'
<br/>
<br/>
<img width="437" alt="스크린샷 2021-06-24 03 47 47" src="https://user-images.githubusercontent.com/85876717/123190135-4fe18380-d49f-11eb-9d4c-b5b190a7037f.png">
<br/>
Head rows of table 'Number of Each Brand Store, Total Population, GDP by province'
- Because I couldn't figure out any correlation between total number of stores and variables,
  I tried with each brands. Kiddy's class and lefties are just for pick-up service, 
  so it could be interpreted that Zara left that district to convert as online mall clients
<br/>
<br/>
<img width="582" alt="스크린샷 2021-06-24 03 49 26" src="https://user-images.githubusercontent.com/85876717/123190142-5243dd80-d49f-11eb-972f-0a2be3f62b5f.png">
<br/>
Heatmap of correlation
- Those of population and Zara, Kiddy's class & GDP and Zara, Kiddy's class reflect that are correlated (Coefficient nearly 1)
<br/>
<img width="524" alt="스크린샷 2021-06-24 03 49 51" src="https://user-images.githubusercontent.com/85876717/123190156-54a63780-d49f-11eb-8cb2-1e462cf06b2e.png">

<br/><br/><br/>
To verify the hypothesis that I mentioned on Readme, There was a very lack of data. However, visualized data show that Zara did not set up stores focusing on population, but segmented areas to be converted to online malls based on different criteria. Some provinces do not even have a single Zara store, which is being replaced by Kiddy's class and lefties, where you can order and receive Zara's products.
<br/>
If there are data such as area or sales that show the size of the store, and data on the closing and opening status of the store, more accurate verification of the hypothesis is possible.

