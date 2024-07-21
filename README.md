# Amazon QuickSight Dashboard Project

## Overview
This project demonstrates how to visualize a dataset using Amazon QuickSight, AWS's data visualization service. The dataset used here is based on Netflix titles, showcasing how to upload data to an S3 bucket, connect it to QuickSight, and create insightful visualizations.

## Game Plan
### 🪣 Upload Dataset to S3:
- Store dataset files (netflix_titles.csv and manifest.json) in an S3 bucket.

### 🆕 Create Amazon QuickSight Account:
- Register for a QuickSight account, which is free to set up.
- Enable QuickSight's access to your S3 bucket where the dataset resides.

### 🔗 Connect Dataset to Amazon QuickSight:
- Link the dataset in the S3 bucket to QuickSight using the manifest.json file's URI.

### 📊 Create Visualizations:
- Utilize QuickSight to generate various graphs and charts from the dataset.
- Example: Visualize the number of movies released each year categorized by type (movie or TV show).

### 🏆 Publish Dashboard:
- Compile all visualizations into a cohesive dashboard.
- Export the dashboard as PDF for sharing and documentation purposes.

## Steps Completed
### Upload Project Files into S3
The dataset (netflix_titles.csv) and its metadata (manifest.json) were uploaded to an S3 bucket. The manifest.json file was edited to ensure it points correctly to the dataset's URI within the bucket.

![Screenshot 2024-07-21 at 21 49 06](https://github.com/user-attachments/assets/fa94cfda-a6ae-4312-8bb8-85fd92bfac89)


### Create QuickSight Account
A QuickSight account was created without any cost. Setup took less than 5 minutes, and access to the S3 bucket was configured to facilitate dataset visualization.

![Screenshot 2024-07-21 at 21 57 12](https://github.com/user-attachments/assets/ee958312-9e1f-431d-9fc3-8fe6ddc3b3f2)


### Connect S3 QuickSight
The dataset in the S3 bucket was connected to QuickSight by providing the URI from the manifest.json file. This step ensures QuickSight can locate and interpret the data for visualization.

![Screenshot 2024-07-21 at 22 03 27](https://github.com/user-attachments/assets/b269c8cd-15fa-4960-bb1e-7f2ed2622c26)


### Make Visualizations
Using QuickSight's AutoGraph feature, visualizations such as charts depicting the number of movies released each year by type (movie or TV show) were created. Filters were applied to focus on specific years and genres, enhancing data analysis.

![Screenshot 2024-07-21 at 22 12 49](https://github.com/user-attachments/assets/1131a679-03f4-4a3f-8d32-14079b83f3af)


### Set Up Your Dashboard
Visualizations were organized into a presentable dashboard layout. The dashboard design was structured to highlight key insights effectively.

![Screenshot 2024-07-21 at 22 51 35](https://github.com/user-attachments/assets/9802276e-b146-4738-b2f7-7f27f46e18f9)


### Key Learnings
- Utilization of S3: Understanding how to store and manage datasets using S3 buckets.
- Integration with QuickSight: Connecting S3 data to QuickSight for seamless visualization.
- Visualization Techniques: Learning to create meaningful charts and graphs to derive insights from data.
Dashboard Publication: Exporting the final dashboard as a PDF for sharing and future reference.

### Conclusion
This project showcases the power of Amazon QuickSight in visualizing data stored on AWS S3. By following these steps, users can effectively analyze datasets and create compelling visual narratives through interactive dashboards.

