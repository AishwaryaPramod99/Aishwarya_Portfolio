| [home page](https://aishwaryapramod99.github.io/Aishwarya_Portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

## Part one: Working with web-based visualization tools and data

Government Debt as a Percentage of GDP - 2023

For this part of the assignment, I used OECD data to visualize general government debt as a percentage of GDP for various countries in 2023. Here bar chart provides a clear and straightforward way to compare debt levels across nations.

The chart shows that Greece and the United States have significantly higher debt levels relative to their GDP compared to other countries. It also highlights nations with lower debt levels, such as Estonia and the OECD average, offering a comprehensive overview of global debt variation.

By visualizing the data this way, it becomes easy to identify which countries are struggling with high debt and which have managed to keep their debt levels low. This visualization is especially useful for those who need to quickly understand the global debt landscape and identify countries that may require closer economic attention.

![Part 1 Visualization](/Part1.png) <!-- Ensure the image is correctly referenced with the proper path -->

## Part two: Working with Tableau

In this section, I used Tableau to visualize government debt data spanning from 1995 to 2020. The heatmap I created effectively illustrates the debt-to-GDP ratio across various countries over time, allowing for easy comparison of trends. The color gradients highlight shifts in debt values, making it clear which periods saw significant changes.

This visualization is particularly useful in tracking long-term debt evolution. For instance, Japan’s consistent rise in debt levels over the years is evident, while other countries, like Greece, show sharp increases during specific periods. By using this heatmap, policymakers and researchers can quickly identify patterns and outliers in government debt trends.

Here is the embedded Tableau dashboard

<script type='module' 
src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'>
</script>
<tableau-viz 
  id='tableau-viz'
  src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/VisualizingGovernmentDebt/VisualizingGovernmentDebt'
  width='900'
  height='547'
  hide-tabs
  toolbar='bottom' >
</tableau-viz>

## Part three: Create your own visualization

This line graph visualizes government debt as a percentage of GDP for the top 10 OECD countries from 1998 to 2020 using data from the OECD General Government Debt Indicator.

Key customizations include:

    Distinct colors for each country, with Greece (red) and Japan (blue) highlighted for their significant debt trends.
    Thicker lines for Greece and Japan to emphasize their debt increases.
    Annotations for key moments, such as Japan’s peak debt in 2018 (238.7%) and Greece’s sharp rise around 2012.

<script type='module' 
src='https://us-east-1.online.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js'>
</script>
<tableau-viz 
  id='tableau-viz'
  src='https://us-east-1.online.tableau.com/t/aponnamp-b2a709220c/views/LineChart-Debt-to-GDPTrends/Debt-to-GDPTrendsTop10Countriesfrom1998to2020'
  width='900'
  height='547'
  hide-tabs
  toolbar='bottom' >
</tableau-viz>


## Visualization Methods Comparison

For this project, I explored different ways to visualize government debt as a percentage of GDP, like bar charts, heat maps, and line graphs. Bar charts are great for comparing debt at a single point in time, while heat maps give a nice overview of changes across multiple countries. But I found that they didn’t show year-to-year changes as clearly as I wanted.

I ended up choosing a line graph because it does a better job of showing how debt has changed over time. This made it easier to see big trends, like Greece’s sharp rise in debt around 2012 and Japan’s steady increase over the years. The line graph highlights these changes more clearly than other methods I tried.

### Color Scheme
I customized the colors to make important trends stand out. For example, I used red for Greece to highlight its big debt spike around 2012, and blue for Japan to show its steady climb in debt, which peaks in 2018. I used softer colors for countries with less dramatic changes, so the graph stays easy to read without too much going on. This way, the most important trends are easy to spot.

### Data and Source Information
The data comes from the OECD General Government Debt Indicator, which tracks how much debt countries have compared to their GDP. This is an important measure of a country’s financial health. I used the line graph to show how this ratio has changed over time for different countries, especially focusing on key points like Japan’s peak debt and Greece’s debt crisis. The interactive graph also lets you hover over the lines to see specific values for each year.
