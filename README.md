# Analysis-of-Nutritional-Data-for-Disease-Management

![image](https://github.com/user-attachments/assets/02b0420a-7cf2-48cf-8264-bcbb3eab559f)


## INTRODUCTION

The health and wellness of individuals are significantly influenced by dietary habits, physical activity levels, and underlying health conditions. As the global focus shifts towards preventive healthcare and nutrition awareness, it becomes increasingly important to understand how these variables interact across different population groups. This dashboard offers a detailed visualization of key health and nutrition indicators such as calorie intake, fat consumption, activity levels, and disease prevalence, broken down by gender and age demographics. By dissecting this data, the dashboard not only highlights areas of nutritional excess or deficiency but also uncovers correlations between lifestyle choices and the emergence of diet-related diseases.

The aim of this analysis is to provide a clear, data-driven foundation for improving public health outcomes. It sheds light on patterns such as the overconsumption of fat among highly active individuals, the lack of calorie regulation among older adults, and notable gender differences in disease risk. Through such observations, this dashboard serves as a powerful tool for policymakers, health professionals, and wellness program developers, enabling them to tailor interventions that are both demographic-specific and behaviorally informed.

## DATA CLEANING 
The dataset was gotten from Kaggle, and several strategies were applied to ensure data consistency and accuracy:
* Duplicate Removal: Duplicate rows were identified and deleted to prevent inconsistent results.
* Text to Columns: Combined data points in a single column were split using the Text to Columns function, ensuring each value was properly categorized.
* Date Formatting: Inconsistent date entries were corrected, with all dates standardized to a uniform date format for accurate time-based analysis.
* Standard Table Conversion: **The dataset was transformed into a structured Excel table to enable easier management, automation, and dynamic analysis. These steps helped transform the raw dataset into a clean, structured foundation for insightful analysis.

## PRE ANALYSIS

Before building the charts, I conducted a pre-analysis to better understand the dataset and guide my storytelling process. This involved breaking down the data into meaningful components:

* Project Split: I categorized the data points into dependent and independent variables, helping me understand the relationships within the dataset and what types of insights could be extracted.
* Potential Analysis & Questions: From the grouped variables, I generated key questions that the dataset could answer. This step highlighted the potential insights hidden within the data, even before visualizing it.
* Preliminary Insights: By thinking through the questions and data points, I uncovered early insights, which made it easier to shape the narrative and focus the analysis on valuable outcomes
* Storytelling: Once I had a clear understanding of the dataset, I could tell a story from it. By putting together the relationships between the datapoints and the insights uncovered.
* Industry & Stakeholders: This process helped me identify the relevant industry, the stakeholders who would benefit from the analysis, and what success would look like for the organization based on the findings.

## ANALYSIS OF THE CHARTS

### Activity Level by Meal Suggestions

![image](https://github.com/user-attachments/assets/8c97fb76-9809-47ac-bff6-8e38fec2b914)

The distribution of meal suggestions—breakfast, lunch, and dinner—reveals that individuals who are moderately active receive the highest number of meal plans, each type totaling 420 suggestions. The number of suggestions decreases as we move toward either extreme of activity level, with extremely active individuals receiving only 138 suggestions. This suggests a strong focus on nutritional planning for moderately active individuals, possibly due to their balanced lifestyle or higher representation in the dataset.

### Dietary Preference Overview

![image](https://github.com/user-attachments/assets/57c88d66-6f02-476a-8052-25c10e2c16a1)

The chart shows that the majority of individuals identify as omnivores, with a count of 564, making it the most common dietary preference. This is closely followed by vegetarians (546), and pescatarians (448). Vegans represent the smallest group, at 140. This distribution indicates a high prevalence of mixed or flexible dietary patterns, with relatively fewer individuals adhering to strict plant-based diets.

### Activity Level by Carbohydrate Impact

![image](https://github.com/user-attachments/assets/13734935-fe16-4a61-84f0-7a82cddf6ae5)

When examining carbohydrate impact by activity level, the moderately active group again leads with the highest cumulative carbohydrate effect at 109,975. This is followed by the very active and lightly active groups. The extremely active group, however, shows a significantly lower carbohydrate impact at just 40,219. The trend implies that carbohydrate management is most critical for those with moderate to high activity levels, likely reflecting dietary adjustments or metabolic efficiency.

### Highest Disease

![image](https://github.com/user-attachments/assets/bd69bbdc-f7f9-4651-9cfd-8dd1dcb5e99c)

Weight gain emerges as the most prevalent health concern, with 1,312 occurrences recorded. Other prominent disease combinations include weight gain with hypertension and diabetes (129), kidney disease (91), and obesity (82). A smaller cluster also combines diabetes, acne, and weight gain (45). The high incidence of weight-related issues suggests it is a central focus of this nutritional dataset, indicating its association with multiple comorbidities.

### Activity Level by Disease

![image](https://github.com/user-attachments/assets/0db9d45e-9a70-421f-b77d-f88af281ee1d)

Disease frequency appears to correlate with moderate physical activity levels, peaking at 420 cases. This is followed by sedentary (403) and lightly active (396) individuals. Interestingly, extremely active individuals report the lowest number of disease cases at 138. This pattern suggests that while moderate activity is common, increased levels of activity might contribute to lower disease risk or that fewer individuals in the extremely active group have been diagnosed.

### Calorie Consumption by Gender

![image](https://github.com/user-attachments/assets/76fbfd8c-4e5c-482e-aa23-5fa4f4dfbd06)

The calorie consumption distribution by gender shows that males consume more calories (1,945,895) than females (1,783,661). This disparity may reflect differences in metabolic rate, body mass, or lifestyle habits between genders. It also suggests that males may be at a higher risk of excessive caloric intake, which may relate to the prevalence of weight-related issues observed earlier.

###  Age by Highest Fat Intake

![image](https://github.com/user-attachments/assets/3efec92d-f1ff-45d5-9f4f-fa031d18025c)

Among all age groups, age 28 stands out with the highest fat intake, recording 5,094 units, followed closely by age 25 at 4,856. A gradual decline in fat intake is observed across subsequent ages, reaching the lowest at age 22 with 3,491. This trend indicates that fat consumption tends to peak in the mid-to-late 20s and tapers off with age, possibly due to increased dietary awareness or health management in older individuals.

## OBSERVATIONS

* The highest number of meal suggestions is provided for moderately active individuals, indicating a focus on this group. However, extremely active individuals receive the least number of suggestions. This imbalance may leave the most physically demanding group underserved in nutritional planning.
* Omnivores dominate the dietary preference segment, followed by vegetarians and pescatarians. Vegans represent the smallest portion, suggesting either lower participation or limited dietary support options in the system.
* Carbohydrate impact appears highest for moderately and very active individuals, suggesting a higher intake for energy support. Interestingly, extremely active individuals have a dramatically lower carbohydrate impact, which could imply inadequate energy provisioning.
* Weight gain is the most prevalent disease, often accompanied by hypertension, kidney disease, and diabetes. This indicates a trend of comorbidities linked to poor dietary habits and possibly low physical activity levels.
* Individuals who are moderately active or sedentary account for the majority of disease cases. This suggests that middle-ground or low activity levels may not be sufficient in combating diet-related diseases.
* Male calorie consumption significantly exceeds that of females. This reflects either biological needs or cultural consumption patterns, which may contribute to a higher prevalence of diet-related health issues in men.
* The age group with the highest fat intake is 28, followed by 25. Fat consumption then declines steadily with increasing age. This indicates that younger adults might be more prone to unhealthy fat consumption patterns.

## RECOMMENDATIONS

* Increase meal planning for extremely active individuals to support their higher caloric and nutrient requirements. This can help improve performance, recovery, and overall health among this active demographic.
* Develop more tailored and appealing meal plans for underrepresented groups like vegans. This can encourage inclusiveness and ensure all dietary preferences are nutritionally well-supported.
* Evaluate and adjust carbohydrate recommendations for extremely active individuals to better align with their energy output and avoid underperformance or fatigue-related issues.
* Launch multifaceted interventions focusing on both weight control and the prevention of associated conditions. Educational programs and structured meal planning can play a critical role in mitigating these issues.
* Encourage a shift towards higher physical activity levels through public health campaigns and incentives. Complement this with nutritional guidance that supports increased movement and disease prevention.
* Provide gender-specific dietary education and caloric control strategies, especially for males, to promote balanced intake and reduce risks of obesity, cardiovascular diseases, and related conditions.
* Focus nutritional outreach on young adults, especially in their 20s, to promote awareness around healthy fat sources and portion control. Early intervention can help prevent long-term health risks.

## CONCLUSION

This analysis reveals a complex interplay between diet, physical activity, and health outcomes that cannot be overlooked in the conversation about public wellness. Across the charts, significant patterns emerge—for instance, a tendency for younger individuals to consume excessive calories, or for moderately active groups to still suffer from high rates of diet-related diseases. The visual data highlights not only the differences between genders and age groups but also the impact of lifestyle on disease prevalence and nutritional sufficiency.

Such insights are critical in guiding effective health strategies and personalized interventions. They call for a holistic approach—one that combines education on balanced diets, encouragement of physical activity, and the monitoring of disease risk factors. As health systems strive for efficiency and impact, this dashboard provides a solid foundation for informed decision-making. Ultimately, the goal is to leverage these insights to reduce preventable diseases and enhance the quality of life across various communities.
