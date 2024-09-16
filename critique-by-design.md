| [home page](https://bingjie6.github.io/tswd-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment 3 & 4: Critique by Design with Tableau

For this Critique by Design assignment, I'm going to come up with a critique and a data visualization using information and data that was available either online or from the class. The steps are as follows:

Step one: select a visualization to redesign from [MakeoverMonday](https://makeovermonday.co.uk/) <br />
Step two: critique the visualization <br />
Step three: wireframe a solution <br />
Step four: test the solution <br />
Step five: build my solution

Don't waste time. Let's get started!

## Step one: the visualization
<a href="https://www.statista.com/chart/32549/average-effective-labor-market-exit-age-of-selected-countries/" title="Infographic: The Varying State of Retirement Ages | Statista"><img src="https://cdn.statcdn.com/Infographic/images/normal/32549.jpeg" alt="Infographic: The Varying State of Retirement Ages | Statista" width="100%" height="auto" style="width: 100%; height: auto !important; max-width:960px;-ms-interpolation-mode: bicubic;"/>
</a> Data Source <a href="https://www.statista.com/chart/32549/average-effective-labor-market-exit-age-of-selected-countries/">OECD</a>

I selected **"The Varying State of Retirement Ages"** visualization because it presents an important and widely relevant social and economic issue: the age at which people retire in different countries. Understanding global retirement ages is crucial for policymakers, labor economists, and even the general public, as it impacts national productivity, pension systems, healthcare costs, and the overall aging workforce. The visualization makes it easy to compare different countries' retirement trends, particularly in relation to the OECD average, which acts as a benchmark for evaluating a nation's standing in a global context. 

The topic also ties into broader conversations on aging populations, workforce sustainability, and gender disparities. By displaying the data for both men and women, this chart invites further analysis into how gender impacts retirement ages, offering insights into economic and social structures. Given the ongoing debates about labor force participation and retirement policies, particularly in aging nations, this visualization provides a clear and accessible entry point for discussions around global retirement trends.

## Step two: the critique
The graph clearly shows the retirement ages across various countries, and it's easy to compare men and women using the color coding (orange for men and purple for women). The dotted lines representing the OECD averages for both men and women make it easy to compare each country's values against these benchmarks. The arrangement of countries by order with easily recognizable flags adds context, allowing viewers to quickly identify the nations they are interested in. However, the bar chart doesn't differentiate very clearly between countries with small differences in retirement ages, which might lead to crowding or difficulty in exact interpretation. In addition, the chart labels for the country names could be improved in terms of size or placement. Some flags are less recognizable at a quick glance. The chart could also benefit from including exact values atop the bars to avoid forcing readers to estimate the heights.

The primary audience for this graph could be policymakers, retirement analysts, labor economists, or media professionals reporting on retirement trends. The visualization is somewhat effective for policymakers and analysts as it provides a clear overview of the average retirement age in a global context. However, for a general audience, the graph could be difficult to interpret without background knowledge, especially since the country flags are accompanied by abbreviated country names.

This visualization is evaluated according to Stephen Few's [Data Visualization Effectiveness Profile](https://www.tableau.com/blog/stephen-few-data-visualization). Compared to the Good Charts method, this evaluation method pays additional attention to how the targeted audience perceives the visualization and its effectiveness in reaching the audience. The evaluation criteria are also more comprehensive in covering the truthfulness, completeness, and aesthetics of the visualization. To improve, the method could incorporate a walk-through of the graph, similar to the Good Charts method, identifying what the visualization tells at first glance and what information the graph is telling after careful exploration. For example, what color stands out first, or how does the shape, layout, and the design assist in delivering the information, etc.

## Step three: Sketch a solution
![Retirement Ages Men vs Women](retirement-ages.png)

## Step four: Test the solution
I shared my sketch above with two different people and asked for their feedback by preparing interview questions. Both interviewees are CMU master's students in their early twenties.

### Question 1: For this graphic, what do you see first?
**student 1:** I see the retirement ages information across some countries in a format of bar plots. The men retirement ages are shown on the left in blue and the women are on the right in pink. Also, specific numbers are provided.

**student 2:** I first saw the blue and pink color as the color shades are very easy to get noticed. And I comprehend them as indicators of age span. Then are the logos of the countries.

### Question 2: Can you describe to me what this is telling you?
**student 1:** Since the author rank the countries from top to bottom based on who has the largest retirement age to the least. I can easily tell which country has the highest retirement ages or compare between the counties. What’s more, an average retirement ages lines are provided to both men and women, which acts as a reference line to help us build up the concept of what is a general or ‘normal’ retirement age and how is it different from those on the chart. Also, it is easy to compare between men and women retirement ages since they are shown on each side of the countries.

**student 2:** The graph is about retirement ages for men and women in 6 different countries.

### Question 3: Is there anything you find surprising or confusing?
**student 1:** I am surprised by the information that Iceland has such a high retirement age since, under my understanding, it is one of the happiest countries around the world which should have a lower retirement age. Meanwhile, I am confused that why are these countries shown on the chart. What is the logic behind it? Is it, for example, the counties with the top 6 retirement age or the bottom 6?

**student 2:** It is surprising to know that there are certain countries’ retirement age is over 65 years old.

### Question 4: Who do you think is the intended audience for this?
**student 1:** The intended audience could be researchers, intended immigrants, international workers, international students, and so on.

**student 2:** I think it is more like for general knowledge and for audience who would like to learn more about each country’s retirement age.

### Question 5: Is there anything you would change or do differently?
**student 1:** As stated in the ‘confusion section’ above, I would probably clear introduce what are these countries and why are they picked in the title or subtitle section. Also, I might add some background axis lines to help locating the specific number and help comparison.

**student 2:** I will probably include a note like why these 6 countries are selected as I am curious. Like are they the top countries that have the highest retirement ages. Also since there are only 6 countries, maybe a clearer legend would be helpful as audience could wonder if the women/men average ages are for these 6 selected countries or all the countries in general.

The feedback from the two students reveals several key insights regarding the strengths and areas for improvement in the original visualization of retirement ages. One prominent pattern is the effective use of color coding (blue for men and pink for women), which was immediately noticed and helped both students quickly identify the gender comparison. However, despite this clear visual distinction, there was confusion about the selection of countries. Both students questioned the rationale behind the choice of countries and suggested that additional context should be provided. For example, were these countries selected based on having the highest or lowest retirement ages, or for another reason altogether? This lack of clarity detracted from the overall understanding of the chart.

Another strong point of the original design, as mentioned by student 1, was the use of reference lines showing the OECD average retirement ages for men and women. These lines acted as useful benchmarks, helping users to gauge how individual countries compared to a global average. However, the feedback suggests that the legend and labels could be made clearer to enhance this comparison further. For instance, student 2 expressed confusion about whether the averages applied to just the selected countries or globally, indicating that a more explicit explanation could be beneficial.

Based on this feedback, several design changes could improve the overall visualization. First, providing a subtitle or explanatory note regarding the country selection would eliminate confusion and give the chart more purpose. Second, replacing country logos with names and adding background gridlines would make the chart easier to interpret, allowing viewers to quickly identify specific values. Lastly, including annotations or brief explanations of outliers, such as why Iceland has such a high retirement age, could add depth and context, making the data more engaging and insightful for a wider audience. These changes would make the visualization more informative, accessible, and user-friendly, while preserving its core strengths of clear gender comparison and reference to global averages.

## Step five: build the solution
<div class='tableauPlaceholder' id='viz1726522601455' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='RETIREMENT AGES across selected countries for five year period 2017-22 source: OECD'
                 src='https://public.tableau.com/static/images/re/retirementages_17265222578900/Sheet1/1_rss.png'
                 style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display: none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='retirementages_17265222578900/Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/re/retirementages_17265222578900/Sheet1/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object>
</div>

<script type='text/javascript'>
    var divElement = document.getElementById('viz1726522601455');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. 

