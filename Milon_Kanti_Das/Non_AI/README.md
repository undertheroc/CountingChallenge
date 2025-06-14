This folder contains my OpenCV-based, non-AI solution for the object counting challenge.

### Objective
To detect and count the number of distinct objects in an image and generate overlay masks with at least 95% accuracy using classical computer vision techniques (no ML models).

### Tools & Libraries Used
- Python
- OpenCV (cv2)
- NumPy

### Approach Summary
1. Convert image to grayscale
2. Apply adaptive thresholding or Otsu’s method
3. Use morphological operations (opening/closing) to clean noise
4. Detect contours
5. Draw bounding boxes and masks
6. Count distinct contours as objects

### Output
- Processed images with overlaid masks
- Console output with total object count

### Files
- `app.py` – Main pipeline to read, process, mask, and count
- `test/` – Folder with test input images and output results

---
