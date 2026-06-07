# Top 5000 YouTube Channels - Exploratory Data Analysis (EDA)

This project is an exploratory data analysis (EDA) focused on analyzing the top 5,000 YouTube channels. Using a dataset of channel metrics, the notebook walks through data cleaning, processing missing strings, and visualizing patterns across channel grades, video uploads, subscriber counts, and total views using Seaborn.


## Project Structure

The repository includes:
* **`7-top-5000-youtube-channel (with seaborn) (answers).ipynb`**: The Jupyter Notebook containing the data cleaning steps, text processing, analytical questions, and Seaborn visualization code.
* **`7_top_5000_youtube_channels.csv`**: The dataset containing ranking performance and metric details for the top 5,000 channels.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy, Seaborn
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

The `7_top_5000_youtube_channels.csv` dataset contains performance statistics across the following 6 attributes:
* **Rank:** The positioning rank of the channel based on performance.
* **Grade:** The platform-assigned channel tier rating (e.g., A++, A+, A, B+).
* **Channel name:** The display title of the YouTube creator account.
* **Video Uploads:** The total number of videos published on the channel.
* **Subscribers:** Total audience subscription count.
* **Video views:** Cumulative lifetime view counts across all uploads.


## Key Tasks & Insights Covered

The notebook walks through data profiling and answers specific performance-driven questions:
1. **General Profiling:** Checking total records, inspecting column headers, checking the shape, and uncovering internal structure types.
2. **Data Cleaning & Type Casting:** Finding and replacing invalid data markers (like `--` strings), converting numerical columns stored as text into proper integer or float datatypes, and treating missing null rows.
3. **Top Channel Spotlights:** Querying the dataset to isolate and display the exact channels with the highest video upload volume.
4. **Seaborn Distributions:** Utilizing data visualizations to chart categorical metrics, comparing distribution patterns across channel tiers, and looking at relationships between views and subscriber counts.
5. **Feature Engineering:** Calculating custom metrics like average views per channel grouping to assess which tier levels generate the highest user engagement.


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Move your dataset (`7_top_5000_youtube_channels.csv`) into the same folder if it isn't already there.
4. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy seaborn notebook
   jupyter notebook


## Author

Priya Patel  
Aspiring Data Analyst  
Email: patelpriya18217@gmail.com    
GitHub: [priyapatel96140](https://github.com/priyapatel96140)  

If you like this project, feel free to give it a star!
