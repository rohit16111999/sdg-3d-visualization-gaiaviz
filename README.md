# United-Nations-Sustainable-Development-Goals-SDG-Explorer-6, 16 & 17  
**DAEN-690-010_Team UN**

---

## Project Overview:
The United Nations Sustainable Development Goals (SDGs), established in 2015, form a comprehensive global framework aimed at addressing critical issues including health, water access, governance, infrastructure, justice, sustainability, and international cooperation. Among these, SDG-6 (Clean Water and Sanitation), SDG-16 (Peace, Justice, and Strong Institutions), and SDG-17 (Partnerships for the Goals) are particularly important due to their interconnected nature and global relevance. The UN maintains a vast and continuously growing dataset to monitor SDG progress, with over 2.7 million records as of 2023. While this data is publicly available in formats like CSV and JSON, its complexity, scale, and multidimensional structure make it challenging to interpret using traditional 2D visualizations.

To address these challenges, this project proposes an alternative approach using **3D visualizations via GaiaViz**. By transforming SDG data into interactive structures, users can explore donor-recipient interactions, track financial and policy connections, and observe indicator-level progress across geographies and timeframes. The goal is to make complex development data more accessible, interpretable, and actionable.

---

## Project Goals:
The primary objective of this project is to enhance understanding and transparency around global SDG implementation. For Spring 2025, the focus was placed on the following indicators:

### SDG-6:
- 6.3.1 – Wastewater treatment  
- 6.3.2 – Ambient water quality  
- 6.5.1 – Integrated water resources management  
- 6.a.1 – Official Development Assistance (ODA) to water and sanitation  

### SDG-16:
- 16.1.1 – Intentional homicides  
- 16.3.2 – Unsentenced detainees  
- 16.5.1 – Bribery incidence  
- 16.6.1 – Government expenditure as a proportion of the approved budget  

### SDG-17:
- 17.3.1 – Foreign direct investment, remittances, and ODA  

---

## 👤 Personal Contributions by Rohit Motdhare:
As part of this team project, I led and contributed extensively to the **spatial and visualization logic**, including:

- 🗺️ **Geo-encoding 195 countries** using **ArcGIS**, aligning datasets with accurate regional boundaries for visualization in GaiaViz  
- 🐍 **Developed custom Python pipelines** for indicator-wise transformation, temporal grouping, and stakeholder role assignment  
- 📊 Structured over **130K nodes and 90K+ links** formatted for GaiaViz, enabling immersive **3D visualizations** across SDG 6, 16, and 17  
- 🎯 Focused on aligning donor-beneficiary relationships with year-specific visual exploration logic  
- 🧩 Worked across the full data pipeline—from raw dataset preprocessing to node/tag generation for **interactive SDG storytelling**  

📌 Shared this experience on LinkedIn: [LinkedIn Post](https://www.linkedin.com/posts/rohit-motdhare_proud-to-share-our-capstone-project-united-activity-7335416904406241282-z97H)

---

## 🔗 Demo and Resources

📽️ **Demo Link**: [https://lnkd.in/ebwsDj7C](https://lnkd.in/ebwsDj7C)  
💻 **Download GaiaViz App**: [https://lnkd.in/egRe2X7y](https://lnkd.in/egRe2X7y)  
🗒️ **User Guide**: [https://lnkd.in/etQdFSUc](https://lnkd.in/etQdFSUc)  
👨‍💻 **Developer Documentation**: [https://lnkd.in/eekVm9uk](https://lnkd.in/eekVm9uk)

---

## Initial Requirements:
To run this project, you'll need to install the following dependencies:

- Python 3.x  
- pandas  
- requests  
- zipfile (Standard Python Library)  
- Jupyter Notebook (optional, for interactive data exploration)

---

## Notebooks:
Jupyter notebooks that handle data cleaning:

- `notebooks/Integrated_Datasets_Indicators.ipynb` – Handles data cleaning, processing, and export across various SDG indicators  
- `notebooks/SDG-6_Global.ipynb` – Global-level processing for SDG-6 including normalization, geolocation, and tag generation  
- `notebooks/SDG-6_EU_US_china.ipynb` – Region-specific processing for the US, EU, and China with role assignments for GaiaViz  
- `notebooks/SDG-16_Global.ipynb` – Full SDG-16 pipeline, normalization, and tagging  
- `notebooks/SDG-6,16,17_Fullcode.ipynb` – Unified processing for SDG 6, 16, and 17 to generate a comprehensive, interactive visualization

---

## Datasets and Templates:
These files serve as both datasets and templates for structuring the visual output:

- `datasets/Dataset_Sorted_by_Indicator.csv` – Combined dataset for SDG-6 and SDG-16, sorted by indicator  
- `datasets/SDG_6_Indicators_Aligned.csv` – Cleaned and aligned dataset for global SDG-6 analysis  
- `datasets/Combined_SDG6_Countries_Data_Corrected.csv` – SDG-6 data filtered for US, EU, and China  
- `datasets/SDG16_Dataset_With_Roles_Updated.csv` – Cleaned and stakeholder role-assigned dataset for SDG-16  
- `datasets/final_dataset_sdg61617_with_roles.csv` – Unified dataset covering SDG 6, 16, and 17 with normalized values and roles  

### Templates:
- `templates/Tag_Template_SDG-6.csv` – Tag configurations for SDG-6 indicators  
- `templates/Tag_Template_SDG-16.csv` – Tag configurations for SDG-16 indicators  
- `templates/np_node-template.csv` – Node schema template for GaiaViz  
- `templates/np_tag-template.csv` – Tag schema template for GaiaViz  
- `templates/colors.csv` – RGB color mapping for SDG indicators to ensure consistency in visualization

---

## 📫 Contact  
**Rohit Motdhare**  
📧 [motdharer1999@gmail.com](mailto:motdharer1999@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/rohit-motdhare) | [GitHub](https://github.com/rohit16111999)
