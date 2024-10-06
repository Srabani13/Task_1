# Virtual Internship @ AtliQ Technologies
 
As I contribute to various projects in this virtual internship, I’ll gain hands-on experience with data analysis tools and techniques, enhancing my skills in a practical, remote setting. This opportunity will also allow me to collaborate cross-functionally, understanding how data drives key business outcomes at AtliQ Technologies.
### WEEK:1 

```

HR Report
Srabani Banerjee,

Sending you these tasks following up on our call.

The HR dataset can be found in the file "attendance_data.csv". Your tasks are divided into two parts: data cleaning and data analysis.

Task 1: Data Cleaning

Check for duplicates in the dataset and remove them.
Standardize the date values to the format YYYY-MM-DD and extract the month name and day type from them.
Remove any extra characters, such as special characters, from the employee ID values. Some IDs may contain a '@' character at the end, which can be cleaned and brought to a common format.
Standardize the capitalization of names. Convert all names to title case, which means capitalizing the first letter of each word.
Map the corresponding values in the status column with the given abbreviations:
Work From Office --> WFO
Work From Home --> WFH
Birthday Leave --> BL
Menstrual Leave --> ML
Paid Leave --> PL
Sick Leave --> SL
Weekly Off --> WO
Task 2: Ad Hoc aka Analysis

What is the total count of distinct employee names within the dataset?
Calculate the work-from-home (WFH %) percentage in the month of May.
Determine which day of the week had the highest attendance percentage in the month of June.
Find out the number of employees who had a WFH percentage greater than 10% in the month of April.
You are free to use any tool of your preference, such as Pandas, Excel, PowerBI, etc., to complete this task.

If you have any follow-up questions on the task, you can ask your seniors here: [discord link]

But they are busy, try to solve it on your own as much as possible.

Good luck with your task!

Best regards,

Hem
Head of Data Analytics | AtliQ Technologies Pvt. Ltd.
Website: www.atliq.com
```
Solution:
Used_Tools : [Pandas|Excel]  
File_Name : [Solution_1](https://github.com/Srabani13/Virtual_Internship/blob/main/VI_Task1_Soln.ipynb)


### Email 2:
```
Data Normalization Task

Introduction
Hi Srabani Banerjee,

Well done with the previous task. I have a new one for you.

Task Description
One of our client projects requires minor support. The dataset is currently in a de-normalized form, and we need your help to transform it into a normalized form.

Task Details
Your task will involve creating proper fact and dimension tables based on the dataset, which can be found in the "fact_order_lines.csv" file.

Input Data
The dataset is currently in a de-normalized form. Please refer to the screenshots provided for a better idea of what the input data looks like.

Output Data
Your goal is to normalize the dataset and present the final output in the form of proper fact and dimension tables. Please refer to the screenshots provided for a better idea of how the final output should be presented:
- Output Data
- Output Data 1
- Output Data 2
```
   ![Table](https://github.com/Srabani13/Virtual_Internship/blob/main/task2_3.png)
```
Deadline
Please complete this task within the next 2 days.

Contact
Best regards,
```
<img src="https://github.com/Srabani13/Virtual_Internship/blob/main/AtliQ.webp" alt="Logo" width="150"/>



Solution:
Used_Tools : [Google Sheet]  
File_Name : [Solution_2](https://docs.google.com/spreadsheets/d/10K8_xgI4ibk9Xhnt-DshKPoKnihRGV4-/edit?usp=sharing&ouid=111744780396337541766&rtpof=true&sd=true)


## WEEK 2
### Email Task 1

```
Variance Analysis Task
Srabani Banerjee,

Here is the detailed explanation of the task.

You need to conduct variance analysis to compare benchmark data (benchmarks.csv) with their current data (fact_orders.csv). The goal of this analysis is to identify and quantify the differences or variations between the two datasets. Specifically, you will be comparing the order quantity and delivery quantity from the fact_orders.csv file with the benchmark data provided in the benchmarks.csv file.

Datasets:
You will be provided with three datasets for this analysis:

fact_orders.csv: Contains columns like order_id, order_placement_date, mmm_yy, customer_id, product_name, order_qty, and delivery_qty.
dim_customers.csv: Contains columns like customer_id, customer_name, and city.
benchmarks.csv: Contains columns like mmm_yy, customer_id, customer_name, city, total_order_quantity, and total_delivery_quantity.
Workflow:
Here is a brief overview of the workflow for the task:

Review the benchmark data and the current data (fact_orders.csv).
Metrics to compare between two files: Order quantity and Delivery quantity.
Calculate the variance (absolute value) between the benchmark data and the current data for the identified metrics.
Calculate the variance (in percentage) between the benchmark data and the current data for the identified metrics.
Provide a complete report of the difference in numbers between the benchmark data and the main data.
Please ensure that you thoroughly analyze the datasets and provide a comprehensive report of the differences in the order quantity and delivered quantity between the benchmark data and the main data.
```

<img src="https://github.com/Srabani13/Virtual_Internship/blob/main/AtliQ.webp" alt="Logo" width="150"/>

Used_Tools : [Google Colab]  
File_Name : [Solution_3](https://colab.research.google.com/drive/1mPuMPLipg0dJqhkVSBtOEUcPc7Bhl19M?usp=sharing)
