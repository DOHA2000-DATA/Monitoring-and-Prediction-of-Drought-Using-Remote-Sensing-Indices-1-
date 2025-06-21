
🌍 Drought Monitoring in Tigrigra Watershed Using Remote Sensing, GIS, and AI
📌 Project Overview

This project presents a comprehensive drought monitoring system for the Tigrigra watershed over a 20-year period (2000–2022) using Landsat 5, 7, and 8 imagery, remote sensing indices, and artificial intelligence (AI) models integrated with a Geographic Information System (GIS) environment.

The system is designed to evaluate the spatial and temporal patterns of drought based on key environmental indices such as:

    🌧️ Standardized Precipitation Index (SPI)

    🌿 Vegetation Condition Index (VCI)

    🌡️ Temperature Condition Index (TCI)

    🛰️ Vegetation Health Index (VHI)

🎯 Objectives

    Develop a GIS-based spatiotemporal drought monitoring framework.

    Integrate AI models to enhance drought detection accuracy.

    Analyze seasonal and annual drought patterns from 2000 to 2022.

    Predict future drought conditions using historical patterns and indicators.

🗂️ Dataset Description

    Satellite Data:

        Landsat 5 (TM), Landsat 7 (ETM+), Landsat 8 (OLI/TIRS)

        Time Period: 2000–2022

        Seasonal composites (Spring, Summer, Autumn, Winter)

    Drought Indices:

        SPI: Based on precipitation time series

        VCI & TCI: Derived from NDVI and LST respectively

        VHI: Combination of VCI and TCI

📊 Key Findings

    Severe to extreme drought events occurred in the years:
    2003, 2006, 2007, 2008, 2012, 2016, 2019, and 2021.

    VCI: Only 20% of the area is drought-free.

    TCI: Drought affects 50% of the northeastern area.

    VHI: Drought affects 70% of the northeastern area.

    Final Drought Map:

        Southeast and southwest → Extreme/severe drought.

        Northeast and northwest → Low to no drought conditions.

    Predicted Trends: Southern zones remain most vulnerable in the future.

🛠️ Technologies Used

    Python (NumPy, pandas, scikit-learn, matplotlib)

    Google Earth Engine (GEE) for satellite image processing

    QGIS / ArcGIS for spatial analysis and mapping

    PostgreSQL + PostGIS for geospatial database management

    Machine Learning Models (e.g., Random Forest, SVM)

📂 Project Structure

📁 drought-monitoring-tigrigra/
├── 📁 data/                     # Preprocessed and raw remote sensing data
├── 📁 scripts/                  # Python scripts and Jupyter notebooks
├── 📁 models/                   # Trained AI models and evaluation metrics
├── 📁 maps/                     # Output maps and visualizations
├── 📁 docs/                     # Documentation and reports
├── README.md                   # Project description
└── requirements.txt            # Python dependencies

🚀 Getting Started
🔧 Requirements

    Python 3.8+

    QGIS or ArcGIS (optional for map visualization)

    Google Earth Engine account (if using GEE scripts)

✅ Installation

git clone https://github.com/votre-utilisateur/drought-monitoring-tigrigra.git
cd drought-monitoring-tigrigra
pip install -r requirements.txt

🧠 Model Training & Evaluation

To train the AI model and generate drought prediction maps:

python scripts/train_model.py
python scripts/generate_drought_maps.py

🗺️ Results

The results include georeferenced drought maps, temporal drought trends, and risk zones for future events. These outputs can be used by local authorities, NGOs, or researchers for planning and decision-making.
🤝 Contributing

Feel free to fork the repository, improve the code, and submit a pull request.
📄 License

MIT License. See LICENSE for more information.
🙋 Contact

For any inquiries or collaboration requests, please contact:
[IDRISSI MOUNADI DOHA] – Lead Researcher
📧 idrissimounadidoha@gmail.com
https://www.linkedin.com/in/doha-idrissi-mounadi-68b9801a4/
