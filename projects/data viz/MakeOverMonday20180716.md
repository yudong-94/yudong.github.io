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


## Data Visualization -- Makeover Monday 0716

### About Makeover Monday

[MakeoverMonday](http://www.makeovermonday.co.uk/) is a social data project:
"Each week we post a link to a chart, and its data, and then you rework the chart.
Maybe you retell the story more effectively, or find a new story in the data.
We’re curious to see the different approaches you all take. Whether it’s a simple bar chart or an elaborate infographic, we encourage everyone of all skills to partake.
Together we can have broader conversations about and with data."

Starting from Jan 08, 2018, I decided to put aside one hour on Monday weekly to create some visualization and find some insights from the data.

The datasets are published each week at: [MakeoverMonday Datasets](http://www.makeovermonday.co.uk/data/).


### Makeover Monday 0716

This week's topic is about NBA Player Salary since the Season 1990-1991. It includes the salary of each player on each team in each season.  
You can find the original viz [here](https://www.whatsthecap.com/nba/salary-cap/). The basic idea is that, the salary cap has been increasing, but meanwhile, average payroll has always been above the cap.   

#### My Visualization

I made a very simple viz of scatter plots with a trendline showing how the median team salary has been increasing. Also, when you hover on the data points, you will see the team info, and the top 5 highest-salary players on that team in that season. Btw, I am not a big NBA fan, so I do not include the cap info, as I am not sure what it actualy means...  

--  
<div class='tableauPlaceholder' id='viz1531796266340' style='position: relative'>
<noscript><a href='#'>
  <img alt='NBA Player Salary Growth ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeOverMonday0716&#47;NBAPlayerSalaryGrowth&#47;1_rss.png' style='border: none' />
</a></noscript>
<object class='tableauViz'  style='display:none;'>
  <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
  <param name='embed_code_version' value='3' />
  <param name='site_root' value='' />
  <param name='name' value='MakeOverMonday0716&#47;NBAPlayerSalaryGrowth' />
  <param name='tabs' value='no' />
  <param name='toolbar' value='yes' />
  <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MakeOverMonday0716&#47;NBAPlayerSalaryGrowth&#47;1.png' />
  <param name='animate_transition' value='yes' />
  <param name='display_static_image' value='yes' />
  <param name='display_spinner' value='yes' />
  <param name='display_overlay' value='yes' />
  <param name='display_count' value='yes' />
  <param name='filter' value='publish=yes' />
</object></div>              
<script type='text/javascript'>    
  var divElement = document.getElementById('viz1531796266340');              
  var vizElement = divElement.getElementsByTagName('object')[0];           
  vizElement.style.width='800px';vizElement.style.height='627px';          
  var scriptElement = document.createElement('script');                   
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';   
  vizElement.parentNode.insertBefore(scriptElement, vizElement);              
</script>  

--  

#### Insights
* The team median salary has been increasing all the way since 1990. The average team median salary (...) has been 4x since 1990;    
* The range of team median salary is also increasing - salary difference has been larger and larger among teams.  

--  
[⬅️Previous](https://yudong-94.github.io/personal-website/projects/data viz/MakeOverMonday20180709) [➡️Next](https://yudong-94.github.io/personal-website/projects/data viz/MakeOverMonday20180723)  

[Back to Home Page](https://yudong-94.github.io/personal-website/)
