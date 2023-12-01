# Air Quality Analysis and Prediction in Tamil Nadu

Skill Up Applied Data Science Course Project, Project 9

**Project Title:** Air Q Assessment TN

**Problem Statement:** The objective of this project is to analyze and visualize air quality data from various monitoring stations in Tamil Nadu. The dataset contains measurements of Sulfur Dioxide (SO2), Nitrogen Dioxide (NO2), and Respirable Suspended Particulate Matter/Particulate Matter 10 (RSPM/PM10) levels in different cities, towns, villages, and areas. The project aims to gain insights into the air pollution trends, identify areas with high pollution levels, and create a predictive model to estimate RSPM/PM10 levels based on SO2 and NO2 levels.

**Dataset Link:** https://tn.data.gov.in/resource/location-wise-daily-ambient-air-quality-tamil-nadu-year-2014 


## Project Files
**Data set** : [tn-aq-2014.csv](https://github.com/nonkloq/skillup-ADS/blob/main/tn-aq-2014.csv)

**Project Notebook:** [aq-analysis.ipynb](https://github.com/nonkloq/skillup-ADS/blob/main/aq-analysis.ipynb)

**Geospatial Heatmap Visualization:** [geo_spatial_aq_heatmap.html](https://github.com/nonkloq/skillup-ADS/blob/main/geo_spatial_aq_heatmap.html)

**Plots by Area, to analyse (no code):** [plots.pdf](https://github.com/nonkloq/skillup-ADS/blob/main/plots.pdf) 


**Phase Wise Project Submission Documents**: [submission_files](https://github.com/nonkloq/skillup-ADS/blob/main/submission_files)
- Phase1: Problem defenition and design thinking
- Phase2: Innovation (Filler)
- Phase3: Development Part 1 (Data Preprocess)
- Phase4: Development Part 2 (Analysis, Visualization and Model)
- Phase5: Project Documentation & Submission



## Replicating the Results

To replicate the results follow these steps:

1. **Clone the Repository:** Clone this project repository to your local machine using the following command:
    ```bash
    git clone https://github.com/nonkloq/skillup-ADS.git
    ```

2. **Set Up the Environment:** Ensure you have the required Python environment set up (Python >= 3.10). You can create a virtual environment and install the necessary dependencies by running:
    
    For Linux & macOS:
    ```bash
    python -m venv tmpenv
    source tmpenv/bin/activate
    pip install -r requirements.txt
    ```
    For Windows:
    ```
    python -m venv tmpenv
    .\tmpenv\Scripts\activate
    pip install -r requirements.txt
    ```

3. **Run all and Explore The IPython Notebook:** Navigate to the project directory 'skillup-ADS' and launch the Jupyter Notebook to explore the analysis and predictive model. Use the following command: 
    ```bash
    cd skillup-ADS
    python -m jupyter notebook aq-analysis.ipynb
    ```
    Ensure to select the appropriate kernel 'Python (Ipykernel)' before running the cells. Click on the 'Run' tab and select 'Run All Cells' within the notebook '[aq-analysis.ipynb](https://github.com/nonkloq/skillup-ADS/blob/main/aq-analysis.ipynb)' to reproduce the data analysis, visualizations, and predictive models. Make sure to follow the instructions and comments within the notebook for guidance.

By following these steps, you can replicate this air quality analysis and prediction results.

