# Retinal Fundus Image Stitching

A computer vision project that combines overlapping images into a wider panorama. It explores both natural-image stitching and retinal fundus image stitching.

## Features

- Enhances image contrast using CLAHE.
- Detects and matches image features using SIFT/ORB-based approaches.
- Estimates image alignment with homography and RANSAC.
- Produces stitched panorama outputs for visual inspection.

## Tech Stack

Python · OpenCV · NumPy · Matplotlib · PyTorch · Jupyter Notebook

## Getting Started

```bash
git clone https://github.com/bmanasareddy05/retinalfundus_imgstitching.git
cd retinalfundus_imgstitching
pip install -r Requirements
```

Open `imgstitching.ipynb` in Jupyter Notebook and run the cells. Update the input image or dataset paths to match your local setup.

## Outputs

The repository includes example stitched images such as `panorama_enhanced.png` and `retinalimg_stitched.png`.

## Notes

Results depend on image overlap, illumination, and feature quality. This is an image-processing project for experimentation and is **not a medical diagnostic tool**.
