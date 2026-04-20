# Trend-Analysis
Built ETL pipeline (Extract → Transform → Load) \
Integrated API-based data ingestion (no authentication required) \
Implemented text moderation layer for safe analytics \
Produced actionable insights via data visualization 


Functionality- \
🔹 Data Ingestion Layer \
Fetches real-time post data from Lemmy using REST APIs \
Handles API responses and error validation \
🔹 Data Storage Layer \
Stores raw data in JSON format (raw_data.json) \
Ensures reproducibility and traceability \
🔹 Data Processing Layer \
Cleans and transforms data using Pandas \
Applies: \
  Null value removal \
  Score-based filtering \
Profanity detection via better-profanity \
🔹 Analytics Layer \
Performs statistical analysis using NumPy \
Extracts: \
Average engagement metrics \
Top trending posts \
Most discussed topics \
🔹 Visualization Layer \
Generates insights through charts using Matplotlib \
Displays top-performing content and distributions 
