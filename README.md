**Trump Social Network Analysis (SNA)**

This project analyzes the social network of Donald J. Trump using advanced Social Network Analysis (SNA) techniques. It explores how individuals are connected, identifies key influencers, and uncovers hidden community structures within the network using centrality metrics and community detection algorithms.

**🚀 Project Overview**

The network is constructed using node and edge data representing Trump’s social and political connections. Using Python and NetworkX, various metrics and algorithms are applied to better understand influence patterns, structural relationships, and community clusters.

**🧠 Key Features**

Centrality Metrics

Degree Centrality

Betweenness Centrality

Closeness Centrality

Eigenvector Centrality


**Community Detection Algorithms**

Louvain Method

Leiden Algorithm

Girvan–Newman Algorithm


**Additional Analysis**

Ego network visualization

Network structure & modularity

Degree assortativity

Bridges & cluster formation


📊** Results Summary**

303 nodes and 366 edges in the full network

Clear hub-and-spoke structure, with Donald Trump as the central hub

32 distinct communities detected

High modularity score (≈ 0.614) → strong community separation

Negative assortativity (–0.362) → high-degree nodes connect to low-degree nodes

Ego networks reveal direct influence clusters (Trump, Jared Kushner, Mike Pence)

**📁 Repository Structure**
/notebook         → Jupyter notebook (.ipynb)
/presentation     → PPT slides
/images           → Visualizations, ego networks, dashboard images, poster
/data             → Nodes and edges CSV files
/results          → Centrality results, community outputs
README.md         → Project documentation

**🛠️ Technologies Used**

Python

NetworkX

Matplotlib

Louvain & Leiden community libraries

Power BI (Dashboards)

Jupyter Notebook

**📷 Visual Outputs Included**

Full network graph

Centrality histograms


**📌 How to Run the Notebook**

Clone the repository

**Install dependencies:**

pip install networkx matplotlib numpy

**Open the notebook:**
jupyter notebook trump_code.ipynb


Run all cells to generate graphs, centrality scores, and communities
Ego networks (Trump, Kushner, Pence)

Community detection plots
