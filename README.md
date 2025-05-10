# Amazon-Product-Recommendation-System
The Cluster Setup Documentation outlines the configuration and deployment of a multi-node Hadoop-Spark cluster, including hardware specs, software setup, networking, and troubleshooting. It provides steps for installing, configuring, and verifying Hadoop HDFS and Apache Spark in a distributed environment

1. Technologies Used
• Apache Spark: Distributed processing engine for large-scale data analytics.
• Hadoop HDFS: Distributed storage system for handling tweet datasets.
• Python/PySpark: For implementing NLP, ML models, and Spark jobs.
• Jupyter Notebook: Interactive environment for prototyping and analysis.
• OpenCage Geocoding API: For converting text locations to coordinates.
• Folium/Plotly: Visualization libraries for spatial and sentiment analysis.
--------------------------------------------------------------------------------------------------------------------------------------
2. Cluster Configuration
Hardware Setup:
• Master Node: 1 PC (4 CPU cores, 4GB RAM, 25GB SSD).
• Slave Nodes: 2 PCs (each with 4 CPU cores, 4GB RAM, 25GB SSD).
Software Stack:
• OS: Ubuntu 20.04 LTS.
• Java: OpenJDK 8 (required for Spark/Hadoop).
• Spark: v3.2.1 (configured in standalone mode).
• Hadoop: v3.3.1 (for HDFS storage).
Network:
• Static IPs assigned to all nodes.
• Password-less SSH configured between master and slaves.
