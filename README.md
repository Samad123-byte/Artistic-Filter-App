# 🎭 Artistic Filter App (OpenCV + Colab)

This project applies **artistic cartoon-style filters** to images using **OpenCV**.  
It was built as part of the **PixelPlay — OpenCV Funpack (Project 2)**, and demonstrates how to combine **bilateral filtering + edge detection** with additional creative presets.

---

## ✨ Features
- 📂 Upload any image (jpg/png)  
- 🎚 Adjustable sliders:
  - Smooth Size (bilateral filter kernel)
  - Sigma Color / Sigma Space
  - Median Blur size
  - Edge Block size / Threshold
- 🎭 Artistic Presets:
  - **Cartoon1** → strong painted effect  
  - **ComicBook** → bold outlines  
  - **SoftPaint** → pastel look  
  - **PencilSketch** → pencil drawing ✏️  
  - **PopArt** → stylized vibrant colors 🌈  
- 💾 Save output (`artistic_output.png`)  
- 🔍 Full View mode for detailed preview  
- Runs **entirely in Google Colab** — no camera required  

---

## 🛠️ Installation
Clone this repo and install dependencies:

```bash
git clone https://github.com/YOUR_USERNAME/artistic-filter-app.git
cd artistic-filter-app
pip install -r requirements.txt
