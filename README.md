# ZARA Strategy Analysis with Python


<br/>
<br/>

## Objective


Since 2015, Zara has been pushing for an omnichannel strategy by reducing the number of stores and converting customers to online malls.

If so, it means that they closed tiny stores and increased large stores that serve as showrooms, while making it possible to reduce fixed-cost and increase sales by increasing online transaction rates.

Through this work, I'm going to figure out the strategy that Zara has used.

<br/><br/>
### Hypothesis
1. Zara opened a large store, focusing on places with large populations and high GDP.<br/>
2. In the cities with a small population, would have been tiny stores or other brand stores with pick-up services for Zara online mall products.
<br/>

### Limits 

<br/>
Due to the lack of data that explains the size or sales of the store, there were limits to analyzing more relevant variables.

<br/>
<br/>

<br/>
<br/>

## Contents

The project consisted of the following steps:

1. Data collection
  * Extract source of map on the Inditex's [web](https://www.inditex.com/es/quienes-somos/inditex-en-el-mundo?p_p_id=mapsportlet_WAR_mapsportlet&p_p_lifecycle=2&p_p_state=normal&p_p_mode=view&p_p_resource_id=getTiendasByPaisAndIdCadena&p_p_cacheability=cacheLevelPage&p_p_col_id=column-1&p_p_col_count=1&idPais=11&idCadena=1) as Json file
  * Population dataset of Spain counted by pronvince, downloaded at [IGN](https://www.ign.es/web/ign/portal/rcc-nomenclator-nacional)
  * GDP dataset of Spain by province, downloaded at [INE](https://www.ine.es/jaxi/Datos.htm?path=/t35/p010/rev19/&file=02001.px)
 
2. Data Wrangling
  * Identify duplicates rows in the data frame
  * Unify the data of province
  * Select information

3. Data Visualization
  * Visualize map with layer to filter the different type of store
  * Visualize map with the data of population and GDP
  * Visualize the correlation of datas

4. Data Analysis
  * Figure out the relation between store and variables with diverse functions
  * Verify the hipothesis

<br/>
<br/>

## Stack

Jupyter notebook : ```folium```,```pandas``` etc.

<br/>
<br/>
<br/>

You can check out the [results](https://github.com/E-Song330/ZARA-Strategy-Analysis-with-Python/blob/937a6b28fa7ce975600452b5fe2d807826176fd3/Results.md)
