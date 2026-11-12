# Markdown Buddy - R Data Analysis Project

## Overview
This project is part of my BDA400 Data Science Tools and Techniques course at CDI College. The purpose of this project is to demonstrate how R can be used to analyze student grades using a synthetic dataset. The project will organize student grades, calculate average scores, and summarize the results. It also demonstrates how Markdown and R Markdown can be used to create clear and professional documentation.
## Project Structure
The project will contain the following files:

- `README.md` - Explains the project, installation, and usage.
- `student_grades.R` - R script for analyzing synthetic student grades.
- `Student_Grades_Documentation.Rmd` - R Markdown documentation explaining the script.
- `Reflection.md` - Reflection on using AI to create documentation.
- `AI_Prompts_Appendix.md` - Records AI prompts and key responses.

## Installation
To use this project, follow these steps:

1. Install R from https://cran.r-project.org/.
2. Install RStudio Desktop from https://posit.co/download/rstudio-desktop/ or use Posit Cloud.
3. Download the project files from this GitHub repository.
4. Open `student_grades.R` in RStudio.
5. Run the script to analyze the synthetic student grades.

This basic project uses base R and does not require additional R packages.
## Example Code
The following example demonstrates how R can store synthetic student grades and calculate their average.

```r
# Synthetic student grades
grades <- c(75, 80, 85, 90, 95)

# Calculate the average grade
average_grade <- mean(grades)

# Display the result
print(average_grade)
```
## Expected Outputs
When the R script is executed, it should:

- Store five synthetic student grades.
- Calculate the average grade using the `mean()` function.
- Display the calculated average in the R console.
- Help demonstrate basic data analysis using R.


## License

 This project was created for educational purposes as part of BDA400 at CDI College. No open-source license has been assigned. All student data used in this project is synthetic and does not contain personal information.

## AI Assistance Disclosure
AI Tool: ChatGPT (OpenAI, GPT-6)
Date: November 12, 2026

I used ChatGPT to help plan the README structure, draft descriptions, suggest Markdown formatting, and provide an example of R code. I reviewed the suggestions and made changes to the formatting in GitHub.

Main prompts included:
- Explain what sections a good GitHub README for an R data analysis project should include.
- Help me create a README for a Student Grades Analysis project.
- Suggest Markdown headings, installation instructions, and example code.

Verification: I previewed the Markdown headings in GitHub. The complete README and R code still need to be tested and verified before final submission.

I am responsible for checking the accuracy and originality of my final work.
