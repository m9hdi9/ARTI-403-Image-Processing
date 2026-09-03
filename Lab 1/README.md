# Lab 1: Basics of Programming with Python

This lab covers the fundamental concepts of digital image representation and manipulation using Python, Jupyter Notebook, and standard image processing libraries[cite: 2].

---

## 🎯 Lab Objectives
- Understand how digital images are represented as matrices/arrays[cite: 2].
- Load, display, manipulate, and save digital images[cite: 2].
- Perform basic array operations using **NumPy**[cite: 2].

---

## 🛠️ Tools & Libraries
- **Python 3**[cite: 2]
- **Jupyter Notebook**[cite: 2]
- **Libraries Used:**
  - `OpenCV` (`cv2`): Image reading and writing[cite: 2].
  - `Pillow` (`PIL`): Image loading and format handling[cite: 2].
  - `Matplotlib`: Image visualization and plotting[cite: 2].
  - `NumPy`: Multi-dimensional array operations and pixel manipulation[cite: 2].

---

## 📋 Implemented Tasks

### Task 1: Environment & Package Setup
- Installed and configured required image processing packages (`opencv-python`, `pillow`, `matplotlib`, `numpy`)[cite: 2].

### Task 2: Loading and Visualizing Images
- Loaded and visualized grayscale and color images using both **OpenCV** and **PIL**[cite: 2].
- Applied correct color mapping (`cmap='gray'`) for grayscale representation[cite: 2].

### Task 3: Image Storing
- Saved processed image data to disk in standard formats using `cv2.imwrite()` and `Image.save()`[cite: 2].

### Task 4: Image Representation as an Array
- Inspected image dimensions (`shape`), data types (`dtype`), and raw pixel matrices[cite: 2].
- Converted PIL objects into NumPy arrays for numerical computation[cite: 2].

### Additional Operations (NumPy Practice)
- Calculated pixel statistics (minimum, maximum, and mean intensity values).
- Performed basic image cropping using array slicing (`img[y1:y2, x1:x2]`).

---

## 📁 Repository Structure
```text
.
├── images/
│   ├── cameraman.tif
│   └── lena_gray_256.tif
├── Lab1_2240007563.ipynb
└── README.md
