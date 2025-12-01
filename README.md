# TerraVision

**Autonomous Deforestation & Wildfire Detection using Semantic Segmentation**

## Project Description

TerraVision is a research engineering project designed to automatically detect ecological disturbances, such as wildfires and deforestation, based on satellite imagery. The system utilizes Deep Learning (specifically U-Net architectures for semantic segmentation) to generate pixel-level masks of affected areas.

A key focus of this project is Explainable AI (XAI) to ensure transparency in how the model interprets spectral data. The final system is intended to monitor real-time data feeds from NASA, download high-resolution Sentinel-2 imagery, and visualize the analysis results in a web dashboard.

## Planned Features & Roadmap

The project development is divided into the following stages:

1.  **Model Research & Training:** Development of the Deep Learning model using U-Net and ResNet backbones within Jupyter Notebooks.
2.  **Explainable AI:** Implementation of Grad-CAM to visualize and verify the features learned by the model.
3.  **Data Pipeline:** Integration with the NASA EONET API for event triggering and the Microsoft Planetary Computer API for satellite image retrieval.
4.  **Visualization:** Creation of a web-based dashboard (Flask + Leaflet) to display the live analysis and segmentation masks.

## Repository Structure

- `notebooks/`: Contains Jupyter notebooks for data exploration, model training, and XAI evaluation.
- `src/`: Contains the core application logic, API clients, and model definitions.
- `app/`: Contains the web dashboard implementation.
- `data/`: Local storage for datasets (ignored by version control).
