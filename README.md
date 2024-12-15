# Netflix TV Shows & Movies Dataset EDA

This project performs **Exploratory Data Analysis (EDA)** on the Netflix TV Shows & Movies dataset using PySpark. The analysis provides insights into content trends, such as top genres, directors, and production details, leveraging PySpark's distributed processing capabilities.

## Getting Started

### Prerequisites

To run this project, you will need the following:

- **Docker**
- **PySpark**
- **Jupyter Notebook**

### Setup

Follow the steps below to set up your environment:

1. **Install Docker:** Download and install Docker from the [official website](https://www.docker.com/).

2. **Pull the PySpark Docker Image:** Open your terminal and run the following command:

   ```bash
   docker pull jupyter/pyspark-notebook
   ```

3. **Run the Docker Container:** Start the container with the following command:

   ```bash
   docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
   ```

   This will start a Jupyter Notebook server. You can access it by navigating to [http://localhost:8888](http://localhost:8888) in your web browser.

### Dataset

1. **Download the Dataset:**
   - Go to [Kaggle's Netflix TV Shows & Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows).
   - Download the dataset and place it in your project directory. Rename the file to `netflix_titles.csv` for consistency.

## Running the Analysis

1. **Open Jupyter Notebook:** Navigate to [http://localhost:8888](http://localhost:8888) and open a new notebook.

2. **Copy the Python Code:** Use the Python code provided in this project to perform EDA on the dataset. This code processes the data and extracts valuable insights.

## Analysis Overview

The analysis provides insights into the following:

1. **Dataset Information:**

   - Display the schema of the dataset.
   - Count the total number of records.

2. **Top Genres by Content Count:**

   - Identify the most frequent genres available on Netflix.

3. **Directors with the Most Titles:**

   - Find the top directors based on the number of titles they have contributed.

4. **Titles with the Longest Durations:**

   - Highlight the longest movies or TV shows by duration.

5. **Average Release Year by Content Type:**

   - Calculate the average release year for each content type (Movies or TV Shows).

## Results

The EDA results provide key insights such as:

- **Popular Genres:** Identifying the genres with the highest content count.
- **Top Directors:** Highlighting the most prolific directors on Netflix.
- **Long Durations:** Listing movies or TV shows with exceptional durations.
- **Release Trends:** Understanding content production trends over the years.

With this analysis, you can better understand Netflix's content library and make informed decisions or visualizations based on the data.

