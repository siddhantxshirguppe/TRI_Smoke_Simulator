# **TRI_Smoke_Simulator**

The **TRI Smoke Simulation Project** is an interactive visualization and data analysis tool designed to explore the impact of toxic releases from facilities on communities across Chicago. By leveraging multiple datasets and advanced simulation techniques, this project aims to enhance understanding and foster informed decision-making for environmental justice and public health.

---

## **Key Features**

### **Community-Level Aggregation**
- Data is aggregated at the **community level**, balancing the granularity of census tracts and the broader scope of zip codes.
- **Why Community Level?**
  - Provides a midpoint between detailed (census tract) and broader (zip code) aggregations.
  - Ideal for advocacy and storytelling efforts targeted at specific communities.

### **Interactive Visualizations**
- Dynamic visualizations of **smoke density** across a **200x200 grid**.
- Ability to **overlay additional datasets**, such as:
  - Raw facility emissions.
  - Elementary school locations.

### **Cellular Automata Simulation**
- Simulations powered by **cellular automata models** mimic real-world pollutant dispersion.
- Incorporates factors like:
  - **Wind patterns** (speed and direction).
  - **Diffusion rates**.
  - **Dissipation factors**.
- Real-time updates allow users to observe smoke spreading dynamically.

### **Real-Time Exploration**
- Supports **overlaying multiple datasets**, enabling participants to reassess conclusions dynamically.
- Interactive features visualize the intersection of:
  - Toxic releases.
  - Socioeconomic and demographic factors.

### **Purpose-Driven Design**
- Designed to support **agentic sense-making**, empowering users to explore and challenge data narratives.
- Promotes **environmental justice** by providing actionable insights into the effects of toxic releases on underserved communities.

---

## **How It Works**

### **Data Preparation**
- **Public datasets**:
  - Toxic release inventory (TRI).
  - Elementary schools.
  - Community boundaries.
- Datasets are cleaned and preprocessed.
- Data is aggregated at the **community level** for consistency.

### **Cellular Automata Simulation**
- Uses **grid-based models** to calculate smoke diffusion and dissipation over time.
- Factors like **wind direction**, **speed**, and **terrain** are included to reflect realistic pollutant spread.

### **Visualization Creation**
- Users explore smoke density visualizations overlaid with:
  - **Socioeconomic data.**
  - **Educational data.**
- Additional overlays (e.g., community names) enrich the analysis.

---

## **Impact**
- Serves as a **powerful tool** for:
  - Researchers.
  - Policymakers.
  - Advocates.
- Addresses **environmental and health challenges** in marginalized communities.
- Provides an interactive and data-driven platform for meaningful engagement with complex environmental data.

---

## **Built With**
- **Python**: Data preprocessing and static visualizations.
- **GeoPandas**: Geospatial data manipulation.
- **Matplotlib**: Initial exploratory visualizations.
- **Cellular Automata Models**: Smoke dispersion simulation.



![image](https://github.com/user-attachments/assets/ffeda6e0-2490-40d7-89f1-c42f9a14e774)
![image](https://github.com/user-attachments/assets/ba971938-a7d0-4d25-a0fa-98104a88bc96)
![image](https://github.com/user-attachments/assets/cfbdee29-f6db-48a9-bb4c-8356562c4861)

