Group project 1 WAU-DATA-MAR2023
Group No5 (Kristy, Minali, Irina) 
The analysis was about long-term chronic condition trend in Australia 2021. 
Terminology/definitions
Chronic diseases are long-lasting conditions with persistent effects. Many people with chronic conditions do not have a single, predominant condition, but rather they experience multimorbidity – the presence of 2 or more chronic conditions in a person at the same time. (https://www.aihw.gov.au)
The Australian government identifies the duration of chronic diseases is ‘one that has been, or is likely to be, present for six months or more’. (https://www1.racgp.org.au)
The Australian Institute of Health and Welfare (AIHW) identifies 10 major chronic condition groups: arthritis, asthma, back pain, cancer, cardiovascular disease, chronic obstructive pulmonary disease, diabetes, chronic kidney disease, mental health conditions, and osteoporosis. These chronic conditions were selected for reporting because they are common and pose significant health problems.  (https://www.aihw.gov.au)
Resources and tools for the data analysis
Data Explorer - Australian Bureau of Statistics (ABS) was used as the official government data source to prepare chronic condition data tables to make an analysis in this group project. (https://www.abs.gov.au).
Geocoding API was used for the geographical map visualization (https://www.geoapify.com)
Jupiter was used for analysis and clean data.  
The general dependences of Jupyter included pandas, scipy.stats, matplot library, API key, numpy. 
Limitation of our analysis
1.	Our group concentrated the analysis data of one year – 2021. We have not done any other analysis due to the limitation of the data resources. For example, the information about the chronic illness of 2020 and/or 2022 were not represented on the ABS website at the moment.
2.	Our group analyzed chronic disease only in Australia, because our goals did not include research of the other countries’ statistics information relating with chronic health conditions.  
Data table’s structure and analysis
Each team member analysed two set of data (two csv files), total there were analysed 6 csv data files. 
The first lot of data analysis  health_data_byAge_byState.ipynb allowed to identify the trend of the chronic diseases according to the gender and age groups of the population and distribution these chronic conditions in Australian’s States. For example, the proportion of the different chronic conditions were analysed in Western Australia. 
The second lot of data analysis health_data_byAsist_byLabour.ipynb explored the number of populations with chronic health condition who needed any support or assistance in their daily life activities and how the chronic conditions impacted on Australian labour force. 
The third health_data_byContinent_byIncome.ipynb caparisoned the number of population with chronic illness who were born in Australia vs other continents, and level of income people per week with different chronic conditions. 
  Describes the results of the data analysis.
Chronic diseases are a significant burden in Australia, both in terms of their impact on individuals and the wider healthcare system. Chronic diseases are long-term health conditions that can have a profound impact on a person's quality of life, and often require ongoing support and management of care.
The burden of chronic disease is not only felt by individuals and their families but also has significant economic implications. Chronic diseases are a major driver of healthcare costs in Australia, accounting for a large proportion of healthcare spending. They also have a significant impact on productivity and workforce participation, with many people living with chronic disease experiencing reduced ability to work and participate in other aspects of daily life.
In  2021 the number of people who have the chronic mental health conditions is higher than population with arthritis and asthma. The lowest number of people with chronic dementia disease. As showed the analysis the females groups in ages between 20 – 60 years old had the high number of mental health illness. However, the males significant less number who had this chronic condition, particular in this age groups. 
Long Term Condition and the number of the population 
Arthritis                     2150391
Asthma                      2068020
Cancer                       732155
Dementia                   189157
Diabetes                    1198716
Heart disease             999096
Kidney disease           231777
Lung condition            441110
Mental health condition    2231543
Stroke                         234609
As represent on bar chart Fig.2. png. - due to big volume of the information the distribution of the chronic health conditions were analysis only in Western Australia. 
According to the pie chart Fig3.png, 17.8% of Western Australia's population in 2021 suffered from mental diseases or chronic mental health conditions. Diabetes, stroke, and kidney disease were on the bottom of the list with less than 2% of the population affected. Meanwhile, asthma and authorities had a prevalence of over 15%. However, when compared to other Australian states, Western Australia ranked fourth in the total number of people with chronic illnesses, with NSW, Victoria, and Queensland leading the pack.
Furthermore, the data revealed that females required more assistance with daily life activities than males. The largest number of females who needed help were women with arthritis Fig8.png.
The analysis of numbers people with chronic disease who had assistance vs who need assistance demonstrated that people with dementia are the most vulnerable group of the population Fig9.png.
The analysis of the labour force among people with chronic conditions revealed that a significant proportion of the population continued to work and receive income in 2021. However, the unemployment rate was high among people with mental health conditions and asthma. Additionally, a large portion of the population with mental health conditions and arthritis were not in the labour force.
 Fig11.png - the data indicated a negative correlation between the proportion of employed individuals and the proportion of people requiring assistance with chronic conditions. In other words, an increase in the number of employed individuals led to a decrease in the proportion of people requiring assistance.
Moreover, the pie chart Fig4.png revealed that 74.1% of the population with chronic conditions were born in Australia, while only 25.9% were born overseas.
The bar chart Fig.5.png illustrates the proportion of people in Australia with chronic diseases who were born in Australia. Since the majority of chronic conditions are found among the local population, the government needs to explore new ways to prevent chronic illnesses, especially mental health conditions, arthritis, asthma, diabetes, and heart diseases, particularly among females.
Regarding income distribution Fig6.png, the data showed that the majority of people with chronic illnesses had their own income in 2021. However, 4.5% of females and 3.2% of males had no income, and only 47.8% of women and 44.5% of men gained personal income in 2021. Further investigation is necessary to understand how chronic illnesses impact the ability of the population to obtain profitable jobs or stable income.
The bar chart Fig7.png provides a breakdown of the number of people in Australia with various health conditions, categorized by sex and income level. The income levels are divided into several ranges, including no income, $1-499, $500-999, $1,000-1,999, $2,000-2,999, $3,000-3,499, above $3,500, and not stated. For each health condition and sex, the number of people with that condition is broken down by income level, with the "Total By Income" column showing the total number of people with the condition in each income level.
For instance, the chart reveals that 90,627 females with arthritis reported no income, while 38,530 females with arthritis reported an income of $1-149. Similarly, the data shows that 48,340 females with arthritis reported an income of above $3,500, with a total number of females with arthritis in all income levels reaching 1,358,135. Overall, the majority of people with chronic illnesses had an income of no more than $500 per week, highlighting the significant impact of chronic illnesses on a person's ability to earn more and participate in the workforce.

