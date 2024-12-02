### **Face Detection and Influencer Performance Analysis**

This project processes video datasets to detect faces, identify unique influencers, and analyze their performance metrics. It automates influencer selection using a data-driven approach.

---

### **Features**
1. Detects faces in video datasets using **RetinaFace**.
2. Clusters faces to identify unique influencers.
3. Calculates average performance metrics for influencers.

---

### **Tech Stack**
- **Python**
- **RetinaFace** for face detection
- **NumPy**, **pandas** for data processing
- **Scikit-learn** for clustering

---

### **Usage**
1. **Run Face Detection**: Processes video files and extracts faces.
2. **Cluster Faces**: Groups similar faces to remove duplicates.
3. **Analyze Performance**: Links unique influencers to performance data.

---

### **Setup**
1. Clone the repository:  
   ```bash
   git clone https://github.com/corazon71/InfluencerFinder.git
   cd InfluencerFinder
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:  
   ```bash
   python main.py
   ```

---

### **Outputs**
- **Extracted Faces**: Stored in the `faces` directory.
- **Unique Influencers**: Results in a summary table with performance metrics.

---
