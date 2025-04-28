# Gendered Differences of Stress During the 2008 Economic Recession

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to examine how stress experiences and coping mechanisms differed by gender during the 2008 economic crisis, and how these differences were linked to psychological and physical health outcomes. By analyzing survey responses from the American Psychological Association's "Stress in America" dataset, we aim to uncover gender-specific stress patterns to inform better-targeted mental health interventions in future economic downturns.


### Methods Used
* Inferential Statistics (t-tests)
* Data Visualization
  * Bar graphs
  * Box plots
  * Time series analysis

### Technologies
* R (RStudio)
* RMarkdown
* ggplot2 (Visualization)
* dplyr (Data Wrangling)
* tidyr (Data Cleaning)

## Project Description
We used the 2008 "Stress in America" survey from the American Psychological Association, consisting of 3,760 responses, with a focus on 1,568 adult responses.

- **Research Questions:**
  - How did stress experiences and coping mechanisms differ by gender during the 2008 economic crisis?
  - How were these differences linked to psychological and physical health outcomes?

- **Analysis and Visualization Techniques:**
  - Performed exploratory data analysis (EDA) to investigate gender differences in stress levels, stress sources, and coping mechanisms during the 2008 economic recession
  - Analyzed stress trends across 2007-2009 using APA's nationally representative Stress in America survey data
  - Conducted statistical significance testing with p-value analysis to confirm meaningful gender differences in reported stress levels (p<0.001)
  - Compared stress sources between genders, identifying money, work, the economy, and job stability as primary stressors
  - Examined gender-specific coping strategy preferences, finding that women favored emotional/communal approaches (social support, mindfulness, religion) while men preferred autonomous strategies (physical activity, withdrawal)
- Visualization:
  - Created bar charts comparing mean stress levels between males (5.8) and females (6.5) with standard deviation indicators to visualize the statistical significance (p<0.001)
  - Developed pie charts or proportional visualizations to display the gender distribution within the dataset sample across the three years (2007-2009)
  - Designed time series visualizations tracking stress trends over the 2007-2009 period, highlighting the progression through the economic recession
  - Used comparative bar charts to illustrate the prevalence of different stress sources (money, work, economy, job stability) by gender
  - Implemented grouped or stacked bar charts to compare coping mechanism preferences between genders, visually demonstrating how women favored emotional/communal approaches while men preferred autonomous strategies
  - Created visual hierarchies of stress sources from most to least common (with money at the top and personal health at the bottom)

- **Challenges:**
  - Handling a large number of categorical coping mechanisms (smoking, drinking) and stress source variables (money, work, economy, job stability).
  - Ensuring correct interpretation of survey weights and generalizability.
    - Standardizing "male" and "female" values based on uneven numbers of survey participants in each category.
  - Handeling missing values within survey data.

- **Potential Next Steps:**
  - Expand analysis to track changes across multiple years outside of 2007-2009.
  - Explore interactions between gender, age, marital status, and other demographic factors.
  - Apply more sophisticated modeling (e.g., random forests or boosting) for predictive analysis.

## Getting Started

1. **Clone this repository**  
   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/angelinachen6/qtm302class.git
   cd qtm302class
   ```

2. **Open the RStudio Project**  
   Open the `qtm302class.Rproj` file in RStudio. This will automatically set your working directory and project environment correctly.

3. **Restore the R Environment**  
   This project uses `renv` for dependency management. Restore all necessary libraries by running:
   ```r
   renv::restore()
   ```
   This will install the specific package versions listed in `renv.lock`.

4. **Access the Exploratory Data Analysis**  
   Open the `EDANotebookFinal.Rmd` file to view the exploratory data analysis. You can run the code chunks or knit the document to HTML or PDF for a complete report.

5. **Data Folder**  
   The `data/` directory should contain any datasets needed for the project.  
   *Note:* The APA "Stress in America" dataset must be downloaded separately from ICPSR ([link](https://doi.org/10.3886/ICPSR37288.v2)).

6. **Session Files**  
   Files like `.RData` and `.Rhistory` are included but are optional. They can be used to recreate previous R sessions if needed.

## Project Structure
```
.
├── data/
│   └── 37288-0003-Data.tsv
├── renv/
│   ├── .gitignore
│   ├── activate.R
│   ├── library/
│   ├── settings.json
│   └── staging/
├── EDANotebookFinal.Rmd
├── qtm302class.Rproj
└── renv.lock
```


## Featured Deliverable
* [Final Slide Deck](https://docs.google.com/presentation/d/1UtZyBbUDP3E7EUyHZbA9DxTydvEjCJLNcWkVNjZLvf4/edit?usp=sharing)



## Contact
* Angelina Chen (ID: ACCHEN5, angelina.chen@emory.edu, Department of Quantitative Theory and Methods, Emory University)
* Cassie Yu (ID: CYYU123, cassie.yu@emory.edu, Department of Quantitative Theory and Methods, Emory University)
* Yoonseo Bae
