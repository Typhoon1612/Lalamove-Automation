Lalamove Automation Project
Overview
This project is designed to automate and track Lalamove trip data, specifically focusing on logistics performance for a Perodua Viva. It includes tools to generate synthetic datasets for testing and a Power BI dashboard for visual analysis.

Project Structure
Lalamove_Project/: Contains the core data generation scripts and CSV datasets.

make_trips.ipynb: A Jupyter notebook used to generate fake Lalamove trip data using Python, Pandas, and NumPy.

lalamove_trips_march.csv: A generated dataset containing 100 trips with details such as Trip ID, Date, Distance (KM), and Earnings (RM).

lalamove_trips_april.csv: A generated dataset containing 50 additional trips for the month of April.

Lalamove_Viva_Tracker.pbix: A Power BI file used to visualize trip metrics, earnings, and vehicle efficiency.

Data Schema
The generated CSV files follow this structure:

Trip_ID: Unique identifier for each delivery (e.g., LALA-0001).

Date: Timestamp of the delivery.

Distance_KM: Total distance traveled in kilometers.

Lalamove_Earnings_RM: Total earnings in Malaysian Ringgit for the specific trip.

Features
Automated Data Generation: Uses Python to simulate realistic trip data, allowing for testing without using sensitive personal records.

Visualization: Integrates with Power BI to monitor performance trends and earnings over time.

Version Control: Utilizes .gitattributes to manage large files and project tracking.

Getting Started
Open Lalamove_Project/make_trips.ipynb to generate new monthly datasets.

Update the source paths in Lalamove_Viva_Tracker.pbix to point to your latest CSV files for updated visualizations.
