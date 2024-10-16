# Data-Professional-Engagement-Survey-Results
A visualization showcasing the results of a 2022 Workplace Engagement Survey shared by Alex the Analyst. This project was created as a result of his [Data Analyst book camp series](https://www.youtube.com/watch?v=pixlHHe_lNQ&list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF&index=41&ab_channel=AlexTheAnalyst) and showcases several skills using PowerBI. Below you can see a screenshot of the final visualization.
![image](https://github.com/user-attachments/assets/353b08f5-a6c2-40a2-841d-ccbd20b42eff)

### Programs Used ###
PowerBI

### Scope of Work ###
**Deliverables**
- An interactive dashboard in PowerBI

### Goal ###
The goal of this project is to explore PowerBI's interface and create a visualization similar to those found as a result of employee surveys in the workplace. These surveys provide businesses with insights into areas of opportunity such as employee satisfaction with pay or work/life balance. Assigning a number to these generally qualitiative metrics allows businesses to measure their employee engagement and analyze improvement over time. 

### Raw Dataset Transformations ###
This survey had several areas where survey takers could type in their answers. This resulted in a lot of unstandardized data. This unstandardized data is out of scope for this project so we had to make some transformations to keep those typed in survey reponses usable. <br>

| Data issue | Solution |
| ------------- |------------- |
| Unstandardized Data in "Favorite Programming Language"| Converted all non-standard responses to "Other"|
| Unstandaradized Data in "Job Title" | Converted all non-standard responses to "Other"|
| Salary measured in a range | Created additional measure that takes the average of the range|

### Data Opportunities ###
Taking the average of a range of salaries can present some inconclusive results. The most glaring situation can be noted at the top and bottom ranges. It is probably unlikely for someone in the tech industry to make $20,000 a year but that is the average of the 0-40k range. Additionally those who claim to make more than $225,000 a year are capped at 225,000 as the average of 225k is 225k. Additionally, there were opportunities to standardize the other categories to include popular written in answers. 

### Reflection ###
By the end of the project, I found myself finding PowerBI to be rather inutitive and enjoyable to use. In some instances, I enjoyed PowerBI over Tableau. My biggest disgust is the lack of public access to this program. Showcasing my work is much more difficult and it makes me lean towards using Tableau over it. 
