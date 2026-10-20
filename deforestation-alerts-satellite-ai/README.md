# 🌳 Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery and AI

<p align="center">
  <b>A Machine Learning Case Study on Deforestation Driver Classification</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Random%20Forest-orange?style=for-the-badge" alt="Machine Learning">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
</p>

## 🌏 Overview

Deforestation alerts help identify areas where forest loss may be occurring. However, identifying an alert is only one step; understanding the direct drivers behind deforestation is also important for environmental monitoring and decision-making.

This project is a learning implementation inspired by the webinar **“Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery and AI.”** The topic explores how satellite imagery and Artificial Intelligence (AI) can support the attribution of direct drivers to deforestation alerts.

The implementation demonstrates a basic Machine Learning classification workflow using a Random Forest model, evaluation metrics, data visualizations, and an interactive map.

**Important:** This notebook uses synthetic data and simulated coordinates. It does not process actual satellite imagery or identify real deforestation alerts. Therefore, it is a simplified educational demonstration rather than a reproduction of the speaker's research.

## 🎯 Objectives

- Understand the concept of attributing direct drivers to deforestation alerts.
- Demonstrate a basic classification workflow using Machine Learning.
- Evaluate model predictions using classification metrics.
- Visualize category distributions and model performance.
- Display simulated locations on an interactive map.

## 🧠 Implementation Method

The notebook uses a Random Forest Classifier to classify simulated indicators into four illustrative categories:

| Category | Description |
|---|---|
| Agriculture | Simulated indicators associated with agricultural activity |
| Road Development | Simulated indicators associated with road development |
| Mining | Simulated indicators associated with mining activity |
| Fire | Simulated indicators associated with elevated heat and vegetation change |

The input features are vegetation-change indicators, road-activity indicators, and heat indicators. These are artificially generated for demonstration and are not measurements extracted from satellite imagery.

## ⚙️ Workflow

1. Generate a synthetic dataset.
2. Split the dataset into training and testing sets.
3. Train a Random Forest classification model.
4. Predict categories for the test data and a new sample.
5. Evaluate predictions using accuracy, precision, recall, and F1-score.
6. Visualize the results through charts and an interactive map.

## 📊 Visualizations

The notebook includes:

- **Category Distribution:** Displays the number of samples in each simulated category.
- **Confusion Matrix:** Compares simulated ground-truth labels with model predictions.
- **Classification Metrics:** Compares precision, recall, and F1-score.
- **ROC Curve:** Illustrates class-discrimination performance using AUC.
- **Feature Importance:** Shows the relative importance of model input features.
- **Interactive Map:** Displays simulated locations with different colors for each category.

## 🛠️ Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Folium

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a notebook named `deforestation_alerts_satellite_ai.ipynb`.
3. Copy the implementation code into the notebook in the correct order.
4. Run each cell from top to bottom.
5. Review the model evaluation results, visualizations, predictions, and interactive map.

## ⚠️ Limitations

- The dataset is synthetic, not derived from satellite imagery.
- The model has not been validated using real deforestation alerts.
- The simulated map does not represent actual deforestation locations.
- Evaluation metrics reflect performance on the generated dataset only.

## 🔭 Future Development

The project could be extended by integrating Sentinel-1 and Sentinel-2 imagery, verified labels for deforestation drivers, image-based classification using Convolutional Neural Networks (CNNs), and real geospatial data. Independent testing and field validation would also be necessary to assess real-world performance.

## 📚 Webinar Reference

**Topic:** *Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery and AI*  
**Speaker:** Dr. Bart Slater — Wageningen University & Research, Netherlands.

---

<p align="center">
  🌱 <i>Exploring how AI can support the understanding of deforestation drivers.</i>
</p>
