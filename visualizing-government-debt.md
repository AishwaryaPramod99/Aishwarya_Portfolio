<div style="text-align: center; margin-bottom: 20px;">
  <a href="https://cmustudent.github.io/tswd-portfolio-templates/" style="text-decoration: none; color: #007acc;">Home Page</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="visualizing-government-debt.md" style="text-decoration: none; color: #007acc;">Visualizing Government Debt</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="critique-by-design.md" style="text-decoration: none; color: #007acc;">Critique by Design</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="final-project-part-one.md" style="text-decoration: none; color: #007acc;">Final Project I</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="final-project-part-two.md" style="text-decoration: none; color: #007acc;">Final Project II</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="final-project-part-three.md" style="text-decoration: none; color: #007acc;">Final Project III</a>
</div>
<br>
<br>

# Visualizing Government Debt

## Part One: Working with Web-based Visualization Tools and Data

In this section, I explored OECD's web-based visualization tool to analyze government debt. The tool allows for interactive visualizations that show government debt as a percentage of GDP across various countries and years. I experimented with the chart by highlighting specific countries and adjusting the time range. Below is the embedded interactive visualization created using the OECD tool:

<!-- Embed your first visualization from OECD -->
<iframe src="EMBED_CODE_FROM_OECD" width="600" height="400" frameborder="0"></iframe>

## Part Two: Working with Tableau

For the next part of the assignment, I downloaded the OECD government debt dataset and used Tableau to create an interactive visualization that displays the debt-to-GDP ratio over time for various countries. Below is the embedded Tableau visualization.

<!-- Embed your Tableau visualization -->
<script type="text/javascript">                    
  var divElement = document.getElementById('viz1657854513007');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width = '100%'; vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

<div class='tableauPlaceholder' id='viz1657854513007' style='position: relative'>
    <noscript>
        <a href='https://public.tableau.com/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt'>
        <img alt='Dashboard' src='https://public.tableau.com/static/images/Vi/VisualizingGovernmentDebt/1_rss.png'></a>
    </noscript>
    <object class='tableauViz' width='1152' height='547' style='display:none;'>
        <param name='host_url' value='https://public.tableau.com/' /> 
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='VisualizingGovernmentDebt' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
    </object>
</div>

### Process:

In Tableau, I followed these steps to create the visualization:
1. **Loaded the OECD dataset**: After downloading the dataset, I loaded it into Tableau and formatted the time column to ensure the dates were read correctly.
2. **Created a line chart**: I used the "Year" field for the X-axis and "Debt-to-GDP ratio" for the Y-axis, showing how debt has changed over time for various countries.
3. **Added color and filters**: I added color to differentiate between countries and created filters that allow the user to select specific countries for comparison.
   
### Observations:
- Countries like Greece and Japan have consistently high debt-to-GDP ratios, while others like Estonia show much lower values.
- This visualization provides a clear overview of how debt has evolved over time.

## Part Three: Create Your Own Visualization

For my custom visualization, I decided to create a **heat map** to highlight how government debt levels vary between countries across different years. I felt this visualization would provide a clear, comparative view of government debt, allowing for easy identification of countries with the highest and lowest debt-to-GDP ratios.
