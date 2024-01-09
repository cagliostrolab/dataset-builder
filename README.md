# Dataset Builder

This repository contains tools and scripts for building a dataset. The process is outlined below:

1. **Scraping Data**: Utilize [Gallery-dl](https://github.com/mikf/gallery-dl) to scrape the necessary JSON files. This tool is efficient in extracting data from a variety of online galleries and image hosting sites.

2. **Processing Data**:
   - **Data Cleaning**: The notebook included in this repo is designed to clean the data, particularly by removing undesired file extensions, ensuring the dataset's consistency and relevance.
   - **Key Extraction**: Extract crucial keys from the dataset. This step involves identifying and fetching important data points that are essential for your specific use-case.
   - **Classification**: Classify the data into special tags. This step helps in categorizing the data for better organization and accessibility.
   - **Label Preprocessing**: Preprocess the labels associated with the data. This is a crucial step for ensuring the labels are formatted correctly and are ready for further processing or analysis.
   - **Ordering**: Arrange the processed data in a specific order, if necessary, for your application or analysis.

3. **Downloading**: The final step involves the downloading process, where the cleaned, processed, and organized data is downloaded for use in your projects or analyses.

Be aware that the dataset building process can be very slow and may not be optimized for large-scale data scraping and processing. It is recommended to adjust your expectations accordingly and plan for potential delays in the dataset preparation phase.

The notebook provided in this repository is a comprehensive tool that guides you through each step of this process, making dataset building efficient and straightforward.
