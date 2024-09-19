
# 🌍 Commodity Dashboard with Proportional Symbol Map

This project is a **Dash**-based web application that visualizes commodity trading data across different countries. It features a **proportional symbol map** where the size of the circles is proportional to the total value of goods (`totvalue`) for each destination country. The dashboard allows users to filter the data by **commodity type**, **destination country**, and **date range**. The filtered data is displayed in a table, and the map is dynamically updated to reflect the filtered results.

## 🛠️ Features

- **Interactive Map**: A world map with proportional circles showing the total value of goods shipped to each destination country.
- **Dynamic Filters**:
  - **Commodity Type**: Filter by specific commodities.
  - **Destination Country**: Filter by specific destination countries.
  - **Date Range**: Select a custom date range to filter the data.
- **Data Table**: Display the filtered data in a table format.
- **Responsive Design**: The dashboard resizes to fit different screen sizes.

## 🚀 How to Run the Project

### 1. Clone the Repository
First, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/commodity-dashboard.git
cd commodity-dashboard
```

### 2. Set up a Virtual Environment (Optional but Recommended)
It's good practice to use a virtual environment to manage dependencies:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
Install the required Python packages from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 4. Run the Application
After installing the dependencies, you can run the app using:

```bash
python app.py
```

This will start the Dash server, and you can open the dashboard by navigating to `http://127.0.0.1:8050/` in your web browser.

Alteranatively, the code is also available in app_notebook.ipynb.

### 5. Interact with the Dashboard
- Use the dropdown filters and the date picker to filter the data.
- The map will update to reflect the filtered results.
- The filtered data is also displayed in a table below the map.

## ⚙️ Project Customization

- **Data**: You can modify the data by replacing or editing the `country_lat_long` and `commodity_codes` dictionaries in the code.
- **Map Customization**: The map projection, color schemes, and other layout elements can be customized using Plotly’s `geo` and `scatter_geo` options.

## 🧑‍💻 Technologies Used

- **Dash**: A Python web framework for building analytical web applications.
- **Plotly**: A graphing library to create interactive, web-ready visualizations.
- **Pandas**: For data manipulation and analysis.
- **Faker**: A library for generating fake data (used in generating random data for the dashboard).
- **Python 3.8+**

