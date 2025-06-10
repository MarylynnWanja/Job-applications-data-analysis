# Job applications data analysis
Analyzed job application data using spreadsheets to answer key business questions.
This project is part of the Google Data Analytics course. I used a spreadsheet (Google Sheets) to analyze a year's worth of job application data for a recruiting agency. The goal was to summarize application trends and improve the agency’s online application process.

## 🔧 Tools Used

- Google Sheets
- Functions: `SUM`, `AVERAGE`, `MAX`, `MIN`, `TEXT`, `SORT`

## 📊 Business Questions Answered

1. What was the total number of applications received each month?
2. What was the total number of applications received in the year?
3. In which months were the lowest and highest applications received?
4. What was the average number of applications per month?

## 📈 Process

- Cleaned the raw data to ensure all dates were correctly formatted
- Used the `TEXT` function to extract month names from dates
- Applied functions to summarize data (e.g., monthly totals, averages)
- Created a custom data table for monthly application summary
- Sorted data to identify highest and lowest months

## 📌 Key Insights

- The month with the highest number of applications: **July**
- The month with the lowest number of applications: **February**
- Total applications in the year: **32596**
- Average applications per month: **2716.33**

## 📝 Summary Table Screenshot

![Screenshot (29)](https://github.com/user-attachments/assets/5f4fd4a3-5d2c-421c-a8aa-32a4fbef9fa4)


## 📂 Files

- [Download the spreadsheet](https://docs.google.com/spreadsheets/d/1W1V0LKkuUjufcLNUnF78qfhCZFwcV6aAhK8Ugj8b6FA/edit?usp=sharing)


## 🚧 Challenges I Faced

- At first, all the months showed “January” because I applied "January" instead of "mmmm" in the `TEXT(B2, "mmmm")` formula to all rows. I fixed this by replacing "January" with "mmmm".


## 🧠 What I Learned

- Extracting months from dates using `TEXT(B2, "mmmm")`
- Using spreadsheet functions to summarize data
- Creating a custom summary table


## 🔚 Final Thoughts

This project helped me practice real-world spreadsheet analysis using basic functions like SUM, AVERAGE, MAX, MIN, and TEXT. I gained confidence in cleaning data, extracting information from dates, and summarizing results in a readable format. 
If I were to continue this project, I would visualize the data using charts to make the monthly trends easier to understand and share with stakeholders.
