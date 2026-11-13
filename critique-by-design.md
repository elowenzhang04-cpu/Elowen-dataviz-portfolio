| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Out-of-school rate

## Step one: the visualization

I selected the UNESCO Institute for Statistics visualization on out-of-school rates by region and age group for 2018. The original chart is available at [https://makeovermonday.vercel.app/dataset/out-of-school-youths-and-adolescents](https://makeovermonday.vercel.app/dataset/out-of-school-youths-and-adolescents).

The visualization is a grouped horizontal bar chart that shows out-of-school rates for primary, lower secondary, and upper secondary age groups across regions. I chose it because it comes from a professional organization, addresses a clear policy topic, and contains several design choices that invited closer examination, including how the world average is presented, how the data are sorted, and the absence of a clear definition for the indicator. These features made it a useful case for moving from a descriptive display toward a more insight-driven one.

## Step two: the critique

The chart uses a grouped horizontal bar chart to show out-of-school rates by region across primary, lower secondary, and upper secondary age groups in 2018. What stands out most is how it compresses a rather complex dataset into a single comparable view. The color coding is clear, values are labeled directly on the bars, and I can quickly tell that Sub-Saharan Africa and Southern Asia have higher rates, along with a general rise in rates as the age group increases.

The chart works well in its choice of visual encoding. Horizontal bars accommodate longer region names and are well aligned, and length encoding makes proportional comparison straightforward. The three colors are distinguishable. Sorting by the primary out-of-school rate provides a consistent organizing principle, and the source note plus sorting explanation at the bottom follow standard report conventions.

The main weaknesses lie in completeness of context and guidance for interpretation. The chart never explains that the denominator for each rate is the official age-group population for that education level, not the total child population in the region. I was very confused at first, trying to understand what the numerator and denominator of the out-of-school rate actually were. It was only after searching for the UNESCO definition of the out-of-school rate indicator that I finally confirmed what the percentage meant. I was also puzzled by the regional classification and aggregation, for example why Western Asia and Northern Africa are grouped together and why Europe and Northern America are combined. I later discovered that this is how UNESCO originally classifies the regions in the dataset, rather than a grouping chosen by the visualization’s author. World is placed in the same list and visual style as the regions, so it reads as a ninth peer rather than a global aggregate benchmark. The decision to sort by primary rates is technically valid yet quietly centers the primary stage without stating the rationale.

Using Few’s criteria helped me look past the clean layout of the chart and focus on whether it actually gave enough context for its audience. Because this visualization is meant for readers trying to understand global education disparities—such as policymakers, researchers, and the general public—missing indicator definitions and unexplained regional groupings make the numbers harder to use. Compared with the Good Charts method, which focuses more on my initial reaction and overall visual impression, Few’s profile gave me a more structured checklist to evaluate specific details like visual encoding and context. At the same time, deciding between close numbers on the rating scale felt less useful than explaining why a particular element worked or fell short.

## Step three: Sketch a solution

The original chart is a bar chart that labels every bar with its exact value and remains largely descriptive. For the redesign I set the context as something aimed at policymakers and researchers in education who need to see the severity of out-of-school problems by stage in particular regions. I therefore moved to a slope chart.

In the pencil sketch I drew only the lines I wanted to emphasize. Sub-Saharan Africa and Southern Asia appear as solid lines rising sharply. The world average appears as a dashed line with square markers. Other regions are indicated with lighter, incomplete strokes so they stay in the background. The y-axis uses an interval of 20 because the goal is to show the overall trend rather than allow readers to read every exact value. A short definition of the out-of-school rate sits under the y-axis label so that the meaning of the percentage is available without leaving the chart. Region names are placed to the right of the final points.

![Pencil sketch](OOS%20Sketch.jpg)

![Prototype](OOS%20Prototype.png)

*Prototype image generated with Gemini based on my pencil sketch and detailed redesign description.*

The sketch helped me confirm that a slope chart could make the increase across stages and the separation of the two highest regions immediately visible while keeping the world average visually distinct.

## Step four: Test the solution

**Student, MSIM program:**

- Noted that upward-sloping lines can feel positive even when the indicator is negative, and suggested exploring the complement so the lines would slope downward.
- Found the dashed world-average line effective.
- Recommended calling out regions that exceed 50 percent in the title because the halfway mark makes the scale of the problem more immediate.
- Observed that the left-to-right order of the stages matches an intuitive time flow.

**Student, first year:**

- Said the word “gap” in the title required extra time to interpret.
- Pointed out that the lower cluster of lines does not show a clear gap, so a general claim about gaps could be misleading.
- Preferred the y-axis definition placed above the axis rather than beside it and questioned whether the definition needed to be so prominent.
- Agreed that the slope chart suited the intended message.

**Student, mid-20s:**

- Found the slope chart appropriate for the message.
- Liked the combination of a dashed line and square markers for the world average.
- Suggested moving the indicator definition to a footnote so that readers who already know the definition are not required to read it again.

**Synthesis:**

Across the feedback, the slope-chart direction and the visual treatment of the world average were consistently supported. Points of friction centered on the title’s clarity, the prominence of the definition, and the risk that “gap” overstated the pattern in the lower lines. In response I kept the slope chart and the distinct world-average treatment, moved the definition into a caption, and revised the title and subtitle to name the two regions, state the size of the increase in percentage points, and note that more than half of upper-secondary-age youth are out of school in Sub-Saharan Africa.

## Step five: build the solution


<div class='tableauPlaceholder' id='viz1794530921076' style='position: relative'><noscript><a href='#'><img alt='Out-of-School Rates Rise Sharply with Education Level — Widening the Regional Gap to 51 Percentage PointsSub-Saharan Africa and Southern Asia drive this divergence, each jumping 38.7 percentage points from primary to upper secondary age—leaving more than ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ou&#47;Out-of-schoolrate&#47;Out-of-SchoolRatesRiseSharplywithEducationLevelWideningtheRegionalGapto51PercentagePoints&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Out-of-schoolrate&#47;Out-of-SchoolRatesRiseSharplywithEducationLevelWideningtheRegionalGapto51PercentagePoints' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ou&#47;Out-of-schoolrate&#47;Out-of-SchoolRatesRiseSharplywithEducationLevelWideningtheRegionalGapto51PercentagePoints&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1794530921076');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


I built the chart in Tableau. The final version uses a dual-axis view. One axis draws the lines; the other draws the markers and the end labels. Calculated fields create the three stage labels, map World to “World average,” group regions into style categories, and generate labels only at the upper-secondary points. An extra blank category on the columns shelf creates space on the right for the labels. Sub-Saharan Africa is drawn in dark red and Southern Asia in bright orange, both with thicker lines. The world average uses a dark gray line and square markers. The remaining regions appear in light blue with thinner lines. The y-axis runs from 0 to 65 with major ticks every 10. Grid lines are light and dotted. The definition of the indicator and the source appear in the caption.

To act on the testing feedback, I restructured the header into a main title for the macro pattern and a subtitle for attribution and severity. I anchored the main title with the exact 51-percentage-point spread between the highest and lowest regions at the upper secondary stage: "Out-of-School Rates Rise Sharply with Education Level — Widening the Regional Gap to 51 Percentage Points." I used the opening of the subtitle to narrow the claim by naming Sub-Saharan Africa and Southern Asia and noting their identical 38.7-percentage-point jump, so readers immediately see that these two lines drive the divergence. I closed the subtitle by translating Sub-Saharan Africa's peak rate into an everyday threshold: "leaving more than half of upper-secondary youth out of school in Sub-Saharan Africa." Framing the peak around a 50 percent benchmark makes the human scale of the problem concrete and sets the right policy urgency before the reader even examines the axes.

The redesigned chart shows that out-of-school rates rise across all three education levels, and that the increase is especially steep in Sub-Saharan Africa and Southern Asia. From primary to upper secondary age, both regions jump 38.7 percentage points, leaving more than half of upper-secondary-age youth out of school in Sub-Saharan Africa. Other regions remain clustered well below the world average at the upper secondary stage, so the visual separation makes clear that the two highlighted regions drive most of the widening gap.

## References

- UNESCO Institute for Statistics. (2018). *Out-of-school rate by region and age group, 2018*. Makeover Monday. <https://makeovermonday.vercel.app/dataset/out-of-school-youths-and-adolescents>
- Few, S. (2017). *Data visualization effectiveness profile*. Perceptual Edge. <http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf>

## AI acknowledgements

1. I generated early prototype images of the slope chart using Gemini. I uploaded a photo of my pencil sketch and described in detail the redesign ideas I had already decided on, including which regions to highlight, how to treat the world average, the placement of labels, and the overall visual hierarchy. Gemini produced several static image versions of the slope chart based on that description. I used those images only as visual references while refining the layout.
2. I used Gemini to troubleshoot a specific Tableau layout problem. Several region names were long enough that the mark labels overlapped the lines when placed at the end of each series. I asked Gemini how to keep the labels left-aligned at the end of the lines without overlapping the marks. The suggestions helped me adjust the dual-axis setup, the label alignment settings, and the use of a blank column for spacing. I then implemented and tested the solution myself in Tableau.
