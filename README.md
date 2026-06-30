# Medical Image Segmentation Dataset

This repository contains a curated dataset of original medical images along with their corresponding binary segmentation masks, split into benign and malignant cases.

---

## 1. Benign Dataset Folder

This folder contains the original benign medical images along with their corresponding binary segmentation masks. 

| Patient / Case ID | Original Image (`.jpg`) | Segmentation Mask (`.png`) | Description / Notes |
| :--- | :--- | :--- | :--- |
| **Case 01** | `benign 1.jpg` | `mask 1.png` | Benign lesion sample 1 with corresponding mask. |
| **Case 02** | `benign 2.jpg` | `mask 2.png` | Benign lesion sample 2 with corresponding mask. |
| **Case 03** | `benign 3.jpg` | `mask 3.png` | Benign lesion sample 3 with corresponding mask. |
| **Case 04** | `benign 4.jpg` | `mask 4.png` | Benign lesion sample 4 with corresponding mask. |
| **Case 05** | `benign 5.jpg` | `mask 5.png` | Benign lesion sample 5 with corresponding mask. |
| **Case 06** | `benign 6.jpg` | `mask 6.png` | Benign lesion sample 6 with corresponding mask. |
| **Case 07** | `benign 7.jpg` | `mask 7.png` | Benign lesion sample 7 with corresponding mask. |

---

## 2. Malignant Dataset Folder

This folder contains the original malignant medical images along with their corresponding binary segmentation masks as shown in image_482a7f.png.

| Patient / Case ID | Original Image (`.jpg`) | Segmentation Mask (`.png`) | Description / Notes |
| :--- | :--- | :--- | :--- |
| **Case 01** | `malignant 1.jpg` | `mask malignant 1.png` | Malignant lesion sample 1 with corresponding mask. |
| **Case 02** | `malignant 2.jpg` | `mask malignant 2.png` | Malignant lesion sample 2 with corresponding mask. |
| **Case 03** | `malignant 3.jpg` | `mask malignant 3.png` | Malignant lesion sample 3 with corresponding mask. |
| **Case 04** | `malignant 4.jpg` | `mask malignant 4.png` | Malignant lesion sample 4 with corresponding mask. |

---

## Dataset Specifications

* **Total Image Pairs:** 11 cases (22 total medical imaging files).
  * **Benign:** 7 cases (14 files)
  * **Malignant:** 4 cases (8 files)
* **Format:** Original imaging features are stored in `.jpg` format; ground truth segmentation boundaries are stored in `.png` format.
* **Purpose:** Built for evaluating, training, or validating computer vision and semantic segmentation models on clinical cases.

---
## 🤝 Acknowledgments

The authors gratefully acknowledge **Dr. Shahabuddin Siddiqui** (Advanced Diagnostic Center and Advanced International Hospital, Islamabad, Pakistan) for his generous contribution in providing and annotating the clinical test dataset.

---
## Citation Required

If you utilize this dataset, its underlying images, or associated architectures in your research, publications, or projects, you are requested to cite the following publication:

### APA 7 Format
Hafeez, Y., Memon, K., AL-Quraishi, M. S., Yahya, N., Elferik, S., & Ali, S. S. A. (2025). Explainable AI in Diagnostic Radiology for Neurological Disorders: A Systematic Review, and What Doctors Think About It. *Diagnostics*, *15*(2), 168. https://doi.org/10.3390/diagnostics15020168

### BibTeX Format
```bibtex
@article{hafeez2025explainable,
  title   = {Explainable AI in Diagnostic Radiology for Neurological Disorders: A Systematic Review, and What Doctors Think About It},
  author  = {Hafeez, Yasir and Memon, Khuhed and AL-Quraishi, Maged S. and Yahya, Norashikin and Elferik, Sami and Ali, Syed Saad Azhar},
  journal = {Diagnostics},
  volume  = {15},
  number  = {2},
  pages   = {168},
  year    = {2025},
  publisher={MDPI},
  doi     = {10.3390/diagnostics15020168},
  url     = {[https://www.mdpi.com/2075-4418/15/2/168](https://www.mdpi.com/2075-4418/15/2/168)}
}

