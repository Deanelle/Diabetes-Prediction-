# World-Happiness-Experimental-Design

Introduction
The World Happiness Report up to 2020 is an interesting survey that looks at the state of worldwide happiness of 153 nations.
Happiness is vital to living a long, prosperous life and I would like to focus on how social support plays a role in healthy life expectancy because of how important it is for people to have a sense of belonging and camaraderie.

Hypothesis
H_o: There is no statistically significant correlation between social support and healthy life expectancy in population.
H_a: There is statistically significant correlation between social support and healthy life expectancy in population.

Data
The joy scores and rankings utilize information from the Gallup World Survey. The scores are based on answers to the most life evaluation addresses inquired within the survey. This address, known as the Cantril step, asks respondents to think of a step with the most excellent conceivable life for them being a 10 and the most exceedingly bad conceivable life being a 0 and to rate their current lives on that scale.
The columns taking after the bliss score assess the degree to which each of six variables – financial generation, social support, healthy life expectacion, flexibility, nonattendance of debasement, and liberality – contribute to making life assessments higher in each nation than they are in what would be considered a Dystopia.

This file contains the Happiness Score for 153 countries and looks holistically at the other scores that influence that score which provides insights into what these countries are currently doing or need to do to help increase the happiness of its citizens. The Happiness Score is explained by the following factors: GDP per capita, Healthy Life Expectancy, Social support, Freedom to make life choices, Generosity, Corruption Perception The data comes from: https://www.kaggle.com/mathurinache/world-happiness-report?select=2020.csv



Results
Based on a visual inspection, social support and healty life expectancy have a strong postive correlation. The higher the social support, the higher the healthy life expectancy. The r-value being .743 shows this positve relationship. From this, you can expect a signifciant correlation between these two variables to generalize out to the population.
Therefore since the p-value is less than 5% we can conclude that it is statistically significant , we can reject the null hypothesis H_o and accept the alternative hypothesis H_a.
The 95% confidence interval suggests that the difference in social support and healthy life expectancy is between 65 and 63.

Discussion and recommendation
Social Support and Healthy life expectancy have a strong positive correlation. Which means that as perception of social support goes up so does the healthy life expectancy. Meaning that having a strong social support correlates to having a higher healthy life expectancy.
This research has implicatons for stakeholders who work as policy makers to make decisions about social impacts on health and why it is important to address the social needs of their constituents. Thus, helping governments to focus on cultivating a social environment that is suitable for encouraging the health and happiness of their nation.
The question here though, is how does social support correlate with other variables like GDP or perecpetion of corruption or how does it relate to different groups in the population such as countries in a different geographical regions? Therefore, as a next step in the process, I will examine how social support and happiness differ based on geographical regions, then examine through A/B testing the results of how geography plays a role in happiness.
