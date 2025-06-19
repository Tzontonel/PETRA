# PETRA – a gesture-controlled experience of 3D Rocks & Minerals

[![Download Latest Release](https://img.shields.io/badge/Download_Latest_Release_%E2%86%93-1f425f?style=for-the-badge)](https://github.com/aapopei/PETRA/releases/latest)

**PETRA** is an open-source, gesture-controlled system for exploring 3D rocks and minerals. Developed in TouchDesigner, it uses a standard webcam and the MediaPipe framework to translate natural hand movements into real-time manipulation of digital specimens.

This project was developed as part of the scientific article:
> *Apopei, A. I. (2025). Accessible interface for Museum Geological Exhibitions: PETRA - a gesture-controlled experience of 3D Rocks & Minerals. [submitted to Minerals (ISSN: 2075-163X)].*

[![Watch the PETRA Demo Video](https://img.youtube.com/vi/jeJQMB4h6UE/hqdefault.jpg)](https://www.youtube.com/watch?v=jeJQMB4h6UE)

---

## 🎯 Project Goals

* To create a low-cost, accessible interface for museum and educational settings.
* To provide an intuitive, touchless, and hygienic way to interact with digital 3D models.
* To serve as a practical case study for the Mineralogy 4.0 framework.

## 🚀 Getting Started

### Prerequisites

* A Windows or macOS computer.
* A recent version of **TouchDesigner** (the free non-commercial version is sufficient).
* A standard HD or FullHD webcam.

### Installation

#### **Recommended Method: Download the Latest Release**
1.  Go to the [**Releases Page**](https://github.com/aapopei/PETRA/releases) of this repository.
2.  Under the latest release (e.g., `v2025.6`), download the `PETRA-vYYYY.X.zip` file from the "Assets" section.
3.  Unzip the folder, and you're ready to go.

#### **Alternative (For Developers): Clone the Repository**

If you want the very latest development code and are comfortable using Git, you can clone the repository:
```
git clone https://github.com/aapopei/PETRA.git
```

### **Running the Application**

1.  Open the `PETRA.1.toe` file in TouchDesigner.
2.  The system should start automatically. If your webcam is not detected, go to the **Camera Input** section (Gray nodes), select the MediaPipe container, and then inside it, go to the `Webcam` operator and select the correct camera source from its parameters.
3.  To launch in full screen, go to the **Start Performance Mode** section (Green nodes) and click the "START" button for either Landscape or Portrait mode.
---

## ⚙️ How to Use and Customize

This project is designed to be easily understood and modified. The network is organized with a color-coded legend to guide you.

### Color-Coded Legend

* 🎨 **Green: Performance Controls**
    * *Interactive buttons used to start the application in its final, full-screen performance mode.*
* ⚙️ **Gray: User Settings & Content**
    * *General settings intended for easy user modification. This is where you can change the webcam source, update UI text, or add your own 3D models.*
* ⚠️ **Yellow: UI Layout**
    * *Nodes that control the user interface layout. Modify these with caution, primarily for adjusting the UI for different screen orientations.*
* ⛔ **Red: Core Logic**
    * *Critical nodes that handle the project's core functionality. **Modification is not recommended.***

## 🐛 Bug Reports & Feedback

If you find a bug or have a suggestion for improvement, please **[open an issue](https://github.com/aapopei/PETRA/issues)** on this repository.

---

## ⚖️ Licensing

This entire project, including all code, 3D models, textures, and audio assets, is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to:
* **Share** — copy and redistribute the material in any medium or format.
* **Adapt** — remix, transform, and build upon the material.

Under the following terms:
* **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
* **NonCommercial** — You may not use the material for commercial purposes.
* **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

You can find the full license text in the `LICENSE` file.

---

## ✍️ How to Cite

If you use this project or its assets in your own research, please cite the paper:

> *Apopei, A. I. (2025). Accessible interface for Museum Geological Exhibitions: PETRA - a gesture-controlled experience of 3D Rocks & Minerals. [submitted to Minerals (ISSN: 2075-163X)].*

## 🙏 Acknowledgments

* This project utilizes the [MediaPipe TouchDesigner Plugin](https://github.com/torinmb/mediapipe-touchdesigner) created by Torin Blankensmith.
* 3D models were sourced from the [**Atlas of 3D Rocks and Minerals**](https://www.mdpi.com/2075-163X/14/12/1196) project (Apopei, 2024).
