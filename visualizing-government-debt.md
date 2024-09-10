| [home page](https://aishwaryapramod99.github.io/Aishwarya_Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

## Part one: Working with web-based visualization tools and data

For this part of the assignment, I used OECD data to visualize general government debt as a percentage of GDP in 2023. I chose to create a bar chart, which effectively represents the debt levels of various countries, allowing for easy comparison across nations.

The visualization shows the percentage of GDP attributed to government debt for each country, with Greece and the United States showing significantly higher debt levels compared to other countries. The chart also includes countries with lower debt levels, such as Estonia and the OECD average country, providing a comprehensive overview of how government debt varies across different regions.

By visualizing the data in this way, it is easy to see which countries are struggling with high debt relative to their GDP and which countries have managed to maintain lower debt levels. This type of visualization is useful for policymakers, economists, and researchers who want to quickly understand the global debt landscape.

![Part 1 Visualization](/Part1.png) <!-- Ensure the image is correctly referenced with the proper path -->

## Part two: Working with Tableau

In this section, I used Tableau to visualize government debt data over time, focusing on the debt-to-GDP ratio across different countries from 1995 to 2019. The heatmap I created makes it easy to compare trends in debt levels, with the color gradients indicating changes in debt values over time. This visualization effectively shows how government debt evolved in each country and highlights countries with particularly high or low levels of debt during specific periods.

Here is the embedded Tableau dashboard:::::::::::::::

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz0000000000000');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt';  
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Part three: Create your own visualization

The line graph effectively shows how debt-to-GDP ratios for the top 10 countries have changed over time. Unlike bar charts or heat maps, it highlights long-term trends, such as Greece's debt crisis and Japan's steady increase. This visualization makes it easy to compare countries and see how debt levels have evolved from 1998 to 2020.

{% raw %}
<script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>

{% raw %}
<script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>

<tableau-viz 
    id='tableau-viz' 
    src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt' 
    width='1152' 
    height='547' 
    hide-tabs 
    toolbar='bottom'>
</tableau-viz>
{% endraw %}
