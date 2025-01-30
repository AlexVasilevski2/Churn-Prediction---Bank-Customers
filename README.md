<h1>Project 1. Customer Churn - Bank Business</h1>
The purpose of this project is identify customers that are likely to leave the bank, the business can then think of strategies on how to retain these customer. 

One way can be to segment these customer (an exercise for another time), and offer to them personalised marketing service, discounts etc. 

The key 4 main variables that predicted churn. 

-	Age, more than 50% of the customers aged between 51-60 were predicted to churn or leave the bank.

-	Estimated Salary, higher salary indicated higher portion of customers churning ( I would think the higher the salary the less likely a customer would shop around and there for leave a bank, unless the bank does provide great product for high income customer, perhaps they demand more )
  
-	Credit Score, low credit score has a higher customer churn, perhaps these customers are shopping around for credit / credit cards.
  
-	Bank Balance, higher balance indicates higher customer churn, could be a similar reason for estimated salary.
  
Tools Used:
I have used Python in Jupiter notebooks, pandas library to import and transform that dataset for analysis. Random Forest library or algorithm to predict the likelihood of a customer leaving.
Power BI to visualize the predicted output.

Resources and Inspiration of the project: https://www.youtube.com/watch?v=X4IRceUvh_E
<br />

<h2>Dashboard:</h2>
<p align="center">
<img src="https://i.postimg.cc/zXJxp6V6/Customer-Churn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



<h1>Project 2. Return-to-Work Analysis - Worksafe</h1>

<h3>Purpose:</h3>

By combining Return-to-work Analysis, A/B Testing, and Industry Analysis, WorkSafe can:

✅ Identify high-risk workers early.

✅ Improve return-to-work programs for different worker groups.

✅ Optimize financial efficiency by funding effective interventions.

✅ Reduce long-term claims and get injured workers job-ready faster.

<h4>Overview of Return-to-work Analysis:</h4>

This analysis evaluates the key factors influencing return-to-work timelines among employees who have sustained injuries. By identifying significant predictors, we provide actionable recommendations to improve recovery outcomes and workforce efficiency.

<h4>Key Findings:</h4>

1.	Age, Mental Health, Gender, Manufacturing Work, and Injury Severity significantly affect return-to-work time.
   
2.	Moderate and severe injuries have the most significant impact, dramatically delaying return.
   
3.	Mental health improvements increase return speed.
   
4.	Males and manufacturing workers return slower than their counterparts


<h4>Detailed Findings:</h4>

A high concordance 0.9 (>0.7) suggests a strong relationship between the predictors and return time.

1.	Injury Severity is the Strongest Predictor:

o	Severe injuries drastically extend recovery time (HR = 0.00), indicating extremely low return-to-work rates.

o	Moderate injuries also significantly delay return (HR = 0.02).

2.	Mental Health Positively Impacts Recovery:
   
o	Employees with better mental health scores return to work faster (HR = 1.30).

3.	Older Employees Take Longer to Return:
   
o	Higher age correlates with slower return-to-work timelines (HR = 0.95).

4.	Males Return More Slowly than Females:
   
o	Male employees have a 15% lower likelihood of returning sooner (HR = 0.85).

5.	Manufacturing Workers Experience Longer Delays:
    
o	Employees in manufacturing industries return more slowly (HR = 0.79).

6.	Industry Sectors Have Minimal Impact:
    
o	Education, Healthcare, and Retail do not significantly affect return-to-work timelines.


<h4>Possible Actions:</h4>

1.	Invest in Rehabilitation Programs for severe injuries and offer early intervention for moderate injuries to minimize long-term absence.
   
2.	Expand Mental Health Support and stress management training to boost recovery and return-to-work outcomes.
   
3.	Implement Flexible Plans for Older Employees, such as progressive schedules and ergonomic adjustments for faster recovery.
   
4.	Address Manufacturing Industry Issues by enhancing safety measures and offering specialized return programs for physically demanding roles.
   
5.	Optimize Gender-Specific Strategies to address delays for male employees, tailoring support structures for improved outcomes.
   
6.	Promote Workplace Mental Health through targeted initiatives that improve recovery and return speed for all employees.


<h4>To further enrich the insights, we can include in the dataset the following factors:</h4>

1.	Include Recovery Programs in the dataset to measure their individual impact of (e.g., physiotherapy, mental health support).
   
2.	Add Job Role Differences (e.g., desk-based vs. physical roles).
   
3.	Separate Manufacturing from Other Manual Labor (e.g., construction, logistics).


<h4>Conclusion: </h4>

By addressing injury severity, mental health, aging workforce needs, and industry-specific challenges, the company can accelerate return-to-work timelines, reduce long-term absences, and enhance overall workforce productivity. Implementing these strategies will drive both financial and operational benefits, ensuring sustainable workforce management.

<h4>Model fit reasoning:</h4>

The Cox Proportional Hazards Model (Cox PH) is well-suited for this analysis because of its ability to handle time-to-event data while making minimal assumptions about the underlying survival distribution.

<h4>Tools Used:</h4>
I have used Python in Jupiter notebooks, pandas library to import and transform that dataset for analysis. Cox Proportional Hazards Model to predict what factors matter the most when it comes to the speed of retruning to work.

<br />

<h2>Dataset:</h2>
<p align="center">
<img src="https://i.postimg.cc/bYM1DBLS/worksafe-dataset.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  
<h2>Analysis:</h2>
<p align="center">
<img src="https://i.postimg.cc/Hk0MNsmb/worksafe-analysis.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
