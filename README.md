# Analyzing Calgary Satisfaction Data and Safety
## *Olatomi Adigun, Gigi Chung, James Oblea, Jericho Pantony, Michaela Reyes*
### October 18, 2023

Calgary is currently experiencing significant population growth, as highlighted in a recent report by CBC, which has identified a "record annual population surge" (Fernando, 2023). For individuals new to Calgary, there are several crucial factors to take into account when selecting an area to live and call home. Among these factors, a top priority is safety which will also play as our main point of interest in our exploration. Our project aims to evaluate the satisfaction levels reported by current Calgary residents in the year 2022 and gain insights into the factors that contribute to their satisfaction. By doing so, we strive to offer valuable information that can assist newcomers in making well-informed decisions when establishing themselves in Calgary. Our target audience for our project consists of newcomers from different backgrounds intending to relocate and establish themselves in Calgary. Through an analysis of this dataset, our primary objectives are to address four key questions:

</div>

1. **Which area(s) in Calgary has the highest satisfaction level?**
2. **How does satisfaction vary among different demographic groups (e.g. age, gender, income, education) in different areas of Calgary?**
3. **How safe do Calgarians feel and what areas report higher safety levels? Does safety correlate with satisfaction levels?**
4. **Can we find relationships between community crime statistics and reported levels of satisfaction on safety?**

# Datasets

<div style="text-align: justify;">

The 2022 Fall Survey of Calgarians (The City of Calgary, 2023) is an annual telephone survey conducted by the City of Calgary with a randomly selected sample of Calgarians aged 18 years and older. As it is on the City of Calgary’s Open Data Portal, we have permission to access and use the dataset. It is a structured dataset in tabular format. This dataset consists of 2,501 rows, each representing an individual respondent, and 141 columns. The columns within the dataset are used to record responses to survey questions. However, instead of directly displaying the actual categories or responses, the cells under each column are encoded with numerical values. These numerical values will require mapping to their corresponding categories or labels in order to make the data more readable and interpretable.

A separate Excel file of metadata summarizes how each question number and corresponding numerical values are mapped to the actual question and responses. For example, the question number “q10” is mapped to “How safe do you feel or would you feel walking alone in your neighborhood after dark?”, then values 1 to 6 are mapped to “q10”, with 1 being “very safe”, 2 as “reasonably safe”, 3 as “somewhat unsafe”, 4 as “very unsafe”, 5 as “don’t know”, and 6 as “don’t know/ not sure”.

In addition to the main dataset on the satisfaction of residents living in Calgary areas, we will employ a peripheral data set that includes a wide array of information regarding Calgary crime statistics. This dataset also originates from the same source as the survey data and includes 76,975 rows and 11 columns on the date, location, number of crime occurrences, and type of crime in Calgary. We plan on drawing relationships between these variables and reported satisfaction levels especially regarding safety.

</div>

# Conclusion and Future Directions

<div style="text-align: justify;">

In this study, we conducted an analysis of survey satisfaction and safety data in Calgary, while also taking into consideration crime statistics, in order to gain a comprehensive understanding of the areas and factors that influence higher satisfaction rates. Our primary objective was to provide newcomers with valuable information to make well-informed decisions when considering a move to Calgary.

</div>

## Key Findings

<div style="text-align: justify;">

<b>Ward-Specific Analysis: </b> 
In response to our first guiding question, we identified that wards 14, 12, and 8 reported the highest average satisfaction levels, while wards 9, 5, and 10 had the lowest satisfaction levels. Notably, the range between the highest and lowest satisfaction rates was relatively small, typically ranging between 7 and 8. To simplify our analysis, we categorized responses from 7 to 10 as "good," assigning them a value of 1, while all other responses received a value of 0. <br>

<b>Demographic Variation:</b> 
In addressing guiding question 2, we examined how satisfaction levels vary among different demographic groups. We found that certain demographic factors, such as age, gender, and income, had varying influences on residents' satisfaction levels. Expanding on this aspect could provide valuable insights into specific groups' experiences within the city. <br>

<b>Safety Perceptions:</b> 
Guiding question 3 led us to employ heatmaps to visualize the proportions of Calgarians who feel safe. Our analysis revealed that wards 2, 3, and 12 reported the highest levels of safety, while wards 5, 9, and 10 reported the lowest levels of safety.<br>

<b>Crime and Safety Correlation:</b> 
In addressing guiding question 4, we created a heatmap illustrating community crime in Calgary and compared it to residents' perceptions of neighborhood safety. While we found consistent trends, with wards 9 and 10 being the least safe and wards 1, 2, and 6 being the safest, certain wards, such as 12 and 14, reported higher crime rates despite residents feeling safe.

</div>

<div style="text-align: justify;">

<h3>Limitations</h3> We should also address the limitations of our study more explicitly. These limitations may include the representativeness of the sample, the potential for confounding variables, and the restriction to a specific time frame (2022). Acknowledging these limitations is crucial for a more accurate interpretation of our findings. <br>


<h3>Practical Implications</h3> Our findings may also have practical implications for city planning and decision-making. City officials, policymakers, and community organizations can use this data to inform strategies aimed at enhancing safety and satisfaction for all residents. The information gathered here can contribute to more targeted interventions in areas with lower satisfaction and safety levels. <br>


<h3>Future Research</h3> Ultimately, analyzing perceptions of safety and satisfaction is a complex task, and our analysis serves as a starting point. Additionally, understanding a newcomer’s needs is a diverse and fruitful process, as there is no “one size fits all” solution. Nevertheless, several avenues for further research and development should be explored: <br>

</div>

1. <div style="text-align: justify;"> <b> Test and analyze with more variables:</b>  Consider including additional variables such as the number of schools, transit stops, and emergency services within each ward, as well as their proximity to residents. Applying statistical significance tests to these variables can help identify the most significant factors contributing to satisfaction and safety levels. </div> <br>
2. <div style="text-align: justify;"> <b>Conduct a time-series analysis:</b> Expanding the scope beyond the year 2022 to encompass historical trends and patterns for satisfaction and safety could provide deeper insights. </div> <br>
3. <div style="text-align: justify;"> <b>Include more comprehensive crime statistics:</b> While incorporating more crime statistics may be beneficial, it's essential to carefully consider the relevance of each crime type to safety levels. Not all crimes may directly impact residents' feelings of safety. Therefore, further research is needed to understand the relationship between crime statistics and safety perceptions. </div> <br>

<div style="text-align: justify;">

In conclusion, our analysis serves as a valuable starting point in understanding the factors influencing satisfaction and safety in Calgary. By addressing these considerations and future research opportunities, we aim to contribute to a more informed, safe, and satisfied community for both newcomers and longtime residents.

</div>


