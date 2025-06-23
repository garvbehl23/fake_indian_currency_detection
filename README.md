# 🧾 Fake Currency Detection System

A Python-based Fake Currency Detection System that leverages image processing and feature extraction techniques using OpenCV and ORB, combined with a user-friendly GUI built using Tkinter. This system analyzes Indian currency notes and helps determine their authenticity by extracting key features such as left bleed lines, right bleed lines, and the number panel using SSM (Structured Similarity Measures), and validating through ORB-based feature matching.

---

## 📌 Features

- ✅ Detects Indian currency notes (real or fake) based on visual and structural cues.
- 🖼️ Extracts:
  - **Left Bleed Lines**
  - **Right Bleed Lines**
  - **Number Panel**
- 🔍 Uses **ORB (Oriented FAST and Rotated BRIEF)** for robust keypoint detection and feature matching.
- 💡 GUI interface using **Tkinter** for easy note selection and real-time result visualization.
- 🔧 Image preprocessing and filtering using **OpenCV**.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Core programming language |
| OpenCV | Image processing and feature extraction |
| Tkinter | GUI development |
| ORB | Feature detection |
| SSM | Structured Similarity Measures for region comparison |

---

## 📸 System Workflow

1. **User selects an image** of the currency note via the Tkinter GUI.
2. The system preprocesses the image (grayscale, thresholding, etc.).
3. **SSM** is applied to extract:
   - Left bleed lines
   - Right bleed lines
   - Number panel
4. **ORB descriptors** are computed and matched with real currency templates.
5. The system gives output indicating whether the note is **Real or Fake**.

---


