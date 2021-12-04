# portfolio
This is my public portfolio for Telling Stories With Data at CMU

# About me
I am Saachi Talwai, currently pursuing a Masters in Information Systems Mangement degree at Carnegie Mellon University. 

# What I hope to learn
I would like to create effective and appealing data visualizations that tell a story. As an aspiring Product Manager knowledge of a tool like ShortHand and getting familiar with visualizations tools like Tableua and Flourish would help me relay a stroy to a potential customer.

# Portfolio
Here is my portfolio curated during my Telling Stories with Data course in taken in Fall 2021.

# Visualizing Government Debt

[Link Here](/dataviz2.md)

The following visual is a single line chart comparing the Debt to GDP Ratios of countries in the OECD Dataset.

<script src="https://public.flourish.studio/resources/embed.js"></script>
Comparing the visuals 2 and 3, the 2nd visual has static components whereas the 3rd visual allows the viewer to filter the Debt to GDP ratio by year. The grid of line charts gives the user an idea of how a country Debt is over time, where as the single line chart gives the viewer a comparision between different countries for a given year. The ideas portrayed are different. From a visual perspective I feel the single line chart is less crowded and seeing the data points on the chart gives the veiwer a quick idea of what the chart represents.


# Data Visualization Critique
We had the chance to critique a visualization of our choice during the course.
[Link Here](/dataviz3.md)

## Step 1) Select a Visualization 

<iframe src="https://ourworldindata.org/grapher/cumulative-covid-19-vaccinations-vs-population" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>


## Step 2) Data Visualization Critique

<p>
 Record of responses for Data Visualization Effectiveness Profile:  
 As a viewer I do believe the graph is relevant. Any graph that is accurate and is related to the pandemic in the last two years is of high usefulness. The  completeness of the graph is debatable, because I don't understand why the given set of countries are chosen in particular. I can make an assumption that the graph wants to represent countries from every population range, but then this is not intuitive. 
 What worked well for the graph is that the user is easily understand what is trying to be mapped - Population VS Cumulative Vaccinations  Doses Administered , the presence of the legend is helpful to interpret the continents that have the most number of vaccinations administered.
The Graph is interactive; we can click on a single data point to isolate it (greying out other points)  and do get it X and Y axis values of that particular point
 The presence of the dotted lines representing the COVID doses makes the chart crowded and doesn't contribute to the Perceptibility and Aesthetic of the graph.
I would remove the the dotted lines representing the kind of doses of the vaccine. All the this in added information about where each country stands with regard to COVID doses, it doesn't really add to the aesthetic and perceptibility of the visual.
 </p>

## Step 3) Wireframe Solutions
Since the data contains countrywise data and associated metrics I thought that the data could be best visualized using a of heat map of the world. The datasource provides the total number of COVID cases per country and the country's population. This data can be used for any comparision chart.
The per capita cumulative covid cases for a country can than be compared.

<img src="Image-1.jpg"/>


## Step 4) Test Solution

Answering the following the questions of the visualization

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Participant 1:
 - A1 The first impression of it that it is a heat map. 
 - A2 It represents the number of vaccine doeses adimistered per country and there is some sort of comparision between countries.
 - A3 I don't know what the units of the values used to create the visual are. 
 - A4 The intended audience of the graph are researchers, people interested in the COVID vaccine. 
 - A5 List the countries on the graph/ or pop-up. The title of the graph needs to be more clear and descriptive. 

Participant 2:
- A1 The first impression of it that it is map measuring the severity of an issue
- A2 The map is comparing countries based on the number of doses of the COVID Vaccine administered
- A3 The legend needs to be clearer with what is being measured.
- A4 The intended audience of the graph are people who are tracking daily COVID cases
- A5 Clearer context to the graph, better title, change the color of the heatmap from green to something more neutral.

Both participants got the idea that the graph was representing a comparision between countries related to the COVID vaccine administration. The wireframe fell short to clearly explaining what the visual intented to do from the title.


## Step 5) Build Solution:
<html>


<div class='tableauPlaceholder' id='viz1636492523617' style='position: relative'><noscript><a href='#'><img alt='A Countrywise Comparision based on the  Number Covid Vaccines given Per Capita  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RedesignedDataVisualization&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RedesignedDataVisualization&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RedesignedDataVisualization&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>         
 
 <script type='text/javascript'>                    var divElement = document.getElementById('viz1636492523617');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);               
 </script>
 
<p> I used Tableau to create a visualization to represent the number of vaccinations per capita for a country. The countireswere differentiaited based on high the per capita metric was. The color palette chosen was a green gradient as a COVID vaccine represents something positive. </p>


</html>

# Final Project:
I decided to choose 'Social Expenditure in the United States' as a story to visualize using ShortHand.
## Part 1:
Link: https://saachit-12.github.io/portfolio/finalProject_SaachiTalwaiPart1.html
  
## Part 2
Link: https://saachit-12.github.io/portfolio/final_project_part2SaachiTalwai.html
## Part 3
Link:  https://saachit-12.github.io/portfolio/finalProject_SaachiTalwai.html
