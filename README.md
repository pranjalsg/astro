# Astrophysics and General Relativity Tools

This repository contains two Python-based computational tools. It features a practical astronomical image stacking application and a theoretical physics calculator for general relativity.

## 1. StackerPy v1.0

StackerPy is an Astronomical Image Stacking Software built entirely using Python. It allows you to process video files recorded through a telescope using any type of camera, including mobile adapters or dedicated astronomy cameras.

### Overview and Features
* **Target Applications:** It is written primarily for planetary imaging, such as capturing the Sun or the Moon. 
* **Deep Sky Mode:** It includes a deep sky stacking mode, though this feature is currently untested.
* **Core Workflow:** The stacking pipeline involves extracting and reading video frames into memory, conducting quality analysis to select frames with sharp edges, aligning the images based on extended objects or star patterns, and stacking them via pixelwise mean or median calculations.
* **Post-Processing:** The software includes multi-scale wavelet post-processing to enhance the final stacked image.
* **Ease of Use:** The notebook features a fully interactive Graphical Interface dashboard built with `ipywidgets`.

> **WARNING:** Never point your telescope or camera towards the Sun without a proper Solar filter.

## 2. General Relativity Tensors - Calculators

This notebook serves as an automated mathematical tool for dealing with the complex tensor calculus required in General Relativity.

### Overview and Features
* **Calculations:** The script computes exact symbolic representations of Christoffel Symbols, the Riemann Curvature Tensor, the Ricci Tensor, the Ricci Scalar, and the Einstein Tensor.
* **Backend:** It utilizes `sympy` and `numpy` to dynamically build vectors and perform Einstein summations.
* **Built-in Testing:** The notebook includes a pre-configured test calculation using the FLRW (Friedmann–Lemaître–Robertson–Walker) Metric.

---

## 🤝 Contributing and Testing

Testers and contributors are warmly invited to help improve this repository! 

Because the Deep Sky stacking mode in StackerPy is currently **untested**, if anyone is willing to contribute and test it out, please feel free to do so. You can send your feedback, bug reports, or improvements to pranjalsengupta5@gmail.com. 

## 📝 Credits

If you use this code for your own astrophotography, physics research, or personal projects, please consider crediting the original author, **Pranjal Sengupta**.
