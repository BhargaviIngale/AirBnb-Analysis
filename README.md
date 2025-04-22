# 🏡 Airbnb Data Analysis & Visualization

An interactive web application built using **Streamlit** and **Power BI/Tableau** for in-depth analysis of Airbnb listings. The project focuses on uncovering insights related to pricing trends, availability patterns, and geospatial dynamics in the travel and tourism domain.

---

## 🌐 Domain

**Travel Industry, Property Management, and Tourism**

---

## 🛠️ Technologies & Skills Used

- **Python Scripting**
- **Data Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Streamlit Web App**
- **Geospatial Visualization**
- **Power BI / Tableau**
- **Pandas, NumPy, Plotly**

---

## 📌 Problem Statement

This project analyzes Airbnb listing data stored in **MongoDB Atlas**, with the following key objectives:

- Connect and retrieve Airbnb data from JSON file.
- Clean and prepare data for analysis.
- Build a Streamlit-based interactive app for visualization.
- Create maps and charts to understand pricing, availability, and neighborhood trends.
- Build dashboards using Tableau or Power BI for comprehensive insights.

---

## 🔍 Project Objectives

1. **JSON Integration**  
   Collect and retrieve Airbnb listing data from JSON file.

2. **Data Cleaning & Preparation**  
   Handle missing values, duplicates, and data type inconsistencies using Pandas.

3. **Streamlit Application**  
   - Visualize listing distribution using maps.
   - Display pricing and rating data interactively.

4. **Price Analysis**  
   - Explore trends based on property type, region, and season.
   - Use dynamic plots and filters.


5. **Dashboard Creation**  
   - Use **Tableau** or **Power BI** to present combined insights.

---

## 🗃️ Data Source

- **Sample Airbnb Dataset** retrieval from JSON file.
- Includes: `listings`, `reviews`, `users`.
<!--- 📎Dataset Link: *[Insert your GitHub repo or data link here]*.
- Demo link:*[Insert your linkedin here]*. -->

### Example JSON Structure

```json
{
  "_id": "unique_listing_id",
  "name": "listing_title",
  "location": {
    "type": "Point",
    "coordinates": [longitude, latitude]
  },
  "price": "listing_price",
  "availability": {
    "start_date": "YYYY-MM-DD",
    "end_date": "YYYY-MM-DD"
  },
  "rating": "average_rating",
  "amenities": ["wifi", "kitchen"],
  "reviews": [
    {
      "reviewer_id": "123",
      "reviewer_name": "Alex",
      "comment": "Great place!",
      "rating": "5"
    }
  ]
}
```

## 🎓 Learning Outcomes

By completing the **Airbnb Data Analysis** project, we gain hands-on experience and proficiency in the following key areas:

### 🌐 1. Retrieving Data from JSON File
- Retrieve data from JSON format and convert it to CSV.

### 💻 2. Python Scripting & Data Preprocessing
- Use **Pandas** and **NumPy** for data cleaning, transformation, and preprocessing.
- Handle missing values, remove duplicates, and convert data types to ensure high data quality.

### 📊 3. Exploratory Data Analysis (EDA)
- Perform in-depth exploratory analysis of pricing, availability, reviews, and ratings.
- Identify trends, outliers, and correlations using visualization libraries like **Plotly** and **Seaborn**.

### 🌍 4. Geospatial Visualization & Mapping
- Visualize listing coordinates on interactive maps using libraries such as  **Plotly**.
- Analyze regional trends and location-based patterns through geospatial analysis.
- Apply clustering or heatmaps to reveal high-demand zones and price hotspots.

### ⚙️ 5. Streamlit Web Application Development
- Build a user-friendly and interactive **Streamlit** application.
- Incorporate widgets (dropdowns, sliders, checkboxes) to filter and explore Airbnb data.
- Embed dynamic visualizations and maps to enhance user experience.

### 📈 6. Interactive Dashboards using Tableau/Power BI
- Design comprehensive dashboards for decision-making using **Tableau** or **Power BI**.
- Integrate charts, maps, and tables for storytelling and summarizing key insights.
- Build interactive drill-down views for exploring seasonal, regional, and categorical trends.

### 🛠️ 7. End-to-End Data Pipeline
- Connect frontend (Streamlit) to backend (MongoDB) and integrate it with visualization tools.
- Develop an end-to-end data processing pipeline for real-time or static analysis.
- Understand the flow of data from ingestion to visualization and reporting.

---

