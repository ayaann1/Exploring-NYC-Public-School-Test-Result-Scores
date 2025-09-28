🏫 NYC Public Schools – SAT Performance Analysis
📌 Overview

This project analyzes New York City public school SAT scores to uncover insights about school performance.
The SAT is a nationwide test in the United States with three sections:

Math

Reading

Writing
Each section has a maximum score of 800.

The analysis answers three key questions:

Which NYC schools have the best math results?

Which are the top 10 performing schools based on total SAT scores (Math + Reading + Writing)?

Which borough shows the largest variation (standard deviation) in combined SAT scores?

🗂️ Dataset

File: schools.csv

Columns:

school_name – Name of the school

borough – NYC borough where the school is located

average_math – Average math score (out of 800)

average_reading – Average reading score (out of 800)

average_writing – Average writing score (out of 800)

⚙️ Steps Performed

Best Math Schools

Selected schools with an average math score greater than 640 (80% of the maximum 800).

Sorted them by highest math score to find the strongest performers.

Top 10 Schools by Total SAT

Calculated a total_SAT score (math + reading + writing).

Found the top 10 schools with the highest combined SAT scores.

Borough with Largest Variation

Grouped schools by borough.

Calculated the standard deviation of total SAT scores for each borough.

Identified the borough with the largest score variation, and also recorded:

Number of schools

Average total SAT score

Standard deviation (std)

🧮 Key Results (Sample Output)
Question	Answer
Best Math Schools	DataFrame best_math_schools (schools scoring >640 in math)
Top 10 Schools by Total SAT	DataFrame top_10_schools
Largest Borough Variation	DataFrame largest_std_dev containing:
• borough
• num_schools
• average_SAT
• std_SAT

(All numeric values are rounded to two decimal places.)

🛠️ Tools Used

Python – programming language

pandas – for data cleaning and analysis

📂 Repository Contents

schools.csv – Dataset of NYC public school SAT scores.

notebook.ipynb – Jupyter Notebook with step-by-step analysis.

README.md – This explanation file.
