# 🖼 Interactive CLAHE Enhancement of an Orthodox Icon

> **Computer Vision • Digital Art History • OpenCV • Jupyter Notebook**

An interactive Jupyter Notebook demonstrating how **Contrast Limited Adaptive Histogram Equalization (CLAHE)** can enhance the visibility of details in an Orthodox icon while preserving its original colour appearance.

---

## Project Overview

This project presents an interactive workflow for applying **Contrast Limited Adaptive Histogram Equalization (CLAHE)** to an Orthodox icon using Python and OpenCV.

Unlike many introductory image processing examples based on generic photographs, this notebook applies Computer Vision techniques to a documented nineteenth-century Orthodox icon. The project combines image enhancement, histogram analysis, interactive parameter exploration and art-historical context into a single educational resource.

The notebook was developed as part of the author's continuing work in **Digital Art History**, demonstrating how modern Computer Vision techniques can support the study of cultural heritage.

---

## Why this Project?

The primary objective of this project is to demonstrate that Computer Vision techniques can support the visual examination of artworks without altering their artistic character.

Rather than interpreting the icon, the notebook illustrates how digital image enhancement can reveal subtle visual information that may otherwise remain difficult to observe.

This project also serves as an educational introduction to:

- Computer Vision
- OpenCV
- CLAHE
- LAB colour space
- Histogram analysis
- Interactive image processing
- Digital Art History

---

## Main Features

- Interactive image upload
- Image property inspection
- RGB → LAB colour space conversion
- Individual channel visualisation
- CLAHE enhancement
- Image reconstruction
- Histogram generation
- Histogram comparison
- Interactive CLAHE parameter adjustment
- Discussion of results
- Educational explanations throughout the notebook

---

## Workflow

```text
Upload Image
      │
      ▼
Image Properties
      │
      ▼
LAB Colour Space
      │
      ▼
Channel Separation
      │
      ▼
CLAHE Enhancement
      │
      ▼
Image Reconstruction
      │
      ▼
Histogram Analysis
      │
      ▼
Interactive Exploration
      │
      ▼
Discussion & Conclusion
```

---

## Example Result

The comparison below illustrates the visual effect obtained after applying CLAHE to the Lightness channel.

<p align="center">

<img src="images/before_after.png" width="900">

</p>

---

## Repository Structure

```text
.
├── README.md
├── Interactive_CLAHE_Orthodox_Icon.ipynb
├── requirements.txt
├── LICENSE
└── images
    ├── icon.jpg
    ├── before_after.png
    └── clahe_demo.gif
```

---

## Study Image

The notebook uses a nineteenth-century Orthodox icon as a case study.

| Property | Description |
|----------|-------------|
| **Title** | *Saint John the Baptist* |
| **Artist** | Ivan Dospevski |
| **Year** | 1867 |
| **Dimensions** | 122 × 83 cm |
| **Location** | Church of St. Demetrius, Kyustendil, Bulgaria |

The photograph was taken by the author during doctoral research in Art History.

Permission for photography was granted by the local representatives of the Bulgarian Orthodox Church.

The image is included exclusively for educational and scientific purposes.
