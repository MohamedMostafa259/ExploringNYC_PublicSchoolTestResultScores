# ExploringNYC_PublicSchoolTestResultScores

This project analyzes SAT test results of NYC public schools using data on average math, reading, and writing scores. It aims to identify top-performing schools, explore which boroughs have the highest variability in SAT scores, and highlight schools with exceptional math performance.

![New York City schoolbus](https://images.unsplash.com/photo-1550523049-a61d0deec4a4?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwcm9maWxlLXBhZ2V8MTAwfHx8ZW58MHx8fHx8)

Photo by [Jannis Lucas](https://unsplash.com/@jannis_lucas) on [Unsplash](https://unsplash.com)_

## Motivation

Every year, American high school students take SATs, standardized tests designed to measure literacy, numeracy, and writing skills. These tests, with sections for reading, math, and writing, each scoring up to **800 points**, are crucial for student admissions. Analyzing school performance based on SAT scores is important for stakeholders like policymakers, researchers, and parents to make informed decisions about educational institutions.

## The Data

The dataset used in this analysis is provided by DataCamp and includes information on NYC public schools' SAT performance:

### `schools.csv`

| Column                | Description               |
|-----------------------|---------------------------|
| `school_name`         | Name of the school        |
| `borough`             | Borough of the school     |
| `building_code`       | Building code             |
| `average_math`        | Average math score        |
| `average_reading`     | Average reading score     |
| `average_writing`     | Average writing score     |
| `percent_tested`      | Percentage of students tested |

# Analysis Questions

-   Which NYC schools have the best math results?

    -   Schools with math results at least 80% of the maximum possible score of 800.

-   What are the top 10 performing schools based on combined SAT scores?

-   Which single borough has the largest standard deviation in combined SAT scores?

# Analysis Results

###   Best Math Results

![Best Math Results](https://github.com/MohamedMostafa259/ExploringNYC_PublicSchoolTestResultScores/blob/main/visualizations/Schools%20with%20Best%20Math%20Results.png)

<br>

---

<br>

### Top 10 Performing Schools

![Ranked schools based on the combined SAT scores from math, reading, and writing sections.](https://github.com/MohamedMostafa259/ExploringNYC_PublicSchoolTestResultScores/blob/main/visualizations/Top%2010%20Performing%20Schools.png)

<br>

---

<br>

### Borough with Largest Standard Deviation

![Determined which borough has the highest standard deviation in the combined SAT scores.](https://github.com/MohamedMostafa259/ExploringNYC_PublicSchoolTestResultScores/blob/main/visualizations/Borough%20with%20Largest%20Standard%20Deviation.png)