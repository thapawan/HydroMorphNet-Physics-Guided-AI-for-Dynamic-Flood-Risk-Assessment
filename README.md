🌟 Overview
HydroMorphNet is a groundbreaking framework that revolutionizes flood risk assessment in complex fluvial environments. By merging advanced deep learning techniques with physically-based hydraulic modeling, it offers unparalleled accuracy and dynamic insights into flood propagation and localized risk. This project aims to provide a robust, scalable, and operationally viable tool for hydrologists, urban planners, and disaster management agencies.

✨ Key Features & Innovations
Superior Meander Classification: Achieves a remarkable 86.7% classification accuracy for meander segments, significantly outperforming conventional deep learning approaches. This precision is driven by a novel hybrid architecture combining a Geometric Attention Transformer with 3D Convolutional Blocks.

Physics-Informed Hydraulic Modeling: Integrates a differentiable hydraulic model capable of dynamically predicting Manning's roughness coefficients based on deep learning-derived meander classifications.

Reduced Prediction Errors:

Substantial 27% reduction in discharge estimation errors.

Significant 34.5% reduction in inundation extent errors compared to static models and FEMA's HAZUS models.

Critical Geomorphological Insights:

Reveals low-sinuosity reaches facilitate 22% faster flood wave propagation.

Identifies compound meanders as localized flood risk hotspots with 45% higher risk due to flow deceleration and sediment deposition.

Uncertainty Quantification: Incorporates Monte Carlo dropout layers to provide robust confidence intervals for flood predictions, enhancing decision-making reliability.

Open-Source & Accessible: Available as an open-source QGIS plugin for practical implementation by agencies like FEMA for levee certification and adaptive floodplain management.

⚙️ How it Works (High-Level)
HydroMorphNet operates by:

Processing multi-temporal Sentinel-1 SAR imagery and derived geometric parameters (e.g., sinuosity, NCMI) through its hybrid deep learning architecture.

Classifying meander segments, with the deep learning output dynamically informing the Manning's roughness coefficients in a differentiable hydraulic model.

Simulating flood propagation using the physics-constrained hydraulic model.

Integrating hydraulic outputs with various geospatial factors (e.g., land cover, soil permeability, historical flood frequency) and climate projections for comprehensive flood risk mapping.

🚀 Installation & Usage
Detailed installation instructions and usage examples will be provided soon. As an open-source QGIS plugin, it will offer straightforward integration into existing geospatial workflows.

🤝 Contributing
We welcome contributions from the community! Please refer to our CONTRIBUTING.md for guidelines on how to get involved.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

📧 Contact
For any inquiries or collaborations, please contact the lead authors:

Pawan Thapa

Lisa Davis

Amobichukwu Amanambu

Leah Mungai

Department of Geography & the Environment, University of Alabama
