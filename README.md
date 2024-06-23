# DataFest 2024 Competition

## Competition Details

**Challenge:** Analyze data from the CourseKata project to provide insights and recommendations to improve the student experience of learning statistics.

## Project Overview

### Team Members
- Ben Trokenheim
- Eric Mass
- Jake Golden
- Lihong Wang
- Michael Thomas

### Data Description
The dataset provided by CourseKata includes interactions students with online interactive textbooks used in several college-level introductory statistics and data science classes across 11 institutions. The data is divided into several files:
- `page_views.csv`: Records of student page accesses.
- `responses.csv`: Student responses to questions.
- `items.csv`: Metadata about the questions.
- `media_views.csv`: Student interactions with videos.
- `checkpoints.csv`: Pulse check surveys and end-of-chapter review summaries.

### Analysis Objectives
1. Identify patterns of student engagement with the CourseKata textbooks.
2. Detect stumbling points and areas of success in the learning process.
3. Provide actionable recommendations to improve the student learning experience.

## Key Findings

### Textbook Features and Structure
- **High Loop Ratio Sections:** Identified chapters with high revisit rates, indicating potential areas where students struggle or find particularly engaging.
  - Examples: 
    - 11.2 – Sampling Distributions of PRE and F
    - 4.2 – Explaining one Variable with Another
    - 12.1 – From Hypothesis Testing to Confidence Intervals
    - 1.5 – Save your Work in R Objects
    - 9.1 – Using a Quantitative Explanatory Variable

### Student Behavior Analysis
- **PageRank Analysis:** Determined the most frequently visited nodes (pages) and the traversal paths between them.
- **Engagement Patterns:** Analyzed the causal effect of pulse check results on end of chapter (EOC) quiz scores.

### Recommendations
1. **Enhance Textbook Connectivity:** Add hyperlinks between commonly travered textbook sections. Students who jumped between different sections more performed better on EOC quizzes.
2. **Targeted Support for Difficult Sections:** Provide additional resources and support for sections identified as stumbling points.
3. **Course Pacing:** Spend more time on particularly difficult chapters which EOC scores and PageRank analysis showed to be more challenging.
