| [home page](https://liuaman.github.io/amanda-liu-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Vacancy Rates by Metro 

## Step one: the visualization

5.6 Million Homes Are Vacant in Nation’s Largest Metros — Here’s Where Vacancy Rates Are Highest, Lowest
https://www.lendingtree.com/home/mortgage/vacant-homes-metros-study/

<div style="display: flex; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/be571288-1e65-4ca4-bf0b-cdb4a1436b79" alt="image" width="49%" />
  <img src="https://github.com/user-attachments/assets/e7c64875-20d5-461c-a976-ba2046dbedf5" alt="image" width="49%" />
</div>

I chose this data visualization because I found the topic interesting. An area’s vacancy rate can be an important indicator of the overall health and character of its housing market. While the article was well written and provided valuable insights, I felt the chart didn’t achieve the same impact. I believe there is a room for improvement in how the visualization could better support the article. That’s why I selected it, and the article also provided a complete dataset for me to use in the redesign.

## Step two: the critique
What work well:
1. It’s clear to see where the cities are on the map and what their rank is.
2. I like the color choose - green is good for the "Lowest Vacancy Rate Chart". It gives a calm impression. 

What didn’t work well:
1. The colors are all the same for the Top 10, and on the map, the whole state is colored, but the data is only for the metro area.
2. The charts only show ranking numbers, not the real vacancy rate, so we don’t know how big the difference is.
3. Most of the U.S. map is just gray, which doesn’t give information.

The primary audience is people who care about the housing market, such as home buyers, renters, investors, and mortgage companies. I don’t think the visualization is effective enough. The charts show which metros have the highest or lowest vacancy rates, but they don’t include the most common reason for vacancy.

## Step three: Sketch a solution

![IMG_5688](https://github.com/user-attachments/assets/db746ea5-ef7d-44c4-9fef-85086d5c258d)
I focused on showing the numbers and rankings by using a bar chart instead of a map. I believe this can reduce the distraction caused by the large areas of gray in the map, since spatial location is not particularly important in this context. I also included the most common reason for vacancy in each metro, as I think this information is valuable for the audience, such as renters and investors.

## Step four: Test the solution

1. Student, mid 20’s:
Suggested a better title. She pointed out that the title did not mention the most common reason, so it required extra time to read the chart or needed more elaboration.

2. Student, MIIPS:
Suggested using higher-contrast colors.

3. Student, Male:
He noted that the color use in the bars could be confusing. At first, he misinterpreted them as showing that 100% of each bar corresponded to the same vacancy reason. He suggested splitting the visualization into two charts—one for “Ranking and Vacancy Rate,” and another for “Most Common Reason for Vacancy.”

Synthesis: 
I learned that the title plays a key role in immediately conveying the story, so it’s important to make it clear. I also reflected on the trade-off between keeping a single chart information-rich versus splitting it into two charts. Some people may feel overwhelmed when too much information is presented in one chart. I think the choice depends on the kind of story you want to tell.

## Step five: build the solution

<div class="tableauPlaceholder" id="vacancyViz" style="position:relative; width:100%; max-width:1100px; margin:0 auto;">
  <noscript>
    <a href="#">
      <img alt="Vacancy Rates by Metro"
           src="https://public.tableau.com/static/images/Va/VacancyRatesbyMetrointheUnitedStates/Dashboard1/1_rss.png"
           style="border:none;" />
    </a>
  </noscript>
  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="name" value="VacancyRatesbyMetrointheUnitedStates/Dashboard1" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById('vacancyViz');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 1) + 'px';

  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


When finalizing the data visualization, I chose red for rent to convey a sense of unaffordability, and used green and blue as calmer tones for seasonal/recreational and personal reasons. I updated the title to “Vacancy Rates by Metro in the United States” with the subtitle “Colored by the Most Common Reason for Vacancy.” I also added an average reference line to provide viewers with a baseline for comparison.

## AI acknowledgements
I asked ChatGPT a few questions about Tableau functions to help me build what I had sketched. After finishing the visualization, I asked it to critique my work again. I also used it to improve my grammar and wording for this assignment.

