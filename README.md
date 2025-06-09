#  Startup-Data-Analysis

Uncover the pulse of India's rapidly evolving **startup ecosystem** with this **interactive data analysis and visualization dashboard**. Built using **Streamlit**, this tool transforms raw data into compelling insights, offering a clear, dynamic view of funding trends and key aspects of Indian startups, all sourced from a meticulously preprocessed dataset.

![Alt text](https://github.com/madhans476/Indian_Startup_Analysis/blob/main/samples/HOME.png)   ![Alt text](https://github.com/madhans476/Indian_Startup_Analysis/blob/main/samples/Map.png) ![Alt text](https://github.com/madhans476/Indian_Startup_Analysis/blob/main/samples/Lollipop.png)


## Project Structure
```plaintext
.
├── .streamlit
│   └── config.toml         # Streamlit configuration file
├── Pages                   # Contains the main dashboard pages
│   ├── CITIES.py           # Analysis based on headquarters location
│   ├── INVESTORS.py        # Analysis based on investment
│   ├── STARTUPS.py         # Analysis based on startup
│   └── VERTICAL.py         # Analysis based on verticals
├── HOME.py                 # Main homepage for the app
├── README.md               # Project documentation
├── cities.csv              # CSV file containing city-specific data
├── startup_funding.csv     # CSV file containing startup funding data
└── functions.py            # functions for plotting
```
## Key Features

* **Interactive Dashboard:** Built with Streamlit for a user-friendly and responsive experience.
* **Dynamic Visualizations:** Utilizes Altair and Plotly to create engaging charts, maps, and treemaps for exploring funding distribution, sector trends, and more.
* **Geospatial Analysis:** Leverages Geopy to geocode startup locations, enabling insights into geographical funding patterns.
* **Comprehensive Data Views:** Dedicated sections for analyzing startups by cities, investors, specific startup features, and industry verticals.
* **Responsive Filters:** Implement interactive filters and real-time updates for enhanced user engagement and granular data exploration.
## Tools and Technologies Used

- **Python**: Primary programming language used.
- **Streamlit**: Framework for building interactive web pages.
- **Pandas**: For reading and manipulating datasets in CSV format.
- **Altair**: Used for creating interactive visualizations.
- **Geopy**: Utilized for fetching latitude and longitude of cities.
- **Plotly**: Used for plotting a Treemap to visualize hierarchical data.
- **Jupyter Notebook**: Environment for data preprocessing and experimentation.

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Python 3.x
- Streamlit 1.37.1
- Altair 5.4.1
- Plotly 5.24.1
- Geopy 2.4.1
- Pandas 2.2.2

### Clone the Repository
```bash
git clone https://github.com/madhans476/Indian_Startup_Analysis.git
cd Indian_Startup_Analysis
```

### Running the application

To launch the Streamlit app:
 ```bash
 streamlit run HOME.py
 ```

### Usage

1. **Home Page**: Start with the Home page.

2. **Navigate to Analysis Pages**:
   - **Cities**: Explore startup distribution and density across Indian cities.
   - **Investors**: Analyze investor data and gain insights on funding types.
   - **Startups**: Look into specific startup features such as year, funding amounts and sectors.
   - **Vertical**: View data on different sectors within the startup ecosystem.

3. **Interactive Visualizations**: Use the interactive charts, maps, and treemaps to drill down into specific data points.

