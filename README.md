# LAPD-Crime-Data

## **Describing Our Dataset and What Data it Contains:**

The dataset we’re using represents crime statistics in Los Angeles as reported by the LAPD, with dates ranging from the year 2020 to 2024. Within the dataset are variables such as the type of crime committed, the year the crime was committed, the sex of the victim, the type of weapon used, and more. This dataset was created by the request of the FBI and is utilized by them today.  

# **Question 1: How do monthly crime patterns for assault, battery, burglary, vandalism, and stolen vehicles differ by month/season, and are there consistent seasonal peaks?**
<img width="1220" alt="image" src="https://github.com/user-attachments/assets/86db3e62-46fa-4089-909d-aac2549d250f" />


## **Why This Question is Interesting and Important:**
Revealing seasonal crime trends helps law enforcement plan ahead, allocate resources, and raise public awareness during high-risk months.

## **The Manipulations Applied to The Data Set as Part of the Analysis:**    
- Year (2020-2023 to disclude possible bias)
- Crime description (5 crimes with most volatility)

## **Analysis and Results:**   
Assault:  
- Appears to peak in the summer consistently

Battery:  
- Crimes involving battery appear to decrease with the start of the new year and increases in warmer months

Burglary:  
- Peaked during spring 2020, with covid locksdowns.

Vandalism:  
- Remained stable year round (2020, 2023), peaked in summer (2021), Peaked in spring (2022)

Stolen Vehicles:  
- Increased during covid lockdown. In 2021 & 2023 peak months were October-November



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





