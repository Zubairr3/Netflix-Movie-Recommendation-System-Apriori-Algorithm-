Netflix Movie Recommendation System
Overview
This project leverages the Apriori Algorithm to perform Market Basket Analysis on a movie-viewing dataset. By identifying frequent movie co-occurrences, the system generates association rules that predict user preferences and provide movie recommendations.

Methodology
Data Preprocessing: Transformation of raw viewing logs into a transactional format for association mining.

Association Mining: Utilization of the apyori library to extract rules based on Support, Confidence, and Lift metrics.

Visualization: Generation of analytical charts to highlight the top-performing movie associations.

Why Apriori?
Interpretability: Provides clear, rule-based logic for recommendations.

Pattern Discovery: Excels at finding implicit connections in sparse transactional data.

Baseline Utility: Offers a scalable foundation for more complex recommendation engines.

Setup
Clone the repository: git clone https://github.com/your-username/your-repo-name.git

Install requirements: pip install -r requirements.txt

Execution: Open Netflix_Movie_Recommendation.ipynb in your preferred environment (Jupyter/Colab).

Data Source
The dataset used in this project is a benchmark transactional movie viewing dataset, widely utilized in data science education for practicing Market Basket Analysis techniques.





License
Distributed under the MIT License. See LICENSE for more information.
