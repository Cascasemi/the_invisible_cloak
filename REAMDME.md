# 🧥 Invisibility Cloak with OpenCV  

This project recreates the **Harry Potter–style invisibility cloak** effect using **Python + OpenCV**.  
It detects a chosen color (red by default) and replaces it with the captured background — making the cloak (and wearer) vanish in real time.  

---

## ⚙️ How It Works
1. **Capture Background** – Records a few frames without the user.  
2. **Convert to HSV** – Easier for color detection than RGB.  
3. **Detect Cloak Color** – Creates masks for red regions.  
4. **Remove Noise** – Cleans false detections with morphological operations.  
5. **Blend Frames** – Cloak area is replaced with background.  
6. **Display Output** – Shows the invisibility effect live.  

---

## 📦 Requirements
- Python 3.7+  
- OpenCV  
- NumPy  

Install dependencies:
```bash
pip install opencv-python numpy
