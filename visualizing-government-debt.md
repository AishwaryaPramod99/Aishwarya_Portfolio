| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

## Part One: Working with Web-based Visualization Tools and Data

In this section, I explored OECD's web-based visualization tool to analyze government debt. The tool allows for interactive visualizations that show government debt as a percentage of GDP across various countries and years. I experimented with the chart by highlighting specific countries and adjusting the time range. Below is the embedded interactive visualization created using the OECD tool:

<!-- Embed your first visualization from OECD -->
<iframe src="EMBED_CODE_FROM_OECD" width="600" height="400" frameborder="0"></iframe>

## Part Two: Working with Tableau

For the next part of the assignment, I downloaded the OECD government debt dataset and used Tableau to create an interactive visualization that displays the debt-to-GDP ratio over time for various countries. Below is the embedded Tableau visualization.

<!-- Embed your Tableau visualization -->
<script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>
<tableau-viz id='tableau-viz' src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt' width='1152' height='547' hide-tabs toolbar='bottom'></tableau-viz>

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

### Custom Visualization:
<!-- Embed your custom Tableau visualization -->
<script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest
