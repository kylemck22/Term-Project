# The Impact of Social Media on Misinformation

*By: Kyle McKeough* 


# Table of Contents:






## Problem Context

Social media has become a primary source of information for millions of people worldwide<mark>(cite)</mark>. While it has revolutionized communication and information sharing, it has also facilitated the rapid spread of misinformation and disinformation<mark>(cite)</mark>. Misinformation refers to false or misleading information shared without harmful intent, while disinformation is deliberately created to deceive audiences. The impact of misinformation on social media is profound, influencing public opinion, shaping political discourse, and even affecting public health outcomes<mark>(cite)</mark>.

 The speed and scale at which misinformation spreads on platforms such as Facebook, Twitter, and TikTok make it a significant societal challenge.







## Executive Summary

The spread of misinformation on social media is a growing problem with significant consequences for public trust, safety, and decision-making. False or misleading information can quickly gain traction, influencing individuals' beliefs and behaviors on a wide scale. This phenomenon is particularly concerning during events like elections, public health crises, or social movements, where misinformation can mislead entire populations and distort public opinion. The nature of social media creates an environment where misinformation can spread rapidly and widely, often without sufficient fact-checking. Tackling this issue involves understanding how misinformation propagates, identifying its sources, and developing strategies to curb its spread, ensuring that users have access to accurate and reliable information.



## Key Performance Indicators

1. Which Politicians Speak the most truthfully and the most unthrufully
   
* Definition: Figure out which politician speaks the most truthfully and untruthfully. Based on the data, I will figure out who spread the most misinformation and who spread the least amount of information.
* Target: Using graphics, show who is the most and least truthful, and comparing the results with their respective tenures. 

2. Which political position is the most truthful? Which is the most untruthful?

* Definition: Find which position of power in the data speaks the most truthful, and which speaks the most untruthful. There will be a specific pattern between the positions. 
* Target: Deduce which position speaks truthfully and which does not. We want to reduce the amount of truth that the President position speaks, to ensure our trust. 

3. Is there a correlation between truth and Presidential election tenure?
   
* Definition: With the data, I will analyze the results of truth, and do some external research to view the tenure of those who spoke this information. I will then compare the two findings and see if there is a correlation.
* Target: I would like to have a positive correlation between speaking truthfully and being re-elected.

4. Is there a correlation between Political Party and Untruthfulness
   
* Definition: The correlation between which political party one is apart of and the amount of truthful statements vs untruthful statements.
* Target: To achieve a decision point where we can view which political party tends to speak less truthfully to then decide who we should vote for in the future.

5. Sentiment Analysis of Misinformation

* Definition: To view what kind of Sentiment was felt pertaining to each political party speakers statements.
* Target: The more positive the sentiment toward the parties, that is which party we should be comfortable voting for.


DATA FOR TERM PROJECT MILESTONE 2:

In Tableau, I created visualisations for my 5 Key Performace Indicators, and included a paragraph write up on each visualisation.

KPI #1: Which Politician speak the most truthfully and untruthfully?
<img width="1201" alt="Image" src="https://github.com/user-attachments/assets/abf7b9ed-33e7-4142-9a50-21b4056d61f6" />

In this visualisation, it shows that George W. Bush had the most untruthful statements during his press conferences, with a total combined score of -1,409. The scores were based on point scale where points are added up based on their statements. The point scoring is -1 for a non-factual statement, 0 points for an unimportant factual statement and +1 point for a check-worthy factual statement. THe politician who was the most truthful was John Anderson, with a combined score of -22.


KPI #2: Which Political Position is the most Truthful? Which is the most Untruthful?
<img width="1201" alt="Image" src="https://github.com/user-attachments/assets/d78b6021-4b35-4d47-a3c3-e132547c17a1" />

In this visualisation, I concluded that those in the governor position spread the most misleading statements, while the congressman position spreads the least mistruthful statements. The positions are colour-coded on the bar chart with the speaker title.


KPI #3: Is there a correlation between truth and Presidential election tenure?
<img width="1205" alt="Image" src="https://github.com/user-attachments/assets/c47620b6-8669-458a-9583-793472b391b1" />

In this visualisation, I seeked to find if there was a correlation between the presidental election tenure and speaking/not speaking the truth. I filtered the speaking title to only include presidents. George W. Bush had the most cases of mistruth, while Ronald Reagan had the least amount of mistruth. After some research, I found the following statistics for each candidate.  
Barack Obama: Cannot be re-elected for the third time, he is not qualified.
Bill Clinton: Was Re-elected in 1996.
George Bush: Lost the election to Bill Clinton in 1992 after speaking.
George W. Bush: Was Re-elected in 2004.
Gerald R. Ford: Replaced President Nixon after the Watergate scandal for the final 2 years, however, he lost the 1976 election to Jimmy Carter.
Jimmy Carter: Lost the 1980 election to Ronald Reagan
Ronald Reagan: Was Re-elected in 1984.


KPI #4: Is there a correlation between Political Party and Untruthfulness
<img width="1208" alt="Image" src="https://github.com/user-attachments/assets/e1f3ca6a-07a8-48c4-b0f4-a8ef10aa2915" />

In this visualisation, I seeked to find if there was a correlation with the amount of untruthfulness, and the political party in which the speaker was a part of. I found that the Republican Party spoke the most amount of untruthfulness, at a total of -5,437, followed by thr Democratic party at -3,759, and finally the Independant Party, at -569. This could be skewed based on the data, considering there are 9 Republican Party Representatives, 9 Democrats and only 2 Independants, however, the republicans would sitll be the most untruthful based on the data we have and the trends. 


KPI #5: Sentiment Analysis of Misinformation
<img width="1201" alt="Image" src="https://github.com/user-attachments/assets/a74499d1-5b9e-442f-bd3d-35a42865a065" />

In this visualisation, we are analyzing the sentiment behind each statement spoken by different political parties. I created numerical values for each political party to help with future models in the Project. 1 is a Democrat, 2 is Republican and 3 is Independant. As shown on the graph, the total verdicts were -435.4 for Democrats, -594.8 for Republicans and -94.5 for Independants.


# Causal Inference & Correlation Analysis

For my data, I opted for option 3, creating a correlation matrix heatmap to see the correlation of my KPIs. The KPI I chose was #5, the sentiment analysis. When it comes to an election, the feelings and opinions of the people are what is most important, so I gauged the sentiment that people felt toward messages from the three different political parties in the dataset, Democrats, Republicans and Independant. The result of the heatmap is the following:

<img width="632" alt="Image" src="https://github.com/user-attachments/assets/6ba5a4d9-bef4-4c81-8114-46221f92729d" />

Looking at the heatmap, we see that the correlation result between sentiment and Political party was -0.02.

I then tried to create a casual inference model, but it did not turn out very well. I will attach it below. I worked at it for hours and could not get it to work.

<img width="647" alt="Image" src="https://github.com/user-attachments/assets/acdd531e-2197-476e-b7a6-87c11d85597e" />







