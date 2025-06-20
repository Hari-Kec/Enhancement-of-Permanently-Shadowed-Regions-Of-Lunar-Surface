
# 🌘 Enhancement of Permanently Shadowed Regions on the Lunar Surface

This project focuses on enhancing images of **Permanently Shadowed Regions (PSRs)** on the Moon using advanced image processing techniques. These regions, located near lunar poles, are never exposed to direct sunlight and are critical for exploration due to the possible presence of water ice.

---

## 🛰️ Project Overview

* Enhances visibility and contrast in lunar PSRs using digital techniques.
* Aims to support scientific analysis and navigation in low-illumination zones.
* Uses Python with OpenCV, NumPy, and matplotlib inside Jupyter Notebook.
* Built with research applicability in remote sensing and planetary science.

---

## 🧠 Key Features

* 📷 Input: Raw grayscale or RGB images of PSRs captured from satellite missions.
* ⚙️ Techniques Applied:

  * Histogram Equalization
  * CLAHE (Contrast Limited Adaptive Histogram Equalization)
  * Gamma Correction
  * Log Transformation
  * Sharpening Filters
* 📈 Visualization: Before & After comparisons of enhanced images
* 🗺️ Use Case: Improving visual clarity in navigation and terrain analysis for lunar missions

---

## 📁 Project Structure

```
PSR_Enhancement/
├── Image_Enhancement.ipynb    # Main notebook with all preprocessing + enhancement
├── input/                     # Folder for original lunar PSR images
├── output/                    # Folder for storing enhanced results
└── README.md
```

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://Hari-Kec/Enhancement-of-Permanently-Shadowed-Regions-Of-Lunar-Surface.git
cd Enhancement-of-Permanently-Shadowed-Regions-Of-Lunar-Surface
```

### 2. Install Dependencies

```bash
pip install opencv-python numpy matplotlib
```

### 3. Run the Notebook

Use Jupyter Notebook or VS Code to open and run:

```bash
jupyter notebook Image_Enhancement.ipynb
```

---

## 📊 Sample Techniques Used

### CLAHE Example

```python
clahe = cv2.createCLAHE(clipLimit=2.0, tileGridSize=(8,8))
enhanced = clahe.apply(gray_image)
```

### Gamma Correction Example

```python
gamma_corrected = np.array(255*(image / 255) ** gamma, dtype='uint8')
```

---

## 🌌 Applications

* NASA/ISRO lunar exploration missions
* Navigation planning in shadowed regions
* Automatic crater detection enhancement
* Preprocessing pipeline for ML models on lunar terrain

---

## 📜 License

```
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy...
```

---

## 👨‍💻 Author

**Hari S.**
For project inquiries, contact: `harisenthilcbe@gmail.com`

---

Let me know if you'd like to:

* Add output visuals or sample data to the repo
* Deploy as a Streamlit/Gradio web tool
* Include citations to scientific papers used

To View the code get access at 
[Google Colab](https://colab.research.google.com/drive/12VNlmFnPRTlXuXZA50s2dukXuLfvXENH?usp=sharing)
