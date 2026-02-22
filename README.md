# NYC 311 Complaints Sankey Diagram

An interactive data visualization that maps the flow of NYC's 311 service complaints from their boroughs of origin through complaint types to the government agencies responsible for handling them.

## Project Overview

This project analyzes **311 service request data from 2020 to the present** (as of February 2026) to reveal patterns in how complaints flow through New York City's government system. Using a Sankey diagram, the visualization makes it easy to see:

- **Which boroughs file the most complaints** (Bronx, Brooklyn, Manhattan, Queens, Staten Island)
- **What types of complaints are most common** (top 10 complaint types)
- **Which city agencies handle different complaint categories**
- **How complaint volume varies across the city**

## Key Features

- **Interactive Sankey Diagram**: Hover over flows to see exact complaint counts
- **Responsive Design**: Works across desktop and tablet screens

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- pandas
- plotly

### Installation

1. Clone this repository or download the files
2. Install dependencies:

```bash
pip install jupyter pandas plotly
```

3. Open the notebook:

```bash
jupyter notebook nyc_311_sankey.ipynb
```

### Data

The analysis uses NYC's **311 Service Requests dataset** containing:
- **Complaint Type**: Category of service issue (e.g., Noise Complaint, Pothole)
- **Borough**: NYC borough where complaint was filed (Bronx, Brooklyn, Manhattan, Queens, Staten Island)
- **Agency**: City agency assigned to handle the complaint
- **Count**: Number of complaints in that category/borough/agency combination

**Data period**: January 2025 – January 2026

## How to Use the Visualization

### Opening the Interactive HTML

1. Open `nyc_311_sankey.html` in any modern web browser
2. The Sankey diagram displays immediately with all 5 boroughs, top 10 complaint types, and assigned agencies

## References

- [NYC Open Data: 311 Service Requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2020-to-Present/erm2-nwe9)
- [Plotly Sankey Diagrams](https://plotly.com/python/sankey-diagram/)
- [Plotly.js API](https://plotly.com/javascript/)

## License

This project uses publicly available NYC Open Data (public domain). Feel free to use, modify, and share.
