# Summer-Internship 1

## Introduction

Welcome to my exploration of image processing in Geographic Information Systems (GIS) using machine learning, deep learning, and artificial intelligence (ML/DL/AI)! This blog-style chronicles my journey from the fundamentals of QGIS to leveraging advanced AI techniques for extracting meaningful insights from geospatial imagery. Feel free to follow along and learn alongside me as I tackle challenges, explore new concepts, and unlock the potential of AI-powered image processing in GIS!

### May 16th, 2024

Registration Process and Installation of QGIS: Today marked the exciting beginning of my QGIS adventure! I embarked on the smooth registration process and successfully installed QGIS on my system. I'm eager to dive into its powerful geospatial capabilities.

### May 17th, 2024

Dataset Acquisition and Exploration: I ventured into the vast world of geospatial data by downloading a dataset from the USGS (United States Geological Survey). Next, I imported these layers into QGIS. This initial exploration allowed me to become familiar with the data structure and visualize its potential for further analysis.

### May 18th, 2024

Image Classification Delve: Today, I delved into the fascinating realm of image classification using QGIS. This technique enables extracting meaningful information from images, such as identifying land cover types or object detection. Experimenting with various classification algorithms within QGIS helped me understand their capabilities.

### May 20th, 2024

Vectorization and QGIS Expansion: I focused on converting raster layers (grid-based data) into the more versatile vector format (points, lines, and polygons) within QGIS. This transformation allows for richer spatial analysis and manipulation. Additionally, I explored other features of QGIS to further broaden my expertise in the software.

### May 21st, 2024

Canny Edge Detection Mastery: The world of edge detection piqued my interest today. I delved into the Canny edge detection algorithm, which is a robust technique for extracting edges from images. By meticulously documenting the procedural steps, I solidified my understanding for future reference.

### May 22nd, 2024

Roboflow Integration and Farm Boundary Detection: Today's challenge involved leveraging Roboflow, a powerful platform for image annotation. I meticulously annotated images to train a model for automatically detecting farm boundaries within QGIS. This marks a significant step towards automating analysis tasks!

### May 23rd, 2024

Deep Dive into Edge Detection: I sought to refine my understanding of farm boundary detection by studying various research papers on Canny edge detection and alternative edge detection methods. This exploration aimed to identify the most efficient technique for extracting precise farm boundaries in my specific dataset.

### May 28th, 2024

Manual Farm Boundary Delineation and Image Segmentation: Recognizing the importance of accurate training data, I meticulously created farm boundaries by hand. Next, I segmented the image into smaller portions to feed these labeled segments into the model for effective training.

### May 29th, 2024

Crop Growth Monitoring with NDVI: I ventured into the world of crop health assessment by learning about the Normalized Difference Vegetation Index (NDVI). By applying NDVI calculations to satellite imagery, I gained insights into the various stages of crop growth, specifically focusing on Bajra (pearl millet) in this instance.

### May 30th, 2024

Exploring Google Earth Engine (GEE): Today, I broadened my horizons by exploring Google Earth Engine (GEE), a cloud-based platform for geospatial analysis. This powerful tool offers vast datasets and processing capabilities, opening up exciting possibilities for future projects.

### May 31st, 2024

Literature Review on NDVI and Crop Growth Stages: To deepen my understanding of NDVI, I conducted a thorough literature review. This research focused on how NDVI values can be used to identify and monitor specific stages in the growth cycle of crops, like Bajra.

### June 3rd, 2024

Calculating NDVI for Specific Crop Growth Stages: Today, I put my NDVI knowledge into practice! I focused on calculating NDVI values for the Bajra crop within a specific range corresponding to its various growth stages. This analysis allows me to identify areas within the image where the crop is at a particular stage of development.

### June 4th, 2024

NDVI Analysis for Bajra Crop in GEE: I leveraged the power of Google Earth Engine (GEE) to analyze the NDVI values I calculated for the Bajra crop. GEE's visualization capabilities allowed me to create maps and identify spatial patterns in crop growth across the image.

### June 5th, 2024

Literature Review on Building Height from Images: My exploration expanded beyond agriculture today. I conducted a literature review on techniques for determining building height from images. This research opens doors to potential future projects in urban analysis or 3D reconstruction.

### June 6th, 2024

Literature Review on Research Papers: Today, I delved deeper into the world of research by reviewing various papers related to geospatial analysis. This broader exploration keeps me up-to-date on the latest advancements and helps me identify new areas of interest within the field.

### June 7th, 2024

Reading on Building Height Measurement: I continued my exploration of building height measurement from images. Immersing myself in technical articles, journals, and research papers equipped me with a more comprehensive understanding of the algorithms and techniques involved.

### June 10th, 2024

Gathering Datasets and GEE Troubleshooting: Data acquisition is crucial! Today, I focused on collecting suitable datasets from various sources for building height measurement analysis. Additionally, I encountered some challenges while working with GEE. By troubleshooting these errors, I gained valuable problem-solving skills within the platform.

### June 11th, 2024

Training Model for Height Measurement and Error Correction: I put my learnings on building height measurement into action! I focused on training a model using the gathered datasets within GEE or a suitable software environment. Addressing the errors encountered previously ensured a smoother training process.

### June 12th, 2024

Calculating NDVI in QGIS and Error Resolution: I revisited NDVI calculations! Today, I imported a TIF file (Tagged Image File Format) acquired from GEE into QGIS. I then performed NDVI calculations on this data. As with GEE, I encountered some errors, but by troubleshooting them, I refined my ability to analyze NDVI data within QGIS.

### June 13th, 2024

Research Paper Exploration: Today, I continued my journey of knowledge acquisition by delving deeper into research papers. Focusing on topics relevant to geospatial analysis and potentially related to building height measurement or other areas of interest kept me up-to-date and sparked new ideas.

### June 14th, 2024

Data Wrangling for Training: Building a custom model requires proper data preparation! Today, I concentrated on downloading and uploading relevant datasets for training purposes. This might involve data from various sources or specific formats needed by the chosen modeling environment.

### June 15th, 2024

Colab Troubleshooting: I encountered errors during the training process within Google Colab, a popular platform for cloud-based machine learning. By tackling these errors effectively, I ensured the smooth training of my custom model. Common errors might involve missing libraries, incorrect data paths, or issues with the model architecture itself.

### June 18th, 2024

Data Organization and Error Correction: Data preparation is crucial for machine learning! Today, I focused on transforming the downloaded data into a format suitable for training my custom model. This might involve creating Comma-Separated Values (CSV) files, cleaning and organizing the data, or addressing any formatting inconsistencies.

### June 19th, 2024

Manual Data Collection from QGIS: Sometimes, readily available datasets might not be sufficient. Today, I leveraged the capabilities of QGIS to manually collect data for training my custom model. This could involve extracting specific features from imagery or manually labeling objects of interest within QGIS.

### June 20th, 2024

Research Deep Dive: Height Detection Techniques: With a focus on building height detection, I reviewed additional research papers today. This exploration exposed me to various algorithms and approaches, allowing me to compare their effectiveness and identify the most suitable technique for my project.

### June 21st, 2024

Shadow-Based Height Estimation: Today, I implemented a creative approach for building height estimation! This technique involved:

Thresholding the image: Simplifying the image by converting pixels 	 exceeding a certain brightness value to white and the rest to black.

Contour detection: Identifying the outlines of building shadows within the thresholded image.

Shadow length measurement: Calculating the length of the detected building shadow.

Trigonometric height calculation: Utilizing the shadow length, sun angle (potentially obtained from external sources), and pixel size to estimate the building height using trigonometry.

This method offers an alternative approach to building height measurement, and its suitability depends on various factors like image quality and sun angle information availability.

### June 24th, 2024

LiDAR Data Exploration: Today's focus shifted towards LiDAR (Light Detection and Ranging) data, a powerful tool for measuring precise elevations. I explored various resources to find and download suitable LiDAR datasets relevant to my area of interest. These datasets can be used in conjunction with other geospatial data for more accurate building height calculations.

### June 25th, 2024

Tree Detection Model Training: The exploration expanded beyond buildings today! I trained a model for detecting trees within imagery. This could involve various techniques like supervised learning with labeled datasets or unsupervised learning approaches depending on the chosen model and available data. Testing the model's performance allows for evaluation and potential refinement.

### June 26th, 2024

Tree Detection Research Paper: Knowledge sharing is important! Today, I focused on writing a research paper on the topic of tree detection. This could involve documenting your approach, methodology, results, and potential applications. Sharing your research can contribute to the advancement of the field and inspire others.

### June 27th, 2024

Height Detection Research Deep Dive: Today, I delved deeper into research papers on building height detection. This exploration might involve focusing on specific algorithms, comparing different approaches, or evaluating the latest advancements in the field. This ongoing research keeps you informed about the best techniques for your project.

### June 28th, 2024

LiDAR Data Processing Exploration: LiDAR data holds immense potential for height measurements. Today, I concentrated on researching LiDAR datasets and how to process them effectively. This might involve understanding different LiDAR file formats, exploring available software options for processing, and familiarizing yourself with common filtering and analysis techniques.

### July 1st, 2024

Tree Detection Paper and Spatiotemporal Analysis: Multi-temporal analysis allows for studying changes over time. Today, I:
Finalized the tree detection research paper: This paper likely documented your approach, methodology, results, and potential applications of your tree detection model. Sharing your research advances the field.
Sought past year's geospatial data: Obtaining historical data allows for analyzing changes in tree cover or other features of interest over time. This data could be from similar sources as your recent data or from historical archives.

### July 2nd, 2024

LiDAR Data Format Conversion: Today, I tackled LiDAR data processing! A crucial step might involve converting the data from its original format (e.g., .pcd) to a format compatible with your chosen processing software (e.g., .pcl). This ensures successful import and manipulation of the LiDAR data.

### July 3rd, 2024

LiDAR Processing Techniques: The power of LiDAR lies in its detailed elevation information. Today, I explored various approaches to process the LiDAR dataset. This could involve techniques like filtering noise points, classifying ground points from vegetation points, or extracting building footprints from the LiDAR data. The specific techniques chosen will depend on your project goals.

### During my internship, I embarked on a dual learning path, delving into both the exciting world of geospatial image processing and the foundations of data science and machine learning. Overall, the internship was instrumental in solidifying my understanding of data science, machine learning, and their applications in both text summarization and geospatial image processing. The experience provided a strong foundation for further exploration and the potential to contribute to advancements in these rapidly evolving fields.

# !!!!!!!  Thank You.  !!!!!!!
