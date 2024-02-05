| [home page](README.md) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design

## Step 1: Choosing a Data Visualization

For this assignment, we were asked to select a data visualization to critique and re-design. Per the professor's suggestion, I selected my data visualization from the [Makeover Monday website](https://makeovermonday.co.uk/).

I selected the visualization ["The Cost of 1GB of Mobile Data in Every Country?"](https://www.visualcapitalist.com/cost-of-mobile-data-worldwide/) which was published July 2020 via Visual Capitalist.

![Image Alt text](VC-Mobile-Data_V3.jpeg)


Having spent a substantial amount of time abroad in Spain and Italy, I was interested in the subject of this data visualization. When I lived in Spain (2017-2019), I was paying 15 euros (about 16 USD) a month for a phone plan with 10GB of data. However, when I recently lived in Italy (2022), I was paying 12 euros (about 12 USD) a month for 150GB of data. Personally, I was shocked by the stark difference and I've been wondering about the cost of mobile data ever since. Hence, I was instantly interested in this data visualization. (And imagine my surprise when one of the call-out boxes listed Italy as one of the 5 least expensive countries for 1GB!)

## Step 2: Critique the Visualization

For this critique, we utilized Stephen Few's [Data Visualization Effectiveness Profile Technique](https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf).

Here is how I scored the data visualization along each of the seven criteria: 

![Image Alt text](Few Criteria Scoring.png)

**Overall Observations:** While ranked high in the area of usefulness, this visualization was too cluttered and not intuitive enough to gain it high scores in other areas. I think this data was useful amongst a wide audience (e.g., consumers, tech companies, and policymakers), especially in 2020 when the pandemic highlighted disparities compounding the tech gap crisis. The second-highest ranking was in the area of truthfulness as it seems that the size differences were representative of the price differences (e.g., the size of Benin and Malawi isn’t very different and neither are their prices). However, the fact that the majority of the country data was under $5 made it very difficult to determine if they were well-positioned. Furthermore, forcing the audience to compare sizes is difficult and decreases perceptibility and clarity. It was hard to 1) tell the difference between similar-sized countries (especially without price/country labels), 2) locate countries, or 3) track regional trends. The use of flags as icons was also not very intuitive as viewers unlikely know the flag for each country. The things that worked really well were actually the callout boxes and captions as I felt that they highlighted some of the data’s main points (e.g., least/most expensive countries, regional trends, and disparity levels). Also, the size key and the y-axis labels were helpful (and necessary) in contextualizing how much 1GB cost in each country.

**Intended Audience:** Given the aesthetic choices made, I assume that the creator intended this visualization to be for a generalized audience. It seems that the creator tried to be creative with the data to entice people who may not be familiar with the topic/data to learn more about the issue. However, I do not think that the visualization is effective because it sacrifices the informative criteria of a visualization for the emotive criteria. Any viewer, even those with more association to the topic/data would have had a difficult time identifying countries, price differences, and regional trends. So, while the audience may find it visually appealing, I do not think that they would actually engage with the data or be encouraged to learn more about the issue. So, while the information could be important for consumers, policymakers, or tech companies, it’s unlikely that it will actually result in any outcome that could resolve the tech gap created by price disparities for data.

**Thoughts on The Effectiveness Profile Technique:** This critique method challenged me to think more deeply about different aspects of the visualization. Splitting elements into informative and emotive categories was also really useful for the visualization I selected because I was able to see how sometimes choosing to focus on emotive categories can come at the expense of the informative elements. When discussing his ranges for the different characteristics, Few discusses how there is more leeway for emotive elements than informative ones, and this visualization would have been more effective if the design were more familiar (e.g., a heat map or even a bar graph) – especially because the data was useful to a broad audience. I don’t think the Few critique method misses anything, but I do think it takes practice to really understand the differences between the criteria as some might seem to overlap at first. For instance, I was struggling to determine if the flag circle icons were more of a perceptibility issue or an intuitiveness issue. For instance, the size comparison was perceptibility while the flag icon was about intuitiveness; however, there is some overlap so it’s difficult to rank various criteria. 

## Step 3: Sketch the Redesign

After critiquing the original data visualization, I had two recommendations for a redesign: 

**1) change the chart type to be a map**
A map layout would be a more intuitive chart type for viewers. It would also present the data in a way that limits clutter and illustrates country differences and regional trends.

**2) use a diverging color scheme** 
This change would maintain the original design's focus on the comparison between countries with the highest cost and countries with the lowest cost.

With these two recommendations in mind, I decided to utilize Tableau for the first draft of my redesign. 

<div class='tableauPlaceholder' id='viz1707104968831' style='position: relative'><noscript><a href='#'><img alt='What Does 1GB of Mobile Data Cost by Country? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Costsof1GBbyCountry&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Costsof1GBbyCountry&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Co&#47;Costsof1GBbyCountry&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1707104968831');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<br />

## Step 4: Test the Solution

### Interviews: 

| &nbsp; | Grad Student in Info Security Policy, 26 | Title I Coordinator at K-5 School, 54 |
|     :---:      |     :---:      |      :---:    |
| What do you think this visualization is about?   | How much 1 GB of data costs per country. | The average price of 1 GB of data in different countries. For example, it's telling me how much 1GB of data would cost if I were to go to Canada or Chad. |
| Who do you think is the intended audience?    | The general public because it seems accessible and like it's just meant to be informative. It's also an international audience becuase otherwise it would just focus on a specific country or region. | Anybody who's interested. But, maybe it's specifically for Africa because the situation seems bad there. Or maybe it's also for those white countries that don't seem to have any internet since they have no data. |
| What do you thinkare the main takeways (or main ideas)?   | That a few countries pay a lot more for mobile data than most others do. The high prices are mostly centralized in Afria, but it's interesting how you've got a red dot in the middle of an affordable area. | That this is no equality for 1GB of internet. Majority of places are getting it at a relatively good price, but Africa and Yemen have a messed up situation. And some countries in Latin America don't get anything at all, while the rest seems to get it at a relatively low price. (In the prior statement, the participant was referring to the white countries again.|
| Is there anything that you find surprising or confusing?    | I wish that even if there was no data for a country, you could still hover over it and still get the country name and a line that said "no data." I'm assuming that the grey area means no data. Given my experience with graphs, grey usually means no data. Plus, I know that those countries exist. | Yeah, Africa is very surprising because I thought the socio-economiic situation was low, but somehow they're having to paay so much for 1GB of data. It's also surprising that countries in one region, like Latin America, could have such different prices. And, what's going on with Iceland? They also don't get internet. But I'm really confused about the white/light grey portions. Do they get internet for free or do they not get it? Because this color isn't explained by the key. |
| Do you feel that the visualization's design is appropriate for the purpose you identified earlier?  |I think so because it shows that countries where it's very expensive are within a certain area. For example, a bar graph woudln't show that relational aspect. | Yes, because it's giving me an overall idea of what I'd be paying in each country on average. It's a good visual because if I wanted to go to a specific country, I knew about what 1GB would cost. A bar graph would be too tight since some of them are paying very close rights. |
| Do you think that the visualization's design is appealing and/or engaging?   | Yes, because the colors aren't obnoxious. It's thought-provoking, but doens't explain much. It gets the reader's attention to ask more questions, especailly because the colors contrast so sharply. The green and red are very different. | It's engaging, but I don't think it's appealing. It's engaging because I can scroll over all the countries. |
| Is there anything that you wish had been different about this visualization?   | I wish that you could click on it by price category (e.g., just see all of the dark reds at once) and grey out everything else. I wish you could also click on the grey ones to see which countries didn't have data as that's interesting info as well. I also wish the map didn't glitch as much. | 1) The map should be bigger because it's very small. And I don't know if it's a user issue, but some of these islands are too small to click on. 2) It should be by state/regionit, not just the whole country (even though it says average). 3) It doesn't tell me what mobile carrier people are using. Is every mobile carrier offering the same price? 4) Added information regarding the white space? It should be added to the key. | 
| Is there anything that you feel is unnecessary (or missing) that hindered your understanding of the data? | I want an accompanying chart to see how many people use data in each country because I assume this info is related to the cost. I also want a subcountry breakdown (e.g., Siberia in Russia would look different than the rest of the country). | I would like to know more about specific countries. For instnace, which areas of Canada or paying more or less than the average? That would help me decide where to go when I travel. Currently, this broad overview is too vague for me and not specific enough. The missing information about the white spaces is really confusing because I don't know what it means. |
| What are your thoughts about the key? | I know what the dark green and the dark red are, but I don't know what the middle values are. I can understand relationally, and I could probably work backwards by clicking on countries to determine a range. But, that's a lot of work and I should just have a concrete number or range. | It could be an issue. I can see that the middle of the light green has what I assume to be a half point, which is arond $13.70. But, I'm having trouble guessing what the range would be and the range is also too big for me. One light green country is $12.55, which is pretty far if the halfway range is $13.70. The provided ranges are just not informative enough. |
| What are your thoughts about the color scheme? Would you have preferred a sequential monochromatic color scheme?  | I think I would have preferred a sequential monochromatic scale. The red-green divergence might over-exaggerate the differences, especially when the light red and light green values might not be too different. The diverging color scheme could have worked better if the middle colors had been something like yellow so it didn't look so different from either red or green. | This scale is good because it's obvious which countries are paying too much. |

### In-Class Feedback:

### Main Takeaways:

## Step 5: Build the Re-design
