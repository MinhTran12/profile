# Personality and Stress: Analyzing Social Media Usage's Stressthrough the Big Five Mode

This study investigates how individual differences in personality, based on the Big Five model, influence physiological stress responses for social media usage.

## Data Processing

We used the K-EmoPhone dataset, a rich collection of multi-sensor information from 77 South Koreans participants, to examine the heart rate variability (HRV) and electrodermal activity (EDA) as biological indicators of stress.

Using Python, we employed various data preprocessing techniques to isolate social media usage events, eliminating confounding factors such as background processes and physical activity. On the otherhand, CVSD (a standardized HRV metric) and Skin Conductance Response (SCR) frequency based on social media usage timepoints were calculated for HRV and EDA as stress measurement stand-ins respectively.

<div class="single-img">
    <img src="images\personality-stress\preprosessing_feature_extraction.png">
</div>

## Data Analysis

A multivariate multiple regression analysis revealed that conscientiousness negatively correlates with HRV (indicating higher stress), and openness negatively correlates with EDA (also indicating higher stress). This ultimately suggests a person scoring high in conscientiousness and openess display higher stress levels when using social media. These relationships were significant when focusing on these two traits alone, though the overall effect sizes were modest when considered together (R² between 0.11–0.16).

There are limitations such as the absence of baseline physiological measurements, potential sensor inaccuracies, and limited generalizability due to cultural homogeneity in the dataset. Nonetheless, we do believe the results warrants further research on the relationships between personality traits and social media usage, whether these aspects act as stressors or coping mechanism.

<div class="double-img">
    <img src="images\personality-stress\scatter_eda_open.png">
    <img src="images\personality-stress\scatter_hrv_cons.png">
</div>
