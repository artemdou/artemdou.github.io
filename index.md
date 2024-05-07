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
Even though we have concluded that the spike of 2020 was an once-off extreme occurrence it still brough to light the tight relation between the economical situation of the population and serious crime occurrences. When gun violence rose to these unprecedented levels the least privileged members of the city's landscape were gravelly and irreparably affected, allowing us to draw a generalized correlation between the financial and social conditions of a community and the number of shooting incidents within it. 

The figure bellow showcases how the concentration of these incidents remains quite stable over the years for some specific police precincts of Bronx, Brooklyn and Queens, communities known for their great minority populations concentration.
</div>

<iframe src="/data/maps/maps.html" width="100%" height="600px"></iframe>

<div style="text-align: justify;">
To better understand why exactly more gun incidents occur in these areas, we need to examine additional datasets that highlight the economic situations of the population within those communities. Plotting descriptors such as unemployment rate, poverty, and community distrust on the map of community districts we can observe a striking similarity to the distribution of gun violence incidents. 
</div>

<iframe src="/data/maps/other_maps.html" width="100%" height="600px"></iframe>

<br>
<div style="display: flex; text-align: justify; justify-content: space-between;">
  <div style="width: 300px; padding-right: 20px;">
    <p>
      We observe that economically disadvantaged communities, which often exhibit higher rates of gun violence, also tend to have a high concentration of minority populations. The correlation between poverty and gun violence leads to the expectation that most of this violence occurs within these communities themselves, with both perpetrators and victims typically belonging to the same demographic. This pattern aligns with sociological theories concerning the intraracial nature of crime<sup><a href="#ref2">2</a></sup> and underscores the contemporary repercussions of segregation and the historical poverty of minority communities in the United States.
    </p>
  </div>
  <div style="flex: 1;">
    <iframe src="/data/confusion_matrix_interracial_shootings copy.html" width="100%" height="80%"></iframe>
  </div>
</div>

### Conclusion
<div style="text-align: justify;">
The data reveals that while shootings in New York City have generally declined, the abrupt spike in 2020 underscores the significant socio-economic impact of the COVID-19 pandemic and widespread unrest. The data also highlights a persistent correlation between gun violence and economically disadvantaged communities, particularly affecting minority populations. Addressing this issue requires a concerted focus on alleviating economic disparities to break the cycle of violence and foster safer neighborhoods.
</div>

### References
  <ol>
    <li id="ref1">Boman, J.H. and Gallupe, O., 2020. Has COVID-19 changed crime? Crime rates in the United States during the pandemic. American journal of criminal justice, 45, pp.537-545.</li>
    <li id="ref2">Baker, R.S., 2022. The historical racial regime and racial inequality in poverty in the American South. American Journal of Sociology, 127(6), pp.1721-1781.</li>
  </ol>

### Dataset Utilized
1. <a href="https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data">NYPD Shooting Incident Data (Historic)</a>
2. <a href="https://trends.google.com/trends/explore?cat=16&date=2020-01-01%202020-12-31&geo=US-NY-501&q=layoffs">Google Trends: Layoffs 2020</a>


### Explainer notebook
The GitHub link to our explainer notebook is here.


