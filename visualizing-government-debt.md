# Visualizing Government Debt

## Part One: Working with Web-Based Visualization Tools and Data

For this exercise, I began by exploring the **OECD’s government debt dataset**. The dataset provides general government debt-to-GDP ratios across various countries from **1995 to 2021**. Using the built-in web tool on the OECD website, I customized a **bar chart** to focus on the year **2021**, allowing for comparison of debt-to-GDP ratios across different countries.

### Embedded Bar Chart Visualization from OECD:
<!-- <script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt' width='1152' height='547' hide-tabs toolbar='bottom' ></tableau-viz> -->

## Part Two: Working with Tableau

Next, I imported the dataset into **Tableau** for further analysis. After connecting the data and correctly formatting the **Time** column as a date, I created a **highlight table** to visually compare debt-to-GDP ratios across various countries over time.

I customized the **color palette** to emphasize countries with high debt-to-GDP ratios (over 100%), and filtered out specific countries for better focus. This heatmap allowed me to more easily spot countries with critical debt situations. Below is the embedded heatmap visualization from Tableau:

### Embedded Tableau Heatmap Visualization:

<script type='text/javascript'>
  var divElement = document.getElementById('vizcd066ccb-e9dd-434b-ad8a-0165401a6a50'); 
  var vizElement = divElement.getElementsByTagName('object')[0]; 
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; 
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement); 
</script>

<div class='tableauPlaceholder' id='vizcd066ccb-e9dd-434b-ad8a-0165401a6a50' style='position: relative; width: 100%; height: 600px;'>
  <noscript><a href='#'><img alt='Tableau Visualization' 
      src='https://public.tableau.com/static/images/your_image_link_here.png' style='border: none' /></a></noscript>
  <object class='tableauViz' width='100%' height='600' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='cd066ccb-e9dd-434b-ad8a-0165401a6a50' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='your_image_link.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
  </object>
</div>

