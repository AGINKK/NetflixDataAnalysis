# Prompt Engineering Log

## Project
AI-Powered Netflix Movies and TV Shows Data Analysis and Reporting

## Experiment 1: Dataset Understanding

**Objective:** Understand the dataset structure and column meanings.

**Prompt used:**
"Act as a beginner-friendly data analyst. Explain the columns in my Netflix dataset, identify their data types, and suggest useful analytical questions. Do not invent statistics."

**AI response summary:**
[Record the actual response you received.]

**Verification:**
Compared the explanation with the output of `df.info()` and `df.head()`.

## Experiment 2: Data Quality

**Objective:** Identify possible data-quality issues.

**Prompt used:**
"Analyze the data-quality summary I provide. Identify missing values, possible duplicates, inconsistent values, and appropriate cleaning strategies. Do not modify or delete records automatically."

**AI response summary:**
[Record the actual response you received.]

**Verification:**
Compared the suggested checks with Pandas missing-value and duplicate counts.

## Experiment 3: Data Analysis

**Objective:** Analyze Netflix content categories.

**Prompt used:**
"Using the verified statistics I provide, explain the distribution of movies and TV shows and identify the most frequent genre labels. Do not invent numbers or interpret genre counts as viewing popularity."

**AI response summary:**
[Record the actual response you received.]

**Verification:**
Compared the reported numbers with the results calculated by Pandas.

## Experiment 4: Report Generation

**Objective:** Generate a clear and reliable analytical report.

**Prompt used:**
"Organize my verified dataset statistics, cleaning results, charts, and limitations into a professional data analysis report. Clearly distinguish measured facts from interpretations."

**AI response summary:**
[Record the actual response you received.]

**Verification:**
Checked the report against the actual dataset and generated charts.

## Conclusion

Prompt engineering helped structure AI requests, clarify requirements, generate code suggestions, and organize analytical findings. Python and Pandas performed the calculations, and verification checks helped assess the reliability of the results.