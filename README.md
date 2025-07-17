# retinalfundus_imgstitching
# 🧠 Image Stitching with OpenCV & PyTorch

This project presents two advanced pipelines for image stitching:

1. 🖼️ **MS COCO / natural scene image stitching** using OpenCV's built-in stitching API.
2. 👁️ **Retinal fundus image stitching** using SIFT/ORB feature-based homography, PyTorch-based warping/blending, and accuracy/loss monitoring.

---

## 📌 Features

### ✅ COCO/Natural Image Stitching
- Uses OpenCV’s `cv2.Stitcher_create()` for quick panorama creation.
- Applies histogram equalization (CLAHE) to enhance brightness and contrast.
- Handles image batch extraction from a ZIP file.

### ✅ Retinal Image Stitching
- Uses SIFT or ORB to detect keypoints and compute descriptors.
- Estimates homography using RANSAC.
- Blends warped image pairs using PyTorch.
- Tracks feature matching accuracy and pixel-level losses across training epochs.
- Saves stitched outputs and matching visualizations.

---

