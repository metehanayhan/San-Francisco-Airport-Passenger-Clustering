# San Francisco Airport Passenger Clustering

## About the Project
This project uses passenger movement data from San Francisco International Airport to perform K-Means clustering and create meaningful passenger segments. The goal is to understand different passenger behaviors at the airport and gain insights into various passenger groups. The Elbow Method is employed to determine the optimal number of clusters, and the results are visualized to highlight the segmentation.

## Dataset Overview
The dataset used in this project includes the following features related to passenger movements:
- **Activity Period**: The year and month of the activity.
- **Operating Airline**: The airline operating the flight.
- **Operating Airline IATA Code**: IATA code of the operating airline.
- **Published Airline**: The airline that published the flight.
- **Published Airline IATA Code**: IATA code of the published airline.
- **GEO Summary**: Geographic summary of the flight.
- **GEO Region**: Geographic region or country of the flight.
- **Activity Type Code**: Type of passenger activity (e.g., Enplaned, Deplaned).
- **Price Category Code**: Price category of the ticket.
- **Terminal**: The terminal from which passengers are served.
- **Boarding Area**: The area or gate where passengers board the plane.
- **Passenger Count**: The number of passengers in the specified activity.

## Steps
1. **Exploratory Data Analysis (EDA)**: Initial analysis of the dataset, including null value handling and summary statistics.
2. **Data Preprocessing**: Filling missing values, encoding categorical variables, and scaling features.
3. **K-Means Clustering**: Using K-Means to cluster the data.
4. **Elbow Method**: Determining the optimal number of clusters.
5. **Clustering Results**: Analyzing and visualizing the clusters based on passenger count and geographic region.

## Requirements
The project requires the following Python libraries:
- pandas
- scikit-learn
- matplotlib
- yellowbrick
- scipy

You can install these dependencies using:
```bash
pip install -r requirements.txt

## Results
The optimal number of clusters was determined using the Elbow Method. The silhouette score achieved was 0.828, indicating well-defined clusters. The results are visualized to show the relationship between passenger count and geographical region across different clusters.