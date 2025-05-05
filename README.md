# Job Skills Trend Analysis Project

---

## Overview

This repository contains the final group project for the AI/ML Bootcamp, focused on analyzing in-demand job skills across industries using Natural Language Processing (NLP) techniques. Each team member explored a unique angle of the job market using real-world job postings and skill datasets, culminating in a collaborative, insight-driven analysis of labor market trends. The goal was to build predictive and analytical pipelines that offer both statistical and visual insights into what skills are rising in demand.

---

## Key Tasks

The project is organized into four major components contributed by each team member:

---

### 1. Elliot – Skills to Education Mapping

- Explored the relationship between job skills and corresponding educational programs.
- Mapped skill keywords to relevant university degrees or certifications.
- Used TF-IDF and keyword extraction to relate job descriptions to degree programs.
- Final output: a function that recommends educational paths based on desired job skills.

---

### 2. Mehdi – Most In-Demand Job Titles

- Focused on determining the most in-demand job roles.
- Used NLP to extract and count common job titles across datasets.
- Visualized the frequency and growth trend of job categories.
- Helped identify industry sectors with the most hiring activity.

---

### 3. Mike B – Skill Extraction from Resume Data

- Created a prototype model for extracting high-priority skills from resumes and job listings.
- Compared and aligned resume keywords with job requirements using cosine similarity.
- Tested multiple skill clustering approaches.
- Final goal: help job seekers align resumes with job descriptions.

---

### 4. Mike G – Skill Heatmap & Temporal Trends

- Conducted trend analysis across time to determine which skills are growing or fading.
- Used rolling averages and sentiment scoring for specific technology terms.
- Created heatmaps and visual overlays of the highest impact job skills.
- Proposed potential integration into a recommendation engine for career pivot planning.

---

## How to Run

Clone the Repository:  
`git clone https://github.com/<your-org-or-username>/job-skills-trend-analysis.git`  
`cd job-skills-trend-analysis`

1. Set Up the Environment:

   - Ensure Python 3.x is installed.
   - Install required libraries:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
     ```

2. Run the Notebooks:

   - Open each notebook (`MikeG.ipynb`, `Elliot_stuff.ipynb`, etc.) in Jupyter Notebook or VS Code.
   - Execute each cell sequentially to reproduce the analysis and results.
   - Results include text classification, keyword clustering, visualizations, and mapping tables.

---

## Dependencies:

Ensure the following Python libraries are installed:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- nltk  
- scikit-learn  
- wordcloud

Install with:  
`pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud`

---

### Results

The final project successfully:

- Mapped emerging job skills to degrees and education programs.
- Identified top job roles by frequency and title clustering.
- Extracted keywords from resumes and compared them to job postings.
- Visualized growing and declining job skills using heatmaps and trend charts.
- Provided data-backed recommendations for job seekers and educators.

---

## License

This project is licensed under the MIT License.
