# US-Accidents-Analysis
US Accidents Analysis – Exploratory Data Analysis (EDA)

This project explores traffic accident patterns in the United States using a sample of the US Accidents dataset. The goal is to understand how various factors—time, weather, environmental conditions, and traffic infrastructure—impact accident frequency and severity.

# Methodology

This analysis focuses on understanding accident patterns using temporal, environmental, and weather-related variables. The dataset was first cleaned and prepared by extracting key features such as hour of day, day of week, weather condition, visibility, temperature, and road environment indicators. Time-based variables were converted into numeric form to enable grouping and pattern detection. Accident counts were aggregated by hour and weekday, while weather conditions were filtered to include the most frequent categories. A Random Forest model was also trained to evaluate which features contribute most to predicting accident severity.

# Visualization

Several visualizations were created to explore trends within the dataset. A bar chart of accidents by hour of day highlighted changes in accident frequency throughout a 24-hour period. Another bar chart showed accident distribution across days of the week. A grouped bar chart visualized how severity levels differ under various weather conditions. A heatmap displayed correlations between severity and selected environmental and atmospheric features. Finally, a feature-importance chart ranked variables such as pressure, temperature, and visibility to illustrate their contribution to severity prediction.

# Key Insights

Accidents rise sharply during peak commuting hours, with a major spike around 11 AM and another during the early evening. Early morning hours (3–5 AM) report the lowest accident counts. Weekdays experience significantly higher accident volumes, especially Tuesday through Thursday, compared to weekends when traffic is lighter. Clear weather has the highest number of accidents overall — not because it is more dangerous, but because more people drive under clear conditions. Hazardous weather such as rain or fog leads to fewer accidents but tends to increase severity. Correlation results indicate that no single feature strongly determines accident severity; however, machine learning results show that atmospheric factors like pressure, temperature, and humidity contribute most to predicting severity, while road features such as traffic signals and crossings have smaller but still noticeable effects.

# Conclusion

The analysis reveals that accident frequency is primarily influenced by traffic density — specifically time of day and weekday patterns — while accident severity depends more on environmental and weather factors. Clear-weather conditions produce the highest number of accidents due to heavy road usage, whereas severe weather conditions, though less common, increase the likelihood of higher-severity crashes. Since no single factor strongly predicts accident severity, a combination of environmental, infrastructural, and weather-related variables must be considered. These findings emphasize the need for targeted traffic management during peak hours and enhanced safety measures under adverse weather conditions.
