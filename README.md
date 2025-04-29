# LAPD-Crime-Data

## **Describing Our Dataset and What Data it Contains:**

The dataset we’re using represents crime statistics in Los Angeles as reported by the LAPD, with dates ranging from the year 2020 to 2024. Within the dataset are variables such as the type of crime committed, the year the crime was committed, the sex of the victim, the type of weapon used, and more. This dataset was created by the request of the FBI and is utilized by them today.  

# **Question 1: How do monthly crime patterns for assault, battery, burglary, vandalism, and stolen vehicles differ by month/season, and are there consistent seasonal peaks?**  
## Visualization 1: Monthly Data from 2020-2023
<img width="1220" alt="image" src="https://github.com/user-attachments/assets/86db3e62-46fa-4089-909d-aac2549d250f" />  

## Visualization 2: Monthly Data By Year (2020-2023)  

<img width="1401" alt="image" src="https://github.com/user-attachments/assets/92301bcb-846b-4201-958a-d4c8cb0b2bfe" />

## **Selecting The Crimes We Focused On**  
<img width="1329" alt="image" src="https://github.com/user-attachments/assets/bdb7cd55-b9c5-4623-acd4-e83d2505dae4" />  
We chose the five crimes with the highest frequency of occurence. The data with these crimes is more reliable to answer our general question of patterns as the crimes occur more.  

- We discluded identity theft because it doesn't behave the same way seasonally as the physical crimes we're studying, so including it would dilute our insights
- We discluded burglary from vehicle because we already included general burglary



## **Why This Question is Interesting and Important:**
Identifying seasonal patterns in assault, battery, burglary, vandalism, and vehicle theft helps law enforcement plan ahead, allocate resources efficiently, and launch targeted public awareness efforts during high-risk months. By anticipating when certain crimes are more likely to occur, agencies can increase patrols, adjust staffing, and encourage preventative actions from the community. This leads to more effective crime prevention, better resource management, and improved public safety outcomes.  

## **The Manipulations Applied to The Data Set as Part of the Analysis:**    
- Year (2020-2023 to disclude possible bias)
- Crime description (5 crimes with highest frequency of occurence)

## **Analysis and Results:**   
Assault:  
- Assaults show a small seasonal peak in the summer months, particularly in July, with a noticeable dip during the winter months (February and December). This suggests that assaults may increase slightly with warmer weather, possibly due to more outdoor activities and social interactions.

Battery:  
- Simple battery incidents follow a similar pattern to assault, with higher counts during the summer (June and July) and a decline in the winter (especially February). The peak in the summer months indicates that battery incidents may also be influenced by seasonal social activity.

Burglary:  
- Burglaries slightly increase during the summer months, peaking around June and July. There is a drop-off during the early part of the year (February and March) and again in late fall and winter. This pattern supports the idea that burglary is higher when people are more likely to be away from home during vacations.
- Another side point we discovered was that during the start of when COVID-19 lockdowns were implemented, there was significant spike of burglaires from April 2020 to June 2020. We believe this can be due to looting and such associated during that time.

Vandalism:  
- Vandalism cases stay relatively steady throughout the year but show slight rises in the spring and early summer (April to July) and drop off during the colder months. This trend suggests that vandalism may correlate with increased outdoor presence and less deterrent from cold weather.

Stolen Vehicles:  
- Stolen vehicle reports show the strongest seasonal pattern, peaking sharply in the summer, especially in August, and remaining higher through fall. The lowest numbers occur during the winter (especially February). Additionally, the extended daylight hours and higher levels of outdoor activity during the summer months may create more opportunities for theft, contributing to the seasonal spike.

## **Possible Bias:**  
The frequency of our selected violent crimes appears to drastically fall off after 2023. We’re not sure if this is an accurate representation, possibly a hole in the dataset.

To avoid potential error, we filtered the Year variable to 2020-2023 for Question 1, excluding 2024.

<img width="450" alt="image" src="https://github.com/user-attachments/assets/5f4d8427-cff7-4f9c-bb96-f9622d9824f8" />




# **Question 2: To what proportion are men and women victims of crimes involving different weapons?**  
 
## Visualization 1 (image 1+2): Crime count < 10k
<img width="1404" alt="image" src="https://github.com/user-attachments/assets/a6fbeb36-3976-4efa-a2eb-68327e6d6bb4" />  
<img width="1388" alt="image" src="https://github.com/user-attachments/assets/b7fee18f-8d25-459b-bc49-dee588a7ec43" />  

## Visualization 2 (image 3): Crime count > 10k
<img width="1320" alt="image" src="https://github.com/user-attachments/assets/c898628d-a6e3-4003-a871-e5b4c279e821" />

## **Why This Question is Interesting and Important:**  
Understanding the proportion of male and female victims in crimes involving different weapons sheds light on gender-based vulnerabilities and risks. Certain weapons may disproportionately affect one gender over another, revealing important patterns in how violence is carried out. This information is critical for designing more targeted public safety policies, law enforcement training, and community outreach programs. For example, if women are disproportionately victimized in crimes involving certain weapons, resources can be focused on prevention strategies and support services tailored to their needs. Additionally, identifying these patterns supports more equitable victim assistance programs and ensures that interventions are backed by data, ultimately leading to safer and more informed communities.

## **The Manipulations Applied to The Data Set as Part of the Analysis:**   
- Victim sex (male, female)
- Weapon Description (discludes "null")
- Crime count (visualization 1: count < 10k) (visualization 2: count > 10k)

## **Analysis and Results:** 
The data indicates that men have a consistently higher likelihood of being victims of violent crimes involving weapons compared to women. Across almost every weapon category — including firearms, knives, blunt objects, and physical force — male victims outnumber female victims. This pattern may reflect broader societal factors such as differences in behavior, occupation, or exposure to high-risk environments.

 **Notable Data Observations:**

Handgun vs. Pistol Victimization:
- A surprising distinction appears in the dataset between "handgun" and "pistol" crimes. For "handgun" incidents, there are only female victims recorded — no male victims are associated with this weapon category. This is an unusual outlier given the broader trends.
In contrast, "pistol" crimes (which are generally considered the same or very similar weapon type) show a male-majority victimization, consistent with the overall pattern of the dataset.

Potential Data Entry or Classification Issue:
- The separation between "handgun" and "pistol" could be due to inconsistencies or differences in how weapons were classified during police reporting. This raises a possible concern about the reliability of weapon categorization and suggests that some caution is needed when interpreting these specific categories.

Overall Weapon Trends:
- For high-frequency weapon types such as kitchen knives, blunt instruments (e.g., hammers), and physical attacks without weapons, male victims consistently dominate the counts.
In categories like mace/pepper spray and some cutting instruments, the gender gap is narrower, but men still slightly outnumber women.

**Summary:**
While the overall data shows men are more likely to be victims of weapon-involved crimes, some anomalies — like the "handgun" category — highlight potential areas where data reporting or classification methods may have introduced inconsistencies.





