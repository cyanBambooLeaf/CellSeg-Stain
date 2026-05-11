# CellSeg-Stain: Cell Segmentation & Stain Recognition Tool

**CellSeg-Stain** is a cross-platform desktop application built with **Vue.js + Electron** for the frontend and **Python** for the backend. It provides an intuitive graphical interface for biomedical researchers to perform cell segmentation and stain recognition tasks on histopathological images.

## Key Features

- 🧫 **Cell Segmentation** - Leverages deep learning models (Cellpose) to accurately segment cells from tissue images
- 🎨 **Color Deconvolution** - Separates stained tissue images into individual stain channels (H&E, H-DAB, etc.)
- 📊 **Stain Intensity Calculation** - Quantifies staining intensity at single-cell level with customizable thresholds
- 🖥️ **Modern GUI** - Built with Vue 3 and Electron for a smooth, native-like user experience
- 🔬 **Python-Powered** - All heavy computations are handled by Python scripts, ensuring performance and flexibility

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Vue 3, Electron, Vite |
| Backend | Python 3.8+ |
| Image Processing | scikit-image, OpenCV, TIFFile |
| Deep Learning | Cellpose, PyTorch |
| Data Output | CSV, PNG annotations |

## Use Cases

- Quantitative analysis of immunohistochemistry (IHC) staining
- High-throughput cell morphology studies
- Pathological image annotation and validation
