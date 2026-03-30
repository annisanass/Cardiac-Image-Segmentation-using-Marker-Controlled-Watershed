# Cardiac Image Segmentation Using Marker-Controlled Watershed

## Overview

This project explores cardiac image segmentation using the marker-controlled watershed algorithm on CT images. The goal is to accurately extract heart structures such as the left atrium for medical analysis.

## Objectives
- Identify cardiac anatomical structures from medical images
- Implement an accurate segmentation method
- Evaluate segmentation performance
  
## Methodology
- Preprocessing: Grayscale conversion, Gaussian blur
- Edge Detection: Sobel gradient
- Marker Generation: Internal & external markers
- Segmentation: Marker-controlled watershed + morphology
- Post-processing: Visualization & analysis

## Tools
Python, NumPy, SciPy, scikit-image, Matplotlib, pydicom, Google Colab
  
## Results
- Successfully segmented cardiac regions across multiple datasets
- Best performance achieved in early iterations
- Over-segmentation reduced using marker-controlled approach
  
## Impact
Accurate cardiac segmentation supports medical diagnosis and treatment planning.
This project highlights how classical image processing methods remain effective and computationally efficient.

## Additional Resources
- Full report (Indonesian): report/full_report_id.pdf
