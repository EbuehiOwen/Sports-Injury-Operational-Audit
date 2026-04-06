2021–2025 Sports Injury & Medical Operational Audit 
Situation 
This report analyses 15,000 medical records and the management of a medical budget 
of €27.7M over the course of 4 seasons between 2021 and 2025 to evaluate the financial 
efficiency and clinical effectiveness of the organization’s injury management. Key 
f
indings include a highly stable spend to workload ratio of approximately €1,360 for every 
1000 minutes played and a localized recovery spike in the 3rd season (2023–2024) 
driven by an increase in severe cases. 
Task 
My objective was to perform an audit on: 
• Medical efficiency by measuring the days till recovery against the cost of 
treatment. 
• Injury data for age and gender to determine if gender-specific safety protocols are 
required. 
• Treatment method effectiveness in restoring athletes to full health. 
• Which coaching styles were getting injured. 
• What regions were getting the greatest number of injuries. 
• What playing surfaces caused the most injuries. 
• Average recovery time. 
Action 
I engineered a Star Schema data model and developed advanced DAX measures to normalize 
the data.  
Specifically, I: 
• Established a multi dimensional framework to measure days to recovery against the cost 
of treatment across the different injury events. 
• Identified the most effective treatment method for a speedy recovery by analysing the 
average days to recovery across all treatment methods, segmented by severity to ensure 
a fair comparison.  
• Developed a custom Spend Efficiency metric to show the cost per 1,000 Minutes Played 
to neutralize the impact of fluctuating season lengths and athlete exposure. 
• Analysed coach and team performance metrics which revealed high cardinality in the 
coaching dataset with an almost 1:1 injury-to-coach ratio.  
• Conducted a regional risk assessment across four European regions. 
• Cross examined 14 unique playing surfaces against competition tiers to isolate high risk 
environments. 
• Conducted an injury volume analysis between Professional and Amateur athlete tiers to 
identify the primary drivers of clinical workload. 
• Dug deeper into the increase in the average recovery time for the 2023-2024 season even 
though the total spent for that year was lower than the previous year. 
• Analysed how age and gender affect injury occurrence. 
Results 
• Analysis of treatment methods showed that rest and ice/heat therapy are the most 
effective methods at restoring an athlete to full health. 
• I proved that despite a €4M variance in annual spending, the organization’s average unit 
cost of safety remained consistent at €1,360 per 1,000 minutes. 
• I discovered that 99% of coach entries contained only a single injury event, rendering an 
individual coach’s consistency metrics statistically insignificant. 
• While Central Europe reported the highest total injury volume with 33.7% of total cases 
(5026 injury reports), Western Europe exhibited a higher relative frequency of 'Severe' 
injuries (15.1%), suggesting variations in playing intensity or environmental risk factors 
across regions. 
• Indoor Courts and Grass emerged as the highest injury causing environments. However, 
the data revealed a consistent 65-70% increase in amateur injuries when compared to 
professionals across all surfaces. 
• There was significant amateur strain, where non-professional athletes account for 70.7% 
(10,610 cases) of the total injury volume and professionals having 29.3% (4,390 cases). 
• The 2023–2024 season exhibited the highest recovery time of 51 days with further analysis 
indicating it was a period of more severe injuries that cost the team despite having less 
total injuries. This is also supported by the spend efficiency being the highest in that 
season. 
• Older players are more likely to get injured with athletes over 30 having the most injuries 
and those below 20 having the lowest number of injuries. Women are also more likely to 
get injured with 65.5% of all injuries from women. 
Recommendations 
1.  
Invest in safer playing surfaces: Allocate more funds toward maintaining and expanding 
the use of lower-risk surfaces such as clay, track, and field. These environments consistently 
show reduced injury rates, which translates into lower medical costs and improved athlete 
availability. 
2.  
Prioritize amateur athlete safety programs: Since amateur athletes account for over 70% 
of total injuries, targeted training, conditioning, and safety protocols for this group will yield the 
greatest reduction in healthcare spend and overall injury volume. 
3.  
Enhance preventive care and monitoring: Introduce regular screenings, physiotherapy 
check-ins, and load management strategies to reduce recurrence rates (currently 19.83%). 
Preventive measures are more cost-effective than reactive treatment. 
4.  
Regional risk mitigation: Develop tailored safety initiatives for Central and Western 
Europe, where injury severity and volume are highest. This may include stricter competition 
regulations, improved medical staffing, or localized training adaptations. 
5.  
Gender- and age-specific protocols: With women representing 65% of injuries and 
athletes over 30 showing higher vulnerability, customized training loads, recovery programs, and 
protective measures should be implemented to address these demographic risks. 
