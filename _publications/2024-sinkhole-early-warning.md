---
title: "Multi-modal Sinkhole Early Warning System using Deep Learning and XAI"
collection: publications
permalink: /publication/2024-sinkhole-early-warning
excerpt: 'Developing an AI-driven hazard forecasting pipeline by integrating satellite telemetry and hydrologic data.'
date: 2024-10-01
venue: 'Independent Research'
paperurl: ''
citation: 'Ra Lan Do Tu Trinh. (2024). "Multi-modal Sinkhole Early Warning System." Independent Research Project.'
---

### Abstract
This research addresses the critical challenge of sinkhole hazard mitigation by developing a Multi-modal AI pipeline. The system integrates heterogeneous data sources, including satellite telemetry and karst-hydrologic temporal data, to provide early warnings.

### Key Contributions
* **Architecture**: Implemented **LSTM and GRU architectures** to process time-series data, improving predictive accuracy for geological events.
* **Forecasting Horizon**: Extended prediction capabilities to 72-hour (short-term) and sub-seasonal (3-month) hazard forecasting.
* **Interpretability (XAI)**: Utilized **SHAP and LIME** to interpret feature importance, ensuring the model's physical consistency with lithology and rainfall patterns—bridging the gap between "black-box" models and geological principles.
* **Data Fusion**: Engineered a risk assessment framework to process 8+ heterogeneous geological datasets, including InSAR and Remote Sensing data.

### Technical Stack
* **Models**: PyTorch, LSTM, GRU.
* **Explainability**: SHAP, LIME.
* **Geospatial Tools**: ArcGIS, QGIS, Google Earth Engine.
* **Data Sources**: NASA Earth Observation, InSAR data.
