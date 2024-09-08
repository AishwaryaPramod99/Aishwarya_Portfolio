# Visualizing Government Debt

## Part One: Working with Web-Based Visualization Tools and Data

For this exercise, I began by exploring the **OECD’s government debt dataset**. The dataset provides general government debt-to-GDP ratios across various countries from **1995 to 2021**. Using the built-in web tool on the OECD website, I customized a **bar chart** to focus on the year **2021**, allowing for comparison of debt-to-GDP ratios across different countries.

### Embedded Bar Chart Visualization from OECD:
<!-- <script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script><tableau-viz id='tableau-viz' src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt' width='1152' height='547' hide-tabs toolbar='bottom' ></tableau-viz> -->

## Part Two: Working with Tableau

Next, I imported the dataset into **Tableau** for further analysis. After connecting the data and correctly formatting the **Time** column as a date, I created a **highlight table** to visually compare debt-to-GDP ratios across various countries over time.

I customized the **color palette** to emphasize countries with high debt-to-GDP ratios (over 100%), and filtered out specific countries for better focus. This heatmap allowed me to more easily spot countries with critical debt situations. Below is the embedded heatmap visualization from Tableau:

### Embedded Tableau Heatmap Visualization:

```html
<script type='module' src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'></script>
<tableau-viz id='tableau-viz' 
  src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt' 
  width='1152' height='547' hide-tabs toolbar='bottom'>
</tableau-viz>
```
