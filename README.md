# Modular Visual Image Processing System

## 🧠 Project Overview

This project is a **modular image processing system** developed in C++ using **Qt Framework**. It enables visual, node-based image manipulation by connecting different processing modules like input, output, filters, and enhancements. Each module (or "node") performs a distinct image operation, enabling complex workflows through a graphical interface.

## ✨ Features Implemented

- 📥 **InputNode**: Load images for processing.
- 🧮 **ImageProcessor**: Core logic for applying various image operations.
- 📤 **OutputNode**: Display or save processed results.
- ⚙️ **Custom Node Architecture**: Abstract base class for easily adding new processing nodes.
- 🖼️ **MainWindow UI**: Graphical interface designed using Qt Designer (`.ui` file).
- 📂 **Qt Project File (.pro)**: Project managed via Qt Creator for seamless builds.

### 📊 Supported Operations
- Brightness and Contrast Adjustment
- Gaussian Blur
- Edge Detection
- Thresholding
- Channel Manipulation
- Image Blending

> Note: You can extend the node system to include more image processing tasks easily.

---

## 🛠️ Build Instructions

### 🔧 Requirements

- **Qt Creator or Qt 5/6 SDK**
- **C++17 compatible compiler**
- **CMake or qmake (depending on your setup)**
- Optional: **OpenCV** (for more advanced processing)

### ⚙️ Using Qt Creator

1. Open `untitled/untitled.pro` with **Qt Creator**.
2. Configure the project (select build kit).
3. Click **Run** or **Build** to compile and launch.

### 💻 Manual Build with qmake

```bash
cd untitled
qmake
make
./untitled
