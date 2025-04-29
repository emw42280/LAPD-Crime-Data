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

Vandalism:  
- Vandalism cases stay relatively steady throughout the year but show slight rises in the spring and early summer (April to July) and drop off during the colder months. This trend suggests that vandalism may correlate with increased outdoor presence and less deterrent from cold weather.

Stolen Vehicles:  
- Stolen vehicle reports show the strongest seasonal pattern, peaking sharply in the summer, especially in August, and remaining higher through fall. The lowest numbers occur during the winter (especially February). This indicates that warmer months may see increased vehicle theft, possibly due to more travel and more vehicles being left unattended.


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
Helps identify gender-based vulnerability to weapon-related crimes and supports more targeted safety policies and victim support programs.

## **The Manipulations Applied to The Data Set as Part of the Analysis:**   
- Victim sex (male, female)
- Weapon Description (discludes "null")
- Crime count (visualization 1: count < 10k) (visualization 2: count > 10k)

## **Analysis and Results:** 
The data indicates that men have a higher likelihood of being victims of these violent crimes than women.  
Data points that stand out in the set:  
- The dataset separates handgun crimes from pistol crimes. For some reason, handgun crimes only include female victims (zero records of male victims). However, men are included as victims of pistol crimes, where they make up the majority.





