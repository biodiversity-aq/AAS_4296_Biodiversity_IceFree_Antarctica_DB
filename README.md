# Data Cleaning with OpenRefine – AAS 4296 Biodiversity Ice-Free Antarctica

## 📖 Overview
This repository contains the **raw** and **cleaned** dataset for the **AAS_4296 Biodiversity Ice-Free Antarctica** project. The data cleaning process was performed using [OpenRefine](https://openrefine.org/), ensuring reproducibility through an exported project and transformation steps.

## 📊 Dataset Information
This dataset is part of a study on **biodiversity in ice-free areas of Antarctica**. It is associated with the following data paper:

Terauds, Aleks; Lee, Jasmine R. ; Wauchope, Hannah S.; Raymond, Ben; Bergstrom, Dana; Convey, Peter ; Mason, Claire; Patterson, Charlotte R.; Robinson, Sharon A.; Van de Putte, Anton; Watts, Dave; Chown, Steven L.. 2025 The biodiversity of ice-free Antarctica database [Data paper]. Ecology, 106 (1), e70000. 2, pp. 10.1002/ecy.70000 

## 📂 Repository Structure

```
├── LICENSE
├── README.md
├── data
│   ├── cleaned		# Directory containing cleaned data
│   └── raw			# Directory containing original data
│       
└── openrefine
    ├── AAS_4296_Biodiversity_IceFree_Antarctica_DB.openrefine.tar.gz # Full OpenRefine project
    └── openrefine-operations.json 		# JSON file with transformation steps
```

## 🚀 Reproducibility: How to Apply Cleaning Steps in OpenRefine
To reproduce the data cleaning process, follow these steps:

### **1️⃣ Install OpenRefine**
Download and install OpenRefine from [https://openrefine.org/download.html](https://openrefine.org/download.html).

### **2️⃣ Load the Raw Dataset**
1. Open OpenRefine.
2. Click **"Create Project"** and select the raw dataset: `data/raw/AAS_4296_Biodiversity_IceFree_Antarctica_DB.csv`
3. Click **Next** and adjust any parsing settings as needed.
4. Click **Create Project**.

### **3️⃣ Apply OpenRefine Transformations**
1. Navigate to the **Undo/Redo** tab.
2. Click **"Apply"**.
3. Upload the transformation script: `openrefine/openrefine-operations.json`
4. Click **OK** to apply the cleaning steps.

### **4️⃣ Export the Cleaned Dataset**
1. Once transformations are applied, click **Export**.
2. Save the cleaned dataset as a TSV file (or another format).
3. The cleaned dataset is available in: `data/cleaned/AAS_4296_Biodiversity_IceFree_Antarctica_DB.tsv`


## 📜 Alternative: Load the Full OpenRefine Project
If you want to inspect the project with all changes applied:
1. Open OpenRefine.
2. Go to the **"Manage projects"** page.
3. Click **"Import Project"**.
4. Select: `openrefine/AAS_4296_Biodiversity_IceFree_Antarctica_DB.openrefine.tar.gz`
5. This will restore the OpenRefine project with all cleaning steps.

## 📌 License
This project is licensed under the [MIT License](LICENSE).

---

### ✉️ Need Help?
If you encounter any issues, feel free to open an **issue** or reach out!







