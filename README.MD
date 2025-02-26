# 🏞️ Wildlife Observations & Conservation Status Analysis  

## 📌 Project Overview  
This project analyzes wildlife observations across various national parks, focusing on species conservation status and endangerment risk. Using statistical tests and data visualization, we explore patterns in species distribution, observation frequencies, and the relationship between taxonomic categories and conservation risks.  

## 📂 Dataset Information  
The analysis is based on two datasets:  

- **`observations.csv`**  
  - `scientific_name`: Scientific name of the observed species.  
  - `park_name`: Name of the national park where observations were recorded.  
  - `observations`: Number of recorded observations in the last week.  

- **`species_info.csv`**  
  - `category`: Taxonomic category of the species (e.g., Mammal, Bird).  
  - `scientific_name`: Scientific name of the species.  
  - `common_name`: Common name of the species.  
  - `conservation_status`: Status of the species (e.g., Species of Concern, Endangered).  

Both **observations.csv** and **species_info.csv** were provided by [Codecademy.com](https://www.codecademy.com).
Note: The data for this project is inspired by real data, but is **mostly fictional**.

## 📊 Goals of the Analysis  
1. **Summarize Observations by Park** – Identify which parks have the highest and lowest wildlife activity.  
2. **Analyze Conservation Status Distribution** – Examine how species are distributed across different conservation status categories.  
3. **Identify Risk of Endangerment** – Determine whether certain taxonomic groups are more prone to being endangered.  
4. **Find the Most and Least Observed Species** – Identify species with the highest and lowest observation counts.  
5. **Compare Observations of Endangered vs. Non-Endangered Species** – Test whether endangered species are observed less frequently than non-endangered ones.  

## 🛠️ Methodology  
- **Data Cleaning & Exploration**: Handling missing values, duplicates, and merging datasets for comprehensive analysis.  
- **Statistical Tests**:  
  - **Chi-Squared Test** to examine the relationship between species category and endangerment risk.  
- **Data Visualization**:  
  - Bar charts to illustrate species distribution.  
  - Heatmaps to highlight taxonomic categories most at risk.  

## 🔍 Key Findings  
- **Yellowstone National Park** has the highest wildlife activity, while **Great Smoky Mountains National Park** has the lowest.  
- The majority of at-risk species fall under the **species of concern** category, with birds and mammals being the most affected.  
- Statistical analysis confirms a strong association between taxonomic category and the likelihood of endangerment (**p-value ≈ 0**).  
- **Vascular plants** are the most observed species (2.5 million observations), while **amphibians** are the least observed (44,600).  
- Endangered species are observed significantly less frequently than non-endangered species, as confirmed by statistical tests.  

