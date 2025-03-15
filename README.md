<div align="center">
  <h1>StudyNetwork Analytics</h1>
</div>

---

## Description
StudyNetwork Analytics explores how student study relationships influence academic performance. Using Python, it analyzes 187 students’ exam scores and study networks across three exams, leveraging Pandas for data processing, NetworkX for network analysis, and Plotly for visualization to uncover patterns like homophily and performance correlations.

---

## Features
- Generates synthetic student data (exam scores, labs, gender) for 187 students.
- Calculates homophily by lab and gender across three exam periods.
- Analyzes probability of same-lab study partnerships.
- Correlates number of study partners with final grades.
- Visualizes study network dynamics with Plotly parallel coordinates.

---

## Tech Stack
- **Python**: Core language for analysis and scripting.
- **Pandas**: Data manipulation and generation.
- **NetworkX**: Social network analysis and homophily calculations.
- **Plotly**: Interactive parallel coordinate visualizations.
- **Matplotlib**: Static plotting support.

---

## Installation
1. Clone the repository: `git clone https://github.com/kamaleshpantra/studynetwork-analytics.git`
2. Navigate to the directory: `cd studynetwork-analytics`
3. Install dependencies: `pip install pandas networkx plotly matplotlib`
4. Open the notebook: `jupyter notebook StudyNetwork_Analytics.ipynb`

---

## Usage
- Run `StudyNetwork_Analytics.ipynb` in Jupyter Notebook or Google Colab.
- Execute cells sequentially to:
  - Generate student data and study networks.
  - Compute homophily by lab and gender.
  - Analyze lab-based study relationships and performance correlations.
  - Visualize results with an interactive Plotly plot.

---

## Screenshots
<img src="data_table.png" alt="Sample Student Data" width="500"/>  
*Sample dataset of 187 students with lab assignments, gender, exam scores, and final grades, generated for analysis.*

<img src="parallel_coordinates.png" alt="Parallel Coordinate Plot" width="500"/>  
*Interactive parallel coordinate plot showing how study partnerships evolve across three exams, colored by Exam 1 scores.*

<img src="homophily_results.png" alt="Homophily Results" width="500"/>  
*Homophily analysis revealing low lab-based similarity (0.08-0.09) and moderate gender-based similarity (0.49-0.51) in study networks.*

<img src="relationship_analysis.png" alt="Relationship Analysis" width="500"/>  
*Analysis showing low probability (0.08-0.09) of same-lab study pairs and weak correlation (0.02-0.06) between study partners and final grades.*

---

## Connect
- [GitHub](https://github.com/kamaleshpantra)
- [Europass Portfolio](http://europa.eu/europass/eportfolio/api/eprofile/shared-profile/kamalesh-pantra/e5d18ee5-da11-4ad2-bb4f-890d59ff8aa6?view=html)  
Questions? Contact me at [kamaleshlmv@gmail.com](mailto:kamaleshlmv@gmail.com).
