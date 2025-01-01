# Cybersecurity Attack Analysis and Visualization

## Overview
This project analyzes and visualizes cybersecurity attack data to identify trends, patterns, and insights that can enhance understanding and response strategies. The dataset contains detailed information about 40,000 attack events, captured across various network segments and involving diverse attack types.

## Dataset Description
- **Rows**: 40,000
- **Columns**: 25
- **Sample Columns**:
  - **Timestamp**: Date and time of the event.
  - **Source IP Address**: The IP address initiating the attack.
  - **Destination IP Address**: The target IP address.
  - **Protocol**: Protocol used in the communication (e.g., TCP, UDP, ICMP).
  - **Packet Length**: Size of the data packet.
  - **Attack Type**: Classification of the attack (e.g., Malware, DDoS).
  - **Severity Level**: Categorization of the attack's impact (e.g., Low, Medium, High).
  - **Malware Indicators**: Indicators of compromise (IoCs) for malware.
  - **Anomaly Scores**: Anomaly detection scores for each event.
  - **Geo-location Data**: Geographical information about the source or target.
  - **Log Source**: Source of the log data (e.g., Firewall, Server).

## Objectives
1. Understand the distribution of attack types and their frequency.
2. Analyze severity levels and anomaly scores for insights into attack behavior.
3. Visualize geolocation data to identify regions with higher attack occurrences.
4. Explore relationships between attack types, protocols, and severity.

## Key Visualizations
1. **Attack Type Distribution**: Bar plots to show the frequency of each attack type.
2. **Severity Level Insights**: Pie charts or stacked bar plots highlighting the proportions of low, medium, and high-severity attacks.
3. **Anomaly Score Trends**: Line graphs or density plots for anomaly score trends over time.
4. **Geolocation Heatmaps**: Heatmaps showcasing attack intensity by geographic region.

## Technologies Used
- **Python Libraries**:
  - `pandas`: For data loading and preprocessing.
  - `matplotlib`: For plotting graphs and charts.
  - `seaborn`: For advanced data visualization.
- **Dataset Source**: https://www.kaggle.com/datasets/teamincribo/cyber-security-attacks/data

## How to Run
1. Load the provided dataset (`cybersecurity_attacks.csv`).
2. Use the Python script (`main.ipynb`) to perform analysis and generate visualizations.
3. Interpret the results based on the plots and insights derived.

## Insights and Findings
- The dataset reveals recurring patterns in malware and DDoS attacks.
- Severity analysis highlights that low-severity attacks are the most common.
- Anomaly scores correlate with certain attack types and geographic locations.
- Geo-location data pinpoints hotspots for network attacks, aiding in targeted defense strategies.

## Conclusion
This project successfully demonstrates the utility of data analytics in cybersecurity. While the analysis highlights recurring attack patterns, severity levels, and geographical hotspots, future enhancements could include incorporating machine learning models for prediction and automating real-time dashboards. 
