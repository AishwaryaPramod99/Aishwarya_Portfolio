# Visualizing Government Debt

## Part One: Working with Web-Based Visualization Tools and Data

For this exercise, I began by exploring the OECD’s government debt dataset. The dataset provides general government debt-to-GDP ratios across various countries from 1995 to 2021. Using the built-in web tool on the OECD website, I customized a bar chart to focus on the year 2021, where I could compare the debt-to-GDP ratios across countries. Below is the embedded visualization.

### Embedded Bar Chart Visualization from OECD:

<!-- Replace with iframe code if necessary or link to OECD bar chart -->

## Part Two: Working with Tableau

Next, I moved the dataset to Tableau for further analysis. After connecting the data and formatting the Time column correctly as a Date, I built a **highlight table** that allowed me to visually compare debt-to-GDP ratios across different countries over time.

I then adjusted the color palette and filtered out certain countries for a more focused analysis. The heatmap visualization helped highlight countries with extremely high debt-to-GDP ratios (above 100%) in a distinctive color, making the data easier to interpret. Below is the embedded heatmap visualization:

### Embedded Tableau Heatmap Visualization:

```html
<script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>
<tableau-viz id='tableau-viz' 
  src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt' 
  width='1152' height='547' hide-tabs toolbar='bottom'>
</tableau-viz>
