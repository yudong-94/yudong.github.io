<head>
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-112502179-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-112502179-1');
</script>
</head>


## Data Visualization -- Makeover Monday 0423

### About Makeover Monday

[MakeoverMonday](http://www.makeovermonday.co.uk/) is a social data project:
"Each week we post a link to a chart, and its data, and then you rework the chart.
Maybe you retell the story more effectively, or find a new story in the data.
We’re curious to see the different approaches you all take. Whether it’s a simple bar chart or an elaborate infographic, we encourage everyone of all skills to partake.
Together we can have broader conversations about and with data."

Starting from Jan 08, 2018, I decided to put aside one hour on Monday weekly to create some visualization and find some insights from the data.

The datasets are published each week at: [MakeoverMonday Datasets](http://www.makeovermonday.co.uk/data/).

### Makeover Monday 0423

As the Earth's Day is coming, this week's dateset is about the Ecological Footprint. The data could be found [here](https://data.world/makeovermonday/2018w17-ecological-footprint-per-capita). And the original dashboard is [here](http://data.footprintnetwork.org/#/compareCountries?cn=all&type=EFCpc&yr=2013).
Basicially, this dataset tells how each country is performing as of the ecological footprint for each type of land. I spent much time understanding the [glossary](https://www.footprintnetwork.org/resources/glossary/).

#### My Visualization

As we know each country's Ecological Footprint Production and Consumption each year, we could identify which countries are net consumer, and which are net producter by comparing the two numbers.
Therefore, I made the classic bubble plot with diagonal reference line to show where each country is regarding ecological footprint.  


--  
<div class='tableauPlaceholder' id='viz1524537370420' style='position: relative'>
<noscript><a href='#'>
  <img alt='EF Prod vs Consumption ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeOverMonday0423&#47;EFProdvsConsumption&#47;1_rss.png' style='border: none' />
</a></noscript>
<object class='tableauViz'  style='display:none;'>
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
  <param name='embed_code_version' value='3' />
  <param name='site_root' value='' />
  <param name='name' value='MakeOverMonday0423&#47;EFProdvsConsumption' />
  <param name='tabs' value='no' />
  <param name='toolbar' value='yes' />
  <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeOverMonday0423&#47;EFProdvsConsumption&#47;1.png' />
  <param name='animate_transition' value='yes' />
  <param name='display_static_image' value='yes' />
  <param name='display_spinner' value='yes' />
  <param name='display_overlay' value='yes' />
  <param name='display_count' value='yes' />
  <param name='filter' value='publish=yes' />
</object></div>                
<script type='text/javascript'>         
  var divElement = document.getElementById('viz1524537370420');      
  var vizElement = divElement.getElementsByTagName('object')[0];        
  vizElement.style.width='800px';vizElement.style.height='827px';          
  var scriptElement = document.createElement('script');                
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';     
  vizElement.parentNode.insertBefore(scriptElement, vizElement);               
</script>  

--  

#### Insights
* Overall, both total ecological consumption and total production are increasing over time;  
* We can find the top producters and top consumers for each land type from the dashboard. For example, for crop land, Canada and Australia are top net ecological footprint producters, and Dijiboute is the top net consumer.  

--  
[⬅️Previous](https://yudong-94.github.io/personal-website/projects/data viz/MakeOverMonday20180416) [➡️Next](https://yudong-94.github.io/personal-website/projects/data viz/MakeOverMonday20180430)  

[Back to Home Page](https://yudong-94.github.io/personal-website/)
