# Project Background
Global shark attacks, recorded from as early as 1868 through to 2017, have increased public fear and apprehension towards sharks, especially amongst tourists, surfers and beach lovers.

There is a significant amount of data regarding locations, dates, information on the victims and the circumstances surrounding the occurrence, such as the victim's activities before the attack. This project carefully analyses the data to reveal critical insights that will improve coastal safety measures and educate the public on this matter to safely enjoy the ocean.

Insights and recommendations emerge from these key areas:

- **Geographic Area Focus:**  Evaluation of primary locations of these attacks, including country, city and areas, focusing on the time of day these attacks occurred, offering a better understanding of peak times for such attacks

- **High Risk Activities:**  An analysis of potentially risky behaviours and activities that may have contributed to the incidents and an evaluation of their influence/impact on the likelihood of attacks and understanding their impact on it.

- **Key Shark Species:** An analysis of the shark species dominating the attacks

- **Regional Comparison:**  A comparison of attack patterns across different regions

For a dynamic exploration of the data, an interactive PowerBI dashboard can be found [here](https://app.powerbi.com/view?r=eyJrIjoiOGEzZGFiYmMtYjIxYy00N2IwLWJjM2UtZjliZjRmMTdjOTg4IiwidCI6ImU4Y2RiYjFmLWYwNzItNDk5Mi05ZTYzLWNiZDEzMDM0OTBmNSIsImMiOjh9)

The queries used to clean, organise, and prepare data for the dashboard can be found [here](https://docs.google.com/document/d/1s1mA_NPUWMitHRODJC-xTtIqo-Cv3_e7-Z4WVrczu70/edit?usp=sharing)





# Data Structure & Initial Checks

The  main database structure, as seen below, consists of a single table with a total row count of 6095 records. A description of each table is as follows:
  
  ![image](https://github.com/user-attachments/assets/e73bc585-0d95-41c1-96ab-c17668a5548f)





# Executive Summary

### Overview of Findings

Shark attacks remained fairly constant between 1990 and 2016. The year 2015 recorded the highest number of shark attacks. There was a noticeable decline in 2017, and it is predicted to continue declining over the coming years. This prediction is broadly linked to increased awareness, better human behaviours around water and the changes caused by the recent pandemic in 2020.  The USA accounted for 35% of these incidents, with Florida as the area with the most attacks worldwide. Surfers and swimmers made up 30% of the victims, and about 15% of the attacks happened during surfing activities. 

The following sections will look into other contributing factors and emphasise areas for improvement.

Below is the overview page from the PowerBl dashboard, and more examples are included throughout the report:

![image](https://github.com/user-attachments/assets/9a71af24-1e12-4ef4-a284-6b5f9bfcc5d2)







# Insights Deep Dive
### Geographic Area Focus:

* **Where and When Do Shark Attacks Happen and Occur?**

Shark attacks are most common in countries like the USA(35%), Australia(22%) and South Africa (9%).
  
The Florida area stands out as having the highest number of attacks globally 1015(16%), with particularly affected locations like new smyrna beach, daytona beach, ponce inlet, cocoa beach and florida keys. 

Another hotspot is New South Wales, Australia,  which recorded 476(7.8%) of attacks, especially in locations like Melbourne Beach.

Most shark attacks occurred in the afternoons. About 22%(1340) of all attacks took place in the afternoons, while 15% occurred in the mornings. The least amount of attacks happen at night, with only about 2%(118).
  
[Visualization specific to category 1]


### High Risk Activities:

* **What Risky Activities**

Swimming and surfing are the activities associated with 30%(1813) of all shark attacks.

Surfers, in particular, are at higher risk because of  prolonged exposure to deeper parts of the water, which can lead to a higher risk of major and fatal injuries if an attack occurs.  

[Visualization specific to category 2]


### Key Shark Species:

* **Shark Species Involved**

In the shark species category, White sharks are responsible for more than 10% (623) of these attacks, followed by tiger sharks at about 4%.

The white sharks dominated these attacks at any time of the day and caused major and fatal injuries.


[Visualization specific to category 3]




# Recommendations:

Based on the insights and findings above, the following recommendations have been provided: 

* The majority of the attacks occurred in the afternoon, and others in the morning, which aligns with the peak times people visit the beach. Increasing staffing and safety personnel around these peak times will help to control and minimise situations that cause these attacks.
  
* Potential Fatal attacks can be reduced during these attacks with quick medical assistance.
  
* Partnering with communities to educate surfers, swimmers and beachgoers about safe behaviours like avoiding activities that might provoke sharks to attack or mislead them to think an object is prey will help lower the chances of shark attacks. 
  
* Performing activities in pairs can also help deter sharks from attacking when compared to activities performed isolated.
  


# Caveats and Assumptions:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Data Limitations and Gaps

The data is not perfect. There are gaps in the data and many missing details. It is not 100% clean and accurate. 

The current and future predictions of shark attacks were made based on real events that occurred across the world, like the global pandemic.
  
* Underreporting  and Misreporting

Several cases lacked sufficient detail for proper classification, especially in the years falling below 2010 and also in developing countries, which means some incidents may not be officially accounted for.
  
* Species Misidentification

 Several cases involved inaccurately naming and blaming a type of shark due to the time of the incident, like nighttime and the stressful circumstances during the attacks, making it difficult to correctly identify the shark.
