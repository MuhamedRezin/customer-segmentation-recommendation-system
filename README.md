# Customer Segmentation and Recommendation System

## Project Overview
This project focuses on segmenting customers based on their purchasing behavior using machine learning techniques and recommending relevant products to each customer segment. The system analyzes transactional data from a UK-based online retail company and applies K-Means clustering to identify distinct customer groups. A cluster-based recommendation system is then used to suggest top-selling products within each segment. The results are visualized using interactive Power BI dashboards.

## Objective
The primary objective of this project is to improve marketing efficiency and boost sales by:
- Segmenting customers into meaningful groups based on purchasing behavior
- Generating personalized product recommendations for each customer segment
- Providing interactive dashboards for customer analysis and decision-making

## Dataset Information
The dataset used in this project is the UK-based Online Retail transactional dataset.

Due to GitHub file size limitations, the original dataset is not uploaded directly to this repository.

**Dataset Source:**  
https://archive.ics.uci.edu/ml/datasets/online+retail

### To run the project:
1. Download the dataset from the above link.
2. Rename the file to `customer_data.csv` if required.
3. Place the file inside the `data/` folder.
4. Run the notebooks in the `notebooks/` directory.

Note: Processed datasets generated during analysis (such as customer-level features) are included in the repository.

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Google Colab
- Power BI
- GitHub

## Project Workflow
1. Data cleaning and preprocessing
2. Feature engineering (Recency, Frequency, Monetary Value, etc.)
3. Feature scaling
4. Customer segmentation using K-Means clustering
5. Cluster evaluation and interpretation
6. Cluster-based recommendation system
7. Dashboard creation and visualization using Power BI

## Repository Structure
customer-segmentation-recommendation-system/
│
├── data/
│ └── customer_features.csv
│
├── notebooks/
│ └── project_notebook.ipynb
│
├── powerbi/
│ └── Customer_Segmentation_Recommendation.pbix
│
├── reports/
│ └── Project_Report.pdf
│
├── README.md

## Deliverables
- Python notebooks for data processing, clustering, and recommendation system
- Processed datasets
- Power BI dashboard source file (.pbix)
- Project report (PDF)

## Results
- Customers segmented into distinct groups based on purchasing behavior
- Cluster-based product recommendations generated for each customer
- Interactive dashboards created for segmentation analysis and recommendations

## Author
- Muhamed Rezin

## License
This project is for academic and internship purposes.
