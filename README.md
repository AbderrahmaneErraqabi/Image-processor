# 🖼️ Image Processor

![C++](https://img.shields.io/badge/C%2B%2B-20-blue.svg?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Mac%20%7C%20Linux%20%7C%20Windows-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Working-success?style=for-the-badge)

### 🔍 Overview
**Image Processor** is a simple C++ project that manipulates RGB pixel images using structured data types and file handling.  
It can:
- Read image data from text files (`Images.txt`)
- Modify pixel colors (RGB)
- Resize images by doubling width or height
- Save output as `.bmp` bitmap files  
Perfect for experimenting with **image data structures**, **loops**, and **file I/O** in modern C++.

---

### ⚙️ Features
- 🧩 Pixel-level operations (color addition, clamping, RGB encoding)
- 📐 Dynamic image resizing (width or height)
- 💾 BMP image saving (`sauvegarderImage`)
- 📄 File import/export from `Images.txt`
- 🖥️ Structured output display of image grids in console

---

### 🚀 How to Build & Run

#### Using **CMake (Recommended)**
```bash
# Clone the repository
git clone https://github.com/<your-username>/ImageProcessor.git
cd ImageProcessor

# Create build directory
mkdir build && cd build

# Configure and compile
cmake ..
make

# Run
./TD4
