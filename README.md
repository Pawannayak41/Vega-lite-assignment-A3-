# 📊 Vega-Lite Assignment 3 — Sales Data Visualization Dashboard

🔗 **Live Demo:**
https://pawannayak41.github.io/Vega-lite-assignment-A3-/

---

## 📌 Overview

This project is part of the **ELL880A Visualization Assignment 3**, where the objective is to build an interactive dashboard using **Vega-Lite** to visualize tabular sales data.

The dashboard presents multiple coordinated views to explore patterns in sales across time, products, and representatives.

---

## 🎯 Assignment Requirements

The following tasks were implemented as per the assignment instructions :

* Donut Chart showing **Total Sales by Representative**
* Streamgraph showing **Sales Trends over Time by Item**
* Trellis Histogram showing **Units Distribution per Item with Mean Overlay**
* Two additional visualizations with interactions:

  * Interactive Heatmap
  * Linked Brush Charts
* A **Multiview (vconcat)** combining all visualizations
* Hosted as a public HTML page

---

## 📊 Visualizations Included

### 1. Donut Chart

* Displays total revenue contribution by each sales representative
* Interactive tooltip for detailed values

### 2. Streamgraph

* Shows how sales vary over time for each product
* Uses centered stacking (`stack: center`)

### 3. Trellis Histogram

* Faceted histograms for each product
* Includes mean overlay using rule marks

### 4. Interactive Heatmap

* Shows revenue by **Rep × Item**
* Row selection interaction to highlight a representative

### 5. Linked Brush Charts

* Top chart: Monthly sales
* Bottom chart: Rep-level breakdown
* Interactive brushing filters data dynamically

### 6. Multiview Dashboard

* All five charts combined using Vega-Lite `vconcat`
* Provides a unified analytical view

---

## 🛠️ Tech Stack

* **Vega-Lite v5**
* **Vega-Embed**
* HTML, CSS, JavaScript
* Hosted using **GitHub Pages**

---

## 📂 Project Structure

```
Vega-lite-assignment-A3/
│── index.html   # Main dashboard file
│── README.md    # Project documentation
```

---

## 🚀 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/Pawannayak41/Vega-lite-assignment-A3-.git
```

2. Open `index.html` in your browser

---

## 🌐 Deployment

This project is deployed using **GitHub Pages**.
Any changes pushed to the `main` branch automatically update the live site.

---

## ✨ Features

* Fully interactive visualizations
* Clean and responsive UI
* Multi-view dashboard design
* No external data dependency (data embedded in code)

---

## 👨‍💻 Author

**Pawan Kumar**
Roll No: 2024EET2379

---

## 📅 Submission Details

* Course: ELL880A Visualization
* Assignment: Vega-Lite Assignment 3
* Due Date: April 7, 2026

---

## 📖 Notes

This project demonstrates how **declarative visualization (Vega-Lite)** can be used to build rich, interactive dashboards with minimal code while maintaining flexibility and clarity.

---
