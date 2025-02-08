### **Netflix Data Visualization Project** 🌊

#### **📌 Project Overview**
This project aims to analyze and visualize a dataset of Netflix movies and TV shows. Using **Amazon QuickSight**, we have created insightful visualizations based on the dataset stored in **Amazon S3**. The project helps in understanding trends in Netflix content over the years.

This project was created with the help of Nextwork.

---

### **🛠️ Tools Used**
- **Amazon S3** – To store the dataset (`netflix_titles.csv`) and its metadata (`manifest.json`).  
- **Amazon QuickSight** – For creating interactive visualizations.  
- **Git & GitHub** – Version control and project storage.  

---

### **📂 Dataset and Storage**
- The dataset (`netflix_titles.csv`) and `manifest.json` file were uploaded to an **Amazon S3** bucket.  
- QuickSight was connected to S3 to fetch the data for visualization.  

#### **🔗 Connecting S3 to QuickSight**
1. Upload the dataset (`netflix_titles.csv`) and `manifest.json` to **Amazon S3**.  
2. In QuickSight, create a new dataset and choose **S3** as the data source.  
3. Provide the **S3 manifest file** to link QuickSight with the dataset.  
4. Load the data and start creating visualizations.  

---

### **📊 Visualizations Created**
Using **Amazon QuickSight**, the following insights were generated:  

1. **Number of Movies & TV Shows by Release Year**  
   - Displays the trend of content released over the years.  
   - Helps identify peak years of content production.  

2. **Movies vs. TV Shows by Release Year**  
   - A breakdown of how many movies vs. TV shows were released each year.  
   - Useful for understanding content distribution trends.  

3. **Top Genres (Thrillers, Comedies, Action & Adventure) Released Since 2015**  
   - Focuses on popular genres in recent years.  
   - Helps in analyzing audience preferences.  

4. **Titles Added Over Time**  
   - Shows the timeline of when Netflix added movies/TV shows to its catalog.  

---

### **🚀 How to Use This Project**
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/AkhilaJanapati30/Netflix-Data-Visualization.git
   cd Netflix-Data-Visualization
   ```

2. **View the Dataset and Visualizations**  
   - Open `netflix_titles.csv` to explore the raw dataset.  
   - View `Quicksights_Dashboard.pdf` for insights and reports.  

3. **Modify and Update**  
   - If needed, update the dataset and re-upload it to **S3**.  
   - Refresh the QuickSight dashboard for new insights.  

---

### **📌 Future Enhancements**
- Adding **interactive dashboards** for better insights.  
- Integrating **machine learning** for content recommendations.  
- Expanding analysis to include **ratings and user engagement metrics**.  

---

