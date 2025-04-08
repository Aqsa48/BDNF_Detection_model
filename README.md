# Project Introduction: BDNF Detection from Images

**Objective:**  
Brain-Derived Neurotrophic Factor (BDNF) plays a critical role in neurodevelopment, synaptic plasticity, and cognitive function. Altered BDNF expression is associated with neurological disorders such as depression, Alzheimer's, and schizophrenia. This project aims to detect and analyze BDNF expression from biological brain images using machine learning techniques, particularly image-based deep learning models.

**Goal:**  
Build an AI-driven system that can automatically detect BDNF expression in microscopy or brain scan images and assist researchers in identifying expression patterns.

---

## Data Gathering: Public Image Sources

### 1.  Allen Brain Atlas  
- **Website:** [https://mouse.brain-map.org](https://mouse.brain-map.org)  
- **Usage:**  
  - A powerful resource for mouse brain research.
  - You can download **immunostained brain images**.
  - Filter specifically by gene: **BDNF**.
  - Includes high-resolution sagittal and coronal brain slices.

---

### 2. GEO Datasets (NCBI)
- **Website:** [https://www.ncbi.nlm.nih.gov/geo/](https://www.ncbi.nlm.nih.gov/geo/)  
- **Usage:**  
  - A repository of gene expression and image datasets.
  - Use search terms like: `BDNF brain mouse image`.
  - Might require parsing image data from supplementary files or related experiments.

---

## 3. The Cancer Imaging Archive (TCIA)
- **Website:** [https://www.cancerimagingarchive.net/](https://www.cancerimagingarchive.net/)  
- **Usage:**  
  - Primarily focused on cancer and MRI/CT scans.
  - While not BDNF-specific, could be used to **simulate detection models** or pretrain on structural brain data.

---

## 4. Additional Repositories: Zenodo / Kaggle / Figshare

### 🔎 Zenodo
- **Search:** “BDNF” or “brain immunohistochemistry”
- Often contains raw research data, including images, from published papers.

### 5. Kaggle
- **Search:** `BDNF brain` or related neuroscience datasets.
- Kaggle notebooks and datasets may help with preprocessing or transfer learning.

### 6. Figshare
- Another academic repository to search for BDNF-labeled images or histology slides.

---

**Note:** Most image data will be in formats like `.tiff`, `.png`, or `.jpeg`, and may require standardization for model training. Be sure to check licensing for academic or commercial use.

