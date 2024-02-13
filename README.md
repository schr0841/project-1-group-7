

# Japan Birth Demographics

This is Project 1 for Group 7 @ the U of M Data Visualization Bootcamp.

Presentation deck (Google slides):  https://docs.google.com/presentation/d/1X1nYIf1Nj5YNCgHWjrRg1SkMbKaOKO6lWD7IPjjwdfw/edit?usp=sharing

## Our Project Goal
This project aims to gain a comprehensive understanding of Japan's birth demographics over the past century (1899-2022) by analyzing collective data, with a specific focus on:
1. Total Fertility Rate (TFR):
•	Goal: Chart and analyze the TFR over 100 years, identifying periods of highs, lows, and fluctuations.
•	Expected Outcome: Understand the historical context and potential factors driving changes in TFR, such as economic conditions, social norms, and government policies.
2. Impact of Major Events on Stillbirths:
•	Goal: Investigate how major events, particularly World War II (1944-1946, despite data limitations), impacted fertility rates, stillbirth rates, and other key birth indicators.
•	Expected Outcome: Identify correlations between historical events and birth trends, providing valuable insights into societal responses to crises.
3. Rise of Out-of-Wedlock Births (ex-nuptial):
•	Goal: Analyze the trend in the number of children born out of wedlock over the past 70+ years, considering potential contributing factors.
•	Expected Outcome: Understand the evolving cultural and legal landscape surrounding marriage and childbirth in Japan.
4. Male vs. Female Birth Rates:
•	Goal: Investigate any trends in the disparity between male and female birth rates, considering possible biological and social influences.
•	Expected Outcome: Gain insights into potential imbalances and their implications for future population demographics.
Additional Considerations:
Address data limitations due to World War II by exploring alternative sources
Consider incorporating contextual information like economic data, social policies, and cultural shifts for a richer analysis.

## What We Are Using 
Data Sources
* Kaggle: https://www.kaggle.com/datasets/webdevbadger/japan-birth-statistics 

Languages
* Python (Matplotlib, Pandas, Seaborn)

## Analysis


Fertility Rate over the past 100 years:

![total fertility rate](https://github.com/schr0841/project-1-group-7/assets/12236689/44395ec0-6474-489a-8659-df773fc6cd57)

We can plot the fertility rate vs year for 1947 to 2022 on a line plot in seaborn. We notice that the fertility rate has been generally decreasing, with a large sudden decrease that only affects the year 1966. Why did the fertility rate decrease so dramatically for just this year? Possible explanations could be war, famine, or a pandemic. 

Infant death rate as proxy for fertility rate:

![infant deaths](https://github.com/schr0841/project-1-group-7/assets/12236689/90c6c9db-dc2d-431f-9260-601280d53b49)

As we can see, there is a sharp decrease in the infant death rate in both 1906 and 1966. This leads us to speculate that there were fewer children being born in those years. According to our research, In 1966 Japan, there was a superstition that affected the number of births. This superstition is based on astrology. In Eastern astrology, each year is represented by a different animal, and the people born during the year take on some characteristics of that animal. 

The Fire Horse is the 43rd combination of the sexagenary cycle, and it occurred in both 1906 and 1966. It will happen again in 2026. According to superstition, women born during the year of the Fire Horse would have bad omens and would not be suitable for marriage. As a result, some couples in Japan chose to not have children in 1906 and 1966.


<img width="1470" alt="Screenshot 2024-02-10 at 12 25 52 PM" src="https://github.com/schr0841/project-1-group-7/assets/151413928/c3d692fc-99bc-4d73-8763-2682d1794968">

A large number of still births in the early 1900s were possibly due to abortions and infanticide being recorded as stillborn, this prompted regions in Japan to have an officer appear during a birth. It looks like larger numbers of stillbirths were recorded after WWII ended in 1945, perhaps reflecting societal responses to crises.

<img width="751" alt="Screenshot 2024-02-10 at 12 25 29 PM" src="https://github.com/schr0841/project-1-group-7/assets/151413928/4c548832-4f57-4c0d-9042-acd75635dbbf">

Japan’s stillbirth rate has consistently gone down since the war possibly attributed to universal health care every woman gets, and the populace decreasing.

Gender Birth Rates: 
Gender ratio is fairly consistent at 51% male / 49% female. While there may be a higher ratio of male births in Japan, the difference is fairly small and similar to what is observed in overall human population.
![image](https://github.com/schr0841/project-1-group-7/assets/153476236/efb39124-c6f4-4dd6-bf97-9404bc31baf2)
![image](https://github.com/schr0841/project-1-group-7/assets/153476236/4449bcd9-788b-4e5a-a62b-7231f4b719d8)

Ex-Nuptial Births, 1947-2022
At first glance, it appears that ex-nuptial births were at a relatively high point in the immediate post-war years, compared with subsequent decades. 
#INSERT IMAGE: ExNuptialBirthsYear 
When comparing Ex-Nuptial Births with Total Live Births by year, however, we see that the high point in ex-nuptial births corresponds with a similar high point in the total number of live births. The peak in ex-nuptial births may not necessarily be unusual but rather in-step with the high overall births. 
![image](https://github.com/schr0841/project-1-group-7/assets/_______________________________________________).
![image](https://github.com/schr0841/project-1-group-7/assets/_______________________________________________).
By plotting ex-nuptial births as a percentage over total live births over time, we see that ex-nuptial births approached 4% of total live births. From the early 1950s through 2022, ex-nuptial births as a percentage of total live births has remained close to 2%. Whether a near-4% rate is significant -- related to something other than random chance -- is something we can't determine using our current statistical skills. 
![image](https://github.com/schr0841/project-1-group-7/assets/_______________________________________________).

## Additional Considerations and Limitations
Some data is missing between the years 1944-1946 due to records lost during World War II. 

Ex-Nuptial Births in Japan: 1947 - 2022
Note: Between the years 1947 and 2000, the data set reports ex-nuptial births every five years. From 2000 to 2022, it reports ex-nuptial births every year.

## References
Drixler, Fabian F. “Hidden in Plain Sight: Stillbirths and Infanticides in Imperial Japan.” The Journal of Economic History, vol. 76, no. 3, 2016, pp. 651–96. JSTOR, http://www.jstor.org/stable/43917379. Accessed 10 Feb. 2024.

Hashimoto, Masanori. “Economics of Postwar Fertility in Japan: Differentials and Trends.” Journal of Political Economy, vol. 82, no. 2, 1974, pp. S170–94. JSTOR, http://www.jstor.org/stable/1829999. Accessed 10 Feb. 2024.

Kanae Kaku (1975) Increased induced abortion rate in 1966, an aspect of a Japanese folk superstition, Annals of Human Biology, 2:2, 111-115, DOI: 10.1080/03014467500000651

Yamada, H. Superstition effects versus cohort effects: is it bad luck to be born in the year of the fire horse in Japan?. Rev Econ Household 11, 259–283 (2013). https://doi.org/10.1007/s11150-012-9162-9
