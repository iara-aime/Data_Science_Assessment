README file

Analysing snakebite envenoming in Brazil: An overview of risk areas

Overview
This script analyses the reported snakebite cases in Brazil from 2000 to 2022. The analysis explores trends in snakebite frequency over time, across regions, and across different states, providing insights into spatial patterns of snakebites in the country. The script also performs a Kruskal-Wallis Test and Dunn's test for statistical significance and uses clustering techniques to identify areas with high snakebite concentrations.

Requirements
Install Jupyter Notebook if not already installed:
pip install notebook
Launch Jupyter Notebook by running:
jupyter notebook
To run this script, the following libraries must be installed:
•	pandas
•	numpy
•	matplotlib
•	seaborn
•	geopandas
•	folium
•	plotly
•	scikit-posthocs
The required libraries can be installed using the following command:
pip install pandas numpy matplotlib seaborn geopandas folium plotly scikit-posthocs

How to Run
1.	Ensure that all required libraries are installed by running the installation command above. 
2.	Download the repository to your local machine and make sure that all files are in the same directory.
3.	Open the notebook in a Jupyter environment (e.g., Jupyter Notebook or JupyterLab).
4.	Open the .ipynb file in the browser interface that appears.
5.	To carry out the analysis, run the cells sequentially by clicking on each cell and pressing Shift + Enter or using the "Run" button in the Jupyter toolbar.

Outputs
The script generates the following visualizations and statistical analyses:
•	A time-series plot showing snakebites over the years.
•	A pie chart displaying snakebite distribution across brazilian regions.
•	Results from the Kruskal-Wallis Test and Dunn’s Test for pairwise region comparisons.
•	A map showing snakebite frequency by state in Brazil.
•	A heatmap showing the spatial distribution of snakebites.
•	A KMeans-based clustering analysis to identify areas of high snakebite concentration.

Author
Iara Aime Cardoso – University of Bristol


