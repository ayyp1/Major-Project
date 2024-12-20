
# 🎓 Major Project: A Deep Learning Based Human Activity Recognition Using Wi-Fi Signals

This repository contains the materials for the final year project on Human Activity Recognition using Wi-Fi signals. The project involves preprocessing Channel State Information (CSI) signals collected from Raspberry Pi and visualizing the data to recognize different human activities.

## Project Workflow

The project is divided into key components:
- **Hardware**: Integrating Hardware components necessary for data collection.
- **Data Collection**: Collecting CSI data using Raspberry Pi(Rx) and Router(Tx) and visualizing the collected data in real-time.
- **Preprocessing**: Filtering and transforming the CSI data.
- **Feature Extraction and Annotation**: Extracting relevant features from the preprocessed data and annotating the data for training.
- **Model Training**: Developing a machine learning model architecture and training the model to recognize different human activities.
- **Visualization**: Visualizing the CSI data and the results of the different activity recognition.

    ```mermaid
    graph TD
        A[Hardware: Integrating Hardware Components] --> B[Data Collection: Collecting CSI data]
        B --> C[Preprocessing: Filtering and transforming the CSI data]
        C --> D[Feature Extraction and Annotation]
        D --> E[Model Training: Developing and Training ML Model]
        E --> F[Visualization: Visualizing CSI Data and Recognition Results]
    ```
---

## Repository Structure

- [Main-Reference-Papers](./Main%20Reference%20Papers/)
  - These are the main papers from which we based our project on.
- [Literature-Review-Papers](./Literature%20Review/)
  - These are the papers to be included in literature review and references.
- [Reports](./Reports/)
  - These are the project reports and presentation for our project.
- [Implementation](./Implementation/)
  - These are the ongoing project implementations.