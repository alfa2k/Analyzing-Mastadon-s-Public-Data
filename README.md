# Social Media Data Analysis on Mastodon

This project explores the social network dynamics of Mastodon, a decentralized social media platform. By employing network analysis techniques, the aim is to understand user interaction, community dynamics, and information flow within the network. The analysis covers various network measures such as Degree Distribution, PageRank, Betweenness Centrality, and Clustering Coefficient, providing insights into the structure and behavior of Mastodon's user network.

### Data Collection and Analysis Tools

- **Mastodon.py**: Python wrapper for Mastodon API
- **NetworkX**: For constructing and analyzing the network graph
- **Matplotlib** and **PyVis**: For data visualization

## Network Measures Explored

- **Degree Distribution**: Analyzes user connectivity within the network.
- **PageRank**: Identifies influential network members.
- **Betweenness Centrality**: Highlights users critical for information flow.
- **Clustering Coefficient & Community Detection**: Examines group formations and their cohesiveness.

## How to Run

1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Run the data collection script:
   ```sh
   python data_collection.py
   ```
3. Execute the analysis notebook:
   ```sh
   jupyter notebook analysis.ipynb
   ```

## Acknowledgments

- Mastodon community for providing an open and decentralized platform for social interactions.
- NetworkX, Matplotlib, and PyVis libraries for enabling network analysis and visualization.

## [Link to Interactive Graph Webpage](https://itsfahmed.github.io/Online-Social-Network-Analysis/index.html)

---
