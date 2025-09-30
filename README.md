 Project Overview 📊
 
InvOpt Supply Chain tackles overstocking and stockouts with data-driven forecasting. Drawing from Shivani's expertise in Lean Six Sigma, BPMN modeling, and cloud platforms (AWS, Google BigQuery, Snowflake), this tool predicts demand, optimizes reorder points, and boosts efficiency—ideal for logistics and operations pros.
Features ✨

Demand Forecasting:
Uses Prophet for precise sales predictions with seasonal trends.
Inventory Optimization: Computes safety stock, reorder points, and Economic Order Quantity (EOQ).
Data Insights: Provides correlation heatmaps, outlier detection, and seasonal decomposition.
Model Evaluation: Offers MAE and RMSE for forecast accuracy.
Scalable Design: Built for Google Colab, compatible with AWS or Snowflake.

Tech Stack 🛠️

Python: Pandas, NumPy, Prophet, Scikit-learn, Statsmodels
Visualization: Matplotlib, Seaborn
Data Source: Kaggle Demand Forecasting Dataset
Environment: Google Colab

Getting Started 🚀

Prerequisites

Python 3.x
Google Colab account
Kaggle API key (kaggle.json)

Setup Instructions

Clone the Repository

bashgit clone https://github.com/shivani17062001-source/Predictive-Inventory-Optimization-for-Supply-Chain-Efficiency

cd invopt-supply-chain

Install Dependencies

Run in Colab:
python!pip install prophet kaggle

Configure Kaggle API

Upload kaggle.json to Colab.
Execute:
python!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json



Download Dataset

python!kaggle competitions download -c demand-forecasting-kernels-only
!unzip demand-forecasting-kernels-only.zip

Run the Notebook

Open InvOpt_Supply_Chain.ipynb in Colab and execute all cells.

Usage 📈

Analyze sales trends for any store-item pair (e.g., Store 5, Item 10).
Review forecasts and optimization metrics to simulate inventory strategies.
Adjust parameters (e.g., lead time, service level) for your needs.

Contributing 🤝

Contributions welcome! Fork the repo, create a feature branch, and submit a pull request. Discuss major changes via an issue first.
Contact 📧

Shivani Uppala

Email: Shivaniuppala034@gmail.com
LinkedIn: linkedin.com/in/shivaniuppala
Location: Northridge, CA



License 📜
MIT License - Use and modify freely!

