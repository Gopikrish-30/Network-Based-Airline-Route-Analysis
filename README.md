# ✈️ Airline Route Network Analysis using Graph Theory

This project analyzes airline routes using graph theory to uncover insights into connectivity, efficiency, and hub importance. By treating airports as nodes and routes as weighted edges (based on distance), this study applies centrality measures and pathfinding algorithms to better understand and optimize airline operations.

## 📁 Project Structure

- `airline.csv` - Raw dataset containing airport and route details
- `graphh.ipynb` - Jupyter notebook for graph construction, analysis, and visualization
- `Graph Case Study.pptx` - Presentation summarizing the methodology and key findings
- `final_report.pdf` - Full analytical report with insights and recommendations

## 🔍 Key Features

- Data preprocessing for graph modeling
- Construction of a weighted graph (airports as nodes, routes as edges)
- Computation of shortest paths between airports
- Centrality analysis (degree, closeness, betweenness, eigenvector) to identify critical hubs
- Insights into route optimization and airline efficiency

## 🧠 Technologies Used

- Python
- NetworkX
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

## 📊 Centrality Measures Used

- **Degree Centrality** – Identifies highly connected airports
- **Closeness Centrality** – Highlights airports with quick access to others
- **Betweenness Centrality** – Reveals critical transfer hubs
- **Eigenvector Centrality** – Spots influential nodes based on their connections

## 🎯 Outcomes

This analysis helps:
- Identify key airports critical to global connectivity
- Reveal route inefficiencies and potential optimizations
- Support airline decision-making and enhance passenger experience

## 📌 Usage

Clone the repo and run the notebook:

```bash
git clone https://github.com/your-username/airline-centrality-analysis.git
cd airline-centrality-analysis
jupyter notebook:  airline_route_analysis.ipynb
