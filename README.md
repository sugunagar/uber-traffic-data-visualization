# uber-traffic-data-visualization
# 🚗 Uber Traffic Data Visualization

A web-based data visualization project analyzing Uber traffic patterns in **Bangalore city (2020–2022)**

## 📌 Live Demo
👉 [Click here to view the project](https://sugunagar.github.io/uber-traffic-data-visualization/)

---

## 📖 About the Project

This project helps travelers understand traffic patterns and predict travel times between locations in Bangalore. Using **20,000 rows** of Uber trip data, it provides multiple interactive visualizations to help users make smarter travel decisions.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📊 **Bar Graph Analysis** | Average travel time across 4 time slots of the day |
| 🗓️ **Heatmap / Calendar Analysis** | Peak traffic visualization across 2020–2022 |
| 📈 **Area-wise Line Chart** | Passenger volume between specific Bangalore locations |
| 🔮 **Travel Time Prediction** | Predict time from source to destination by time of day |
| 🗺️ **Route Prediction** | Best route with intermediate stops and travel time |

---

## 🗂️ Project Structure
```
├── index.html              # Home page / landing page
├── form.html               # Travel time prediction form
├── graph1_bar.html         # Bar chart visualization
├── graph2_heatmap.html     # Heatmap / calendar analysis
├── graph3_line.html        # Area-wise line chart
├── route_prediction.html   # Route prediction output
└── uber_data.csv           # Dataset
```

---

## 📊 Dataset

- **Source:** Uber Developer API & Uber trip receipts
- **Size:** 20,000 rows × 7 columns
- **Period:** 2020 – 2022 (Bangalore city)
- **Dataset Link:** [uber_data.csv](https://github.com/sugunagar/uber-traffic-data-visualization/blob/main/uber_data.csv)

### Columns

| Column | Type | Description |
|---|---|---|
| Date | Date | Trip date |
| Start_destination | String | Pickup location |
| End_destination | String | Drop location |
| Am_timings | Float | Travel time 12:00–6:00 AM |
| Midday_timings | Float | Travel time 6:00–12:00 PM |
| Evening_timings | Float | Travel time 12:00–6:00 PM |
| Mid_night_timings | Float | Travel time 6:00–12:00 AM |

---

## 🔍 Key Insights

Average travel times across Bangalore (full dataset):

- 🌙 **Midnight (12:00–6:00 AM):** 16.01 minutes ✅ Best time to travel
- ☀️ **AM (6:00–12:00 PM):** 27.30 minutes
- 🌆 **Midday (12:00–6:00 PM):** 32.49 minutes ❌ Most congested
- 🌇 **Evening (6:00–12:00 AM):** 20.04 minutes

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Styling:** Tailwind CSS
- **Charts:** Google Charts (Bar, Calendar/Heatmap, Line)
- **ML Model:** Support Vector Machine (SVM) — 67–83% accuracy
- **Data Processing:** Python (Pandas, Jupyter Notebook)

---

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/sugunagar/uber-traffic-data-visualization.git
```
2. Open the project folder
3. Open `index.html` in any modern web browser
4. No server setup required!

---

## 📚 References

- Andrienko et al. — Analysis of Flight Variability, IEEE TVCG (2018)
- Fischer-Baum & Bialik — FiveThirtyEight: Uber vs. Manhattan Taxis
- Uber Engineering Blog — Data Visualization Intelligence (2016)

---

## 📄 License

This project was developed for academic purposes at UNT.
