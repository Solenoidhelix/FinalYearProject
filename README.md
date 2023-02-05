# FinalYearProject
Finaly year project
Abstract


In this paper we will look at how the pandemic has affected people’s mental health sentiment and dietary sentiment using natural language processing. Using a pre-trained BERT model, we can find the sentiment of each free text response and attempt to find correlations with different demographics. With the help of topic modelling, we can find frequency of words to create common topic to see any similarities in responses.


Introduction


During the COVID-19 pandemic, issues around mental health and well-being gained widespread prominence. Although the lockdown was a short-term strategy to combat the disease, it inevitably gave rise to long-term health issues which may or may not have been aware of before. To understand this, we used a survey done by the Centre for public health at QUB. The response contains demographics of respondents and free text responses regarding their mental health and dietary health. With this dataset we can apply natural language processing methods such as sentimental analysis using BERT and topic modelling to better understand and analyze sentiment of respondents. We can go further and try to find correlation between demography and sentiment to find if different demographics were affected more or less by the pandemic. 


Discussion and Reflection on Project


Using sentimental analysis and topic modelling we found that many of the respondents had a negative impact on their brain health and dietary health due to the pandemic. For brain health over 80% of the respondents were affective negatively and only about 1% felt positive. Even across different demographics the negative responses to positive responses were proportional. For dietary health, most respondents (~70%) felt neutral but there were still large amounts of negative sentiment. Pearson correlation coefficient between brain and dietary sentiment was calculated. A coefficient of 0.48 which indicated moderate collation between the two subjects. When using topic modeling, we found that most dominant topics were about food and lack of social interactions. This can be inferred that the negative sentiment for the pandemic was mainly due to the lack of social interaction. Reflecting on my work and results so far after, I see that I should have used a more appropriate model for my sentimental analysis or even created my own model to use for comparison against the one I have used to see if I could have increased my accuracy. Optimization of the genism LDA model could also have been improved. Plotting of results, analysis and topic modelling could have also been done using purpose built tools like Power BI and tabulae for more flexible and clean diagrams/plots. In the future I will revisit this project once I have broadened my knowledge.
