<div style="text-align: center; margin-bottom: 20px;">
  <a href="https://cmustudent.github.io/tswd-portfolio-templates/" style="text-decoration: none; color: #007acc;">Home Page</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="visualizing-government-debt.md" style="text-decoration: none; color: #007acc;">Visualizing Government Debt</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="critique-by-design.md" style="text-decoration: none; color: #007acc;">Critique by Design</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="final-project-part-one.md" style="text-decoration: none; color: #007acc;">Final Project I</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="final-project-part-two.md" style="text-decoration: none; color: #007acc;">Final Project II</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="final-project-part-three.md" style="text-decoration: none; color: #007acc;">Final Project III</a>
</div>
<br><br>

# Visualizing Government Debt

## Part One: Working with Web-based Visualization Tools and Data

In this section, I explored OECD's web-based visualization tool to analyze government debt. The tool allows for interactive visualizations that show government debt as a percentage of GDP across various countries and years. I experimented with the chart by highlighting specific countries and adjusting the time range. Below is the embedded interactive visualization created using the OECD tool:

<!-- Embed your first visualization from OECD -->
<iframe src="EMBED_CODE_FROM_OECD" width="600" height="400" frameborder="0"></iframe>

## Part Two: Working with Tableau

For the next part of the assignment, I downloaded the OECD government debt dataset and used Tableau to create an interactive visualization that displays the debt-to-GDP ratio over time for various countries. Below is the embedded Tableau visualization.

### Tip for Embedding in GitHub
To get the Tableau visualization to render correctly on GitHub, you'll have to do a bit of editing of the code block once you paste it into your new markdown page. To do so, hit enter/return wherever you see big blocks of spaces between the lines. Usually, you will find these after the “;” (or other logical break points). When finished, your final code block should look something like this:

```html
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz0000000000000');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
