# COVID-19 Global Data Tracker (Desktop GUI)

A Python-based desktop application that allows users to view and analyze real-time COVID-19 data globally. The app includes a simple GUI built with Tkinter, enables country-specific searches, and displays historical data trends using charts.

---

## Project Objectives

- Provide a user-friendly interface to access global and country-level COVID-19 statistics.
- Visualize the last 30 days of cases and deaths for any selected country.
- Help users track pandemic trends using real-time data from a public API.
- Offer insights in a lightweight, install-free desktop application.

---

## Tools & Libraries Used

- **[Tkinter](https://docs.python.org/3/library/tkinter.html)** – GUI framework (standard with Python)
- **[Requests](https://docs.python-requests.org/)** – for making API calls
- **[Pandas](https://pandas.pydata.org/)** – for handling tabular data
- **[Matplotlib](https://matplotlib.org/)** – for plotting historical trends
- **[Disease.sh API](https://disease.sh/)** – public API source for COVID-19 data

---

## How to Run the Project

### Prerequisites
Ensure Python 3.7 or higher is installed.

### Installation

1. **Clone or download** the project folder.
2. **Install dependencies** by running:

   ```bash
   pip install -r requirements.txt
   ```

### ▶Running the App

Run the `main.py` file:

```bash
python main.py
```

---

## Features

- Top 10 countries by number of cases
- Search by country name to get current stats
- View a line chart of the last 30 days of cases and deaths
- Lightweight desktop GUI – no web browser needed

---

## Insights & Reflections

- Tkinter was effective for rapid GUI development but has visual limitations.
- The Disease.sh API is reliable and detailed but depends on external uptime.
- This project could be enhanced with auto-suggest for countries and light/dark mode.
- In the future, a web-based or mobile version could make this more widely accessible.

---

**Made with Python to stay informed and aware.**
