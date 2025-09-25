# Applied Econometrics and Data Science with R

## Welcome!

Welcome to the course Applied Econometrics and Data Science with R! We’re excited to spend the next weeks with you and the great statistical programming language R. At the end of the course, you will be able to…

* **Work with data in R:** Clean, organize, and analyze large datasets to answer real economic research questions.

* **Write clear and professional code:** Produce easy-to-read R code that creates high-quality tables, graphs, and results.

* **Make and explain data decisions:** Explain your choices when processing data and compare different methods (including basic machine learning tools) using objective measures.

## Course design and prerequisites
The course consists of two main elements: Introduction to working with R and introduction to Machine learning. We will cover both topics in a very hands-on way, by giving you a basic understanding and then applying the concepts in class. We thus ask you to participate in class and work on your projects during the semester. Please also work on the pre-course task until October 12, 12pm latest that helps us understand the experiences and expectations of all of you. You find the link here.

To start smoothly and solve potential technical problems early, please make sure to **install all required software before the first session**.

## Installation checklist
Please install the following:

* [R (latest version)](https://cran.r-project.org)
* [RStudio Desktop](https://posit.co/download/rstudio-desktop/)
* [GitHub Desktop](https://github.com/apps/desktop)
* [Create a GitHub account](https://github.com)
* Join the GitHub classroom/repository via this link: …
* 
The final version of the code and other course materials will be uploaded to both Moodle and GitHub.

## Structure
For this semester’s course, we will meet each week on Wednesdays, 12:15–13:45 in 3.06.S27.

In each session, you will get input into some aspects of applied econometrics and data science and apply them right away. One of the instructors will code live in class, while the other is available for technical assistance.

Please bring your laptop to the seminars and have a look at the content before each session.

## Schedule 

Here, you will find the detailed course content:

```{r, echo=FALSE}
library(knitr)
library(kableExtra)

# Create the data
dates <- c("15th October 2025", 
           "22nd October 2025", 
           "29th October 2025", 
           "5th November 2025", 
           "12th November 2025", 
           "19th November 2025", 
           "26th November 2025", 
           "3rd December 2025",
           "10th December 2025",
           "17th December 2025",
           "7th January 2026",
           "14th January 2026",
           "21st January 2026",
           "28th January 2026",
           "4th February 2026")

topics <- c("Introduction to R, R-Markdown and Github",
            "Data Wrangling and the `tidyverse`",
            "Data Wrangling and the `tidyverse`",
            "Supervised Machine Learning",
            "Supervised Machine Learning",
            "Automations in R",
            "Automations in R",
            "Q&A and coding practicing",
            "The `ggplot2` package",
            "The `ggplot2` package",
            # "Spatial economics and maps",
            "Q&A and coding practicing",
            "Progress talks & how to present your results in a poster",
            # "How to present your results in a poster",
            "Q&A and coding practicing",
            "Final Poster Presentations??", 
            "")

instructor <- c("Sophie & Felix", 
                "Felix",
                "Felix", 
                "Sophie",
                "Sophie",
                "Felix",
                "Felix",
                "Sophie & Felix",
                "Sophie",
                "Sophie",
                "Sophie & Felix",
                "Felix",
                # "Felix",
                "Sophie & Felix",
                "Sophie & Felix", 
                "")

notes <- c("Course registration",
          "Upload of Topics & Team Assignment \n Final Course Registration on PULS until November XYth at the lastest",
          "Assignment of Topics",
           rep("", 5),
          "Submission of Midterm Code until December 15, 12 pm!",
          rep("", 6)
)

# Combine into a data frame
schedule <- data.frame(Date = dates, Topic = topics, Instructor = instructor, Notes = notes)

# Create the table
kable(schedule, align = "l") %>%
  kable_styling(bootstrap_options = c("striped", "hover", "condensed"))
```

## Instructors 

* Felix Degenhardt (email)
* Sophie Wagner (email)

