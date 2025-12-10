## Parker Jacobik
Hello, this is my earth data science portfolio! I am an undergrad at CU for geography and environmental studies and am most interested in working with environmental health data. I also hope to learn more about coding and mapping processes.\
I work at the Norlin Library Preservation and Conservation department mainly doing book repair, but I also restore maps and other media in the CU collections!

<img 
  src="/img/profilepic.png" 
  alt="author profile pic" 
  width="25%" >

### Contact information
 -  [pjacobik.github.io](https://pjacobik.github.io/)
 -  [paja2126@colorado.edu](paja2126@colorado.edu)

### Here's my work!

<style>
  .tab-container {
    margin-top: 20px;
  }
  .tabs {
    display: flex;
    gap: 10px;
    border-bottom: 2px solid #1FDD26;
  }
  .tab {
    padding: 8px 14px;
    cursor: pointer;
    background: #111;
    border: 1px solid #1FDD26;
    border-bottom: none;
    color: #1FDD26;
  }
  .tab.active {
    background: #1FDD26;
    color: black;
    font-weight: bold;
  }
  .tab-content {
    display: none;
    padding: 15px;
    border: 1px solid #1FDD26;
    margin-top: -1px;
  }
  .tab-content.active {
    display: block;
  }
</style>

<div class="tab-container">

  <!-- Tabs -->
  <div class="tabs">
    <div class="tab active" data-tab="sf">SF Map</div>
    <div class="tab" data-tab="denver">Denver Climate</div>
    <div class="tab" data-tab="lions">Mountain Lions</div>
    <div class="tab" data-tab="pineridge_ndvi">Pine Ridge NDVI</div>
    <div class="tab" data-tab="maricopa_ndvi">Maricopa County NDVI</div>
  </div>

  <!-- Content for each tab -->
  <div id="sf" class="tab-content active">
  <h3>SF Map</h3>
  <p>
    Map of Golden Gate Park in San Francisco, CA.
    One of my favorite third spaces in the closest city I grew up near. Going to visit the academy of sciences or having tea at the Japanese tea garden are must-tries when exploring the area! 
  </p>
  <embed type="text/html" src="img/sanfran.html" width="600" height="600">
</div>

<!-- Denver Data -->
<div id="denver" class="tab-content">
  <h3>Denver Climate</h3>
  <p>
Colorado has a temperate, but continental climate that features  hot summer days, cold winters, low precipitation, and large temperature swings from day to night and high to low altitude. Denver, and the greater metro area, face multiple impacts from climate change other than warming temperatures. The area is at risk for increased wildfires, floods, droughts, and more intense and varied storms (Colorado Climate Action). Along with these issues, the people of Denver have continually faced water scarcity, from reduced snowpacks, and unhealthy air.
    </p>
    <p>
The daily weather data used in this assignment was gathered from Denver International Airport where it is required to have accurate weather observations for aviation safety. In the first graph, you’ll see two significant gaps in the data. The first, from 1995 to 1998, is due to the weather collection site being moved from Stapleton Airport to DIA when it opened (Jones for CPR News, 2023).
    </p>
    <p>
There is another gap from 2005 to 2014 that could be explained by a number of factors from quality or equipment issues to environmental events. Many of the months where data was taken to graph had missing maximum or minimum temperature values to reflect this. The January 1995 value of 23* F reflects the record lows recorded in Denver during the abnormally cold winter. The second graph shows the trend of these temperatures over 30 years. It explains that temperatures in the Denver area have been rising over time, by about 0.18* F per year (3* F in the last 30!), and reflects the trend across Colorado where more warmer days and record highs have been experienced (Ingold for The Colorado Sun, 2023). 
  </p>
<embed type="text/html" src="img/denverdata.html" width="900" height="600">

<h4>Citations</h4>
    <ul>
      <li><a href="https://climate.colorado.gov/health-and-environmental-impacts" target="_blank">Colorado Climate Action</a></li>
      <li><a href="https://coloradosun.com/2023/09/07/denver-record-high-temperatures-chart/" target="_blank">Ingold, 2023</a></li>
      <li><a href="https://www.cpr.org/2023/01/23/denvers-official-weather-reports-come-from-dia-heres-why-and-how-you-can-help-complete-it/" target="_blank">Jones, 2023</a></li>
    </ul>
  </div>

<!-- Mountain Lion Data -->
<div id="lions" class="tab-content">
  <h3>Mountain Lions</h3>
  <p>
Mountain lions (puma concolor) have the most extensive range of any terrestrial mammal in the Western Hemisphere. They are highly adaptable apex predators that can be found from the Canadian Yukon to Southern Chile. These animals are solitary but have fairly large individual ranges that can get up to hundreds of square miles with low population density. Their activity ranges from localized foraging to long-distance dispersal in these areas (NWF, 2025).
    </p>
    <p>
Mountain lion territories vary according to the quality of habitat, availability of prey, and presence of humans. Their migration patterns are mainly influenced by where food can be found, mating opportunities, territorial dynamics, and environmental pressures from climate to seasonal change (Mountain Lion Foundation).
    </p>
    <p>
Observation data of this species is mostly collected thorough camera traps, GPS collars, and citizen science reports. These observations indicate that the species is mostly crepuscular, meaning they are primarily active at dawn and dusk. GPS studies have shown that mountain lions will move to lower elevations during the winter to hunt prey like deer or elk. Citizen observations have shown increasing activity near human-developed areas, which indicates habitat encroachment but highlights the species adaptability. Data analysis of mountain lion observation also shows that corridors connecting fragmented habitats are critical for sustaining the genetic diversity and resilience of the population (Murphy et al., 2022).
    </p>
    <p>
The first graph shows WWF ecoregions that overlap with the recorded GBIF observation data for mountain lions. Notably, many ecoregions not in the species’ native habitat are displayed. This could be because of errors in location data, animals being studied in captivity like zoos, or misidentification for example. The graph below this one displays the specific observation points of mountain lions over the previous ecoregion map for clarity. This display more accurately depicts the range of the species with two outliers. We can assume the southern most point is an error while the eastern most point could be misidentified from an asiatic lion or an actual cougar in the exotic pet trade (Fourage et al., 2025). The final map, seen below, takes the ecoregions in the Western hemisphere where mountain lions are found and displays the average amount of species observations by month. 
    </p>
<embed type="text/html" src="/img/migration_plot.html" width="900" height="900">
<embed type="text/html" src="img/bigcat_portfolio_code.html" width="600" height="600">

<h4>Citations</h4>
    <ul>
      <li><a href="https://link.springer.com/article/10.1007/s44353-025-00040-4" target="_blank">Fourage et al., 2025</a></li>
      <li><a href="https://mountainlion.org/about-mountain-lions/" target="_blank">Mountain Lion Foundation</a></li>
      <li><a href="https://www.sciencedirect.com/science/article/pii/S2351989422001111" target="_blank">Murphy et al., 2022</a></li>
      <li><a href="https://www.nwf.org/Educational-Resources/Wildlife-Guide/Mammals/Mountain-Lion" target="_blank">NWF, 2025</a></li>
    </ul>
  </div>
  
<!-- Pine Ridge NDVI Data -->
<div id="pineridge_ndvi" class="tab-content">
  <h3>Pine Ridge NDVI</h3>
  <p>
    The Oceti Sakowin, an alliance between the Lakota, Dakota, and Nakota peoples, live across the Great Plains region and have called it home for centuries. The Lakota Nation is recognized to be made of seven tribes that live in this area, specifically North and South Dakota, with the Oglala Lakota Nation residing in the Pine Ridge Indian Reservation ([Oglala Sioux Tribe](https://www.oglala.gov)). Pine Ridge is one of the largest reservations in the US, consisting of nine districts with over fifty distinct communities (Oglala Lakota Division of Behavioral Health, 2024). However, it is within some of the poorest counties in the country. This means that many inhabitants struggle with high rates of poverty and unemployment, inadequate housing and infrastructure, and lack essential health and social services (Hampton, 2016). This can be attributed to historic land dispossession, colonization, and systemic neglect that results in intergenerational trauma.
    </p>
    <p>
Even though the Northern Great Plains region is not new to temperature and weather extremes because of their distance from temperate oceans, the variability of such change is beginning to become too chaotic to handle. Since the early 2010s, the Pine Ridge community has dealt with increasingly destructive climate change. In 2011, there was severe drought and wildfires, followed by extensive flooding in 2012. A series of tornadoes was recorded in 2016, a destructive ice storm in 2018, and a bomb cyclone in 2019 (Elbein, 2019). Residents have struggled to rebuild because of the lack of federal help and frequency of disaster as more recent years have continued to see intense storms and floods.
  </p>
<embed type="text/html" src="/img/NDVI/NDVI_July_Means.html" width="800" height="500">
   <p>
The first plot above graphs the change in NDVI every July between the years of 2016 to 2022. It shows that the 2016 tornadoes worsened vegetative health but the area was quick to bounce back over the next two years. The 2018 ice storm did less damage to vegetation than it did to infrastructure, but this event served to exacerbate the total damage done by the 2019 bomb cyclone which, along with intense seasonal events, has served to tank the vegetative health of the area up until now. 
   </p>
<embed type="text/html" src="/img/NDVI/NDVI2016-2018.html" width="800" height="600">
    <p>
The second plot depicts NDVI change from 2016 to 2018 to show the vegetation difference from before and after the tornadoes and ice storms. Because the area experienced above average precipitation and milder drought conditions, more healthy plant growth could be supported after notable disasters. 
    </p>
<embed type="text/html" src="/img/NDVI/NDVI2019-2022.html" width="800" height="600">
    <p>
The third plot depicts NDVI change from 2019 to 2022 to show the vegetation difference from before and after the bomb cyclone. Because the area experienced below average precipitation and persistent heatwaves, vegetation stress rose and greenness diminished. Intense colds in winter, along with heat in summer, have caused soil moisture to decline and discourage growth in the past couple years. 
    </p>
<embed type="text/html" src="/img/NDVI/NDVI_July_Diff.html" width="800" height="600">
    <p>
The last plot depicts the change in NDVI between these two time periods during July. The negative NDVI values here can reflect reductions in grasslands because of drought impacts like increasing temperatures and decreasing rainfall. Pine Ridge vegetation is mostly dependent on these factors because the area has limited groundwater and irrigation systems in a semi-arid prairie ecosystem. 
  </p>

  <embed type="text/html" src="/img/NDVI/pric_code.html" width="600" height="600">
  
<h4>Citations</h4>
    <ul>
      <li><a href="https://news.mongabay.com/2019/07/as-climate-chaos-escalates-in-indian-country-feds-abandon-tribes/" target="_blank">Elbein, 2019</a></li>
      <li><a href="https://memoriesofthepeople.blog/2016/07/07/occupied-lands-the-great-sioux-nation" target="_blank">Hampton, 2016</a></li>
      <li><a href="https://oglalahealth.org/our-community" target="_blank">Oglala Lakota Division of Behavioral Health, 2024</a></li>
      <li><a href="https://www.oglala.gov" target="_blank">Oglala Sioux Tribe</a></li>
    </ul>
  </div>


<div id="maricopa_ndvi" class="tab-content">
  <h3>Maricopa County NDVI</h3>
  
<p>
    Temperature and NDVI research for Maricopa County, Arizona.
  </p>

</div>

<script>
  const tabs = document.querySelectorAll('.tab');
  const contents = document.querySelectorAll('.tab-content');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      tabs.forEach(t => t.classList.remove('active'));
      tab.classList.add('active');

      contents.forEach(c => c.classList.remove('active'));
      document.getElementById(tab.dataset.tab).classList.add('active');
    });
  });
</script>
