---
layout: default
---

## New York Shootings (2006-2024)

### Introduction: NYC Shootings Over the Years

<div style="text-align: justify;">
<b>Gun violence</b> is a chronic problem in US cities, disrupting communities and fuelling a cycle of trauma and fear. This analysis provides a comprehensive overview of such incidents in New York from 2006 to 2024, revealing interesting trends and details. <b>Over time</b>, shootings are expected to decrease due to enhanced educational efforts and effective state intervention. Indeed, the general <b>trend</b> for NYC from 2006 onwards has been thankfully <b>downward</b>. However, it's important to note a highly <b>significant spike</b> in <b>2020</b>, continuing into <b>2021</b>. Therefore, our analysis will focus on this event to determine whether it represents an <b>anomaly</b> or the onset of an alarming <b>new trend</b>.
</div>
      

<iframe src="/data/shootings_by_year.html" width="100%" height="600px"></iframe>

### 2020: A Time of Generalized Unrest


<div style="text-align: justify;">
Taking a closer look at <b>2020</b> and comparing it to previous years, we observe that it follows a similar <b>seasonal pattern</b>, with a bell curve peaking in the summer months. However, the increase in 2020 was notably <b>abrupt</b>. The unique circumstances of 2020, marked by the COVID-19 <b>pandemic</b> and the <b>Black Lives Matter protests</b> in th US, set it apart as a highly unusual year. Notably, the first significant <b>rise</b> in shootings occurred in <b>March</b>, coinciding with the initial COVID-19 <b>lockdown</b> and the murder of <b>George Floyd</b>. The year 2021 saw a continuation and aftermath of this spike, whereas by 2022, shooting incidents had returned to average levels.
</div>
<iframe src="/data/carousel.html" width="100%" height="600px"></iframe>
<div style="text-align: justify;">
To explore whether the <b>Black Lives Matter</b> protests <b>influenced</b> the levels of gun violence, we examined the <b>racial distribution of shooting victims</b>. Despite the exponential increase in shooting incidents, this distribution remained <b>consistent with previous years</b>, suggesting that while the protests may have contributed to overall unrest, the surge in shootings was <b>not racially motivated</b>.
</div>
<br>
<div style="text-align: justify;">
Turning our attention to the likely predominant factor behind many of 2020's challenges, COVID-19, considering the <b>pandemic's broader impact</b>, which includes a global <b>increase in serious crimes</b><sup><a href="#ref1">1</a></sup>. Although definitive conclusions are difficult, the <b>trends in gun violence</b> appear to <b>align</b> with those of another pandemic-related issue: <b>layoffs</b>. Google search trends for 'layoffs' in New York City peaked in May and August of 2020, with the initial surge beginning in March, <b>mirroring</b> the timing of increased shootings and coinciding with the first lockdowns. The decline in searches during June and July aligns with the typical slowdown in business activity during the summer months.
</div>




### Shootings Hotspots Accross Time: A Socio-Economic View

<div style="text-align: justify;">
Even though we have concluded that the <b>spike of 2020</b> was an <b>once-off extreme occurrence</b> it still brough to light the tight relation between the economical situation< of the population and serious crime occurrences. When gun violence rose to these unprecedented levels the least privileged members of the city's landscape were gravelly and irreparably affected, allowing us to draw a generalized correlation between the <b>financial and social conditions</b> of a community and the <b>number of shooting incidents</b> within it. 

The figure bellow showcases how the <b>concentration</b> of these incidents remains quite <b>stable over the years</b> for some specific police precincts of <b>Bronx, Brooklyn and Queens</b>, communities known for their great <b>minority</b> populations concentration.
</div>

<iframe src="/data/maps/maps.html" width="100%" height="600px"></iframe>

<div style="text-align: justify;">
To better understand why exactly more gun incidents occur in these areas, we need to examine <b>additional datasets</b> that highlight the <b>economic situations</b> of the population within those communities. Plotting descriptors such as unemployment rate, poverty, and community distrust on the map of community districts we can observe a striking <b>similarity</b> to the <b>distribution of gun violence</b> incidents. 
</div>

<iframe src="/data/maps/other_maps.html" width="100%" height="600px"></iframe>

<br>
<div style="display: flex; text-align: justify; justify-content: space-between;">
  <div style="width: 300px; padding-right: 20px;">
    <p>
      We observe that economically disadvantaged communities, which often exhibit higher rates of gun violence, also tend to have a high concentration of minority populations. The correlation between poverty and gun violence leads to the expectation that most of this <b>violence</b> occurs <b>within these communities</b> themselves, with both perpetrators and victims typically belonging to the <b>same demographic</b>. This pattern aligns with sociological theories concerning the intraracial nature of crime<sup><a href="#ref2">2</a></sup> and underscores the contemporary repercussions of segregation and the historical poverty of minority communities in the United States.
    </p>
  </div>
  <div style="flex: 1;">
    <iframe src="/data/confusion_matrix_interracial_shootings copy.html" width="100%" height="80%"></iframe>
  </div>
</div>

### Conclusion
<div style="text-align: justify;">
The data reveals that while <b>shootings</b> in New York City have <b>generally declined</b>, the abrupt <b>spike in 2020</b> underscores the significant <b>socio-economic impact of the COVID-19 pandemic</b> and widespread unrest. The data also highlights a persistent <b>correlation</b> between gun violence and <b>economically disadvantaged communities</b>, particularly affecting <b>minority</b> populations. Addressing this issue requires a concerted focus on alleviating economic disparities to break the cycle of violence and foster safer neighborhoods.
</div>
<br>

<hr>

### References
  <ol>
    <li id="ref1">Boman, J.H. and Gallupe, O., 2020. Has COVID-19 changed crime? Crime rates in the United States during the pandemic. American journal of criminal justice, 45, pp.537-545.</li>
    <li id="ref2">Baker, R.S., 2022. The historical racial regime and racial inequality in poverty in the American South. American Journal of Sociology, 127(6), pp.1721-1781.</li>
  </ol>

### Dataset Utilized
1. <a href="https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data">NYPD Shooting Incident Data (Historic)</a>
2. <a href="https://trends.google.com/trends/explore?cat=16&date=2020-01-01%202020-12-31&geo=US-NY-501&q=layoffs">Google Trends: Layoffs 2020</a>
3. <a href="https://data.cccnewyork.org/data/table/97/total-population?fbclid=IwAR2v8QJeP_iLNLYQF2w21PxuhnMvIcpCzK8UhyITSC9IINTYKgB7nAI_PEQ#84/130/127/a/a"> Citizens Committee for Children of New York - Totla Population</a>
4. <a href="https://data.cccnewyork.org/data/map/99/poverty?fbclid=IwAR2YGgDIP3ShXNVKEOWAP20yVgw5jz7fUcXaVGjp3HITsxayE66bdLY5J70#101/11/3/154/62/a/a"> Citizens Committee for Children of New York - Poverty</a>
5. <a href="https://data.cccnewyork.org/data/map/85/unemployment-rate?fbclid=IwAR1LCh86FOWYxY-E8r-tsgtj8Jair311Ee5QkIGWaBBJ9IlJdrxMRYmkbIs#85/a/3/131/127/a/a"> Citizens Committee for Children of New York - Unemployment Rate</a>
6. <a href="https://data.cccnewyork.org/data/table/1312/community-trust?fbclid=IwAR0J7CMG8WEDz-HC6FziJIt_ZNB_BZaZYvuNUXtZkkqlfzu3HRq8kLIffbQ#1312/1531/128/a/a"> Citizens Committee for Children of New York - Community Trust</a>


### Explainer notebook
The GitHub link to our explainer notebook is <a href="https://github.com/IoannisTselios/final_project_social_data/blob/main/Final.ipynb?fbclid=IwAR15LznPBVLaLA_PV5hVIsbR6BJ2tms_yNlO2qKI1UQ3G25umZoKGqSxkFQ">here</a>. The outputs have been deleted to coply with GitHub's file size requirements. 

<hr>


### Contridutions Table

|                     | Artemis Doumeni (s234061)| Ioannis Tselios (s233516) | Mario Medoni (s204684) |
| ------------------- | --------------- | --------------- | ------------ |
| Dataset Exploration | 15%             | 70%             | 15%          |
| Website             | 15%             | 70%             | 15%          |
| Story               | 70%             | 0%              | 30%          |
| Jupyter Notebook    | 10%             | 50%             | 40%          |
| Time series plots   | 80%             | 0%              | 20%          |
| Map plots           | 10%             | 10%             | 80%          |


