# 🖌️ Image to Pencil Sketch Converter

Turn ordinary photos into stunning **pencil sketch artworks** with a single click!  
This project applies basic **Digital Image Processing** techniques to convert colored images into realistic pencil sketches using **Python** and **OpenCV**.

---

## 🚀 Features

- 🖼️ Convert any image (JPEG/PNG) into a pencil sketch.
- 🎨 Realistic sketch effect using **grayscale**, **inversion**, **blurring**, and **blending**.
- ⚡ Fast and lightweight – runs locally with minimal setup.
- 📚 Great as a beginner-friendly **Digital Image Processing** project.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.x** | Programming language |
| **OpenCV (cv2)** | Image processing library |
| **NumPy** | Efficient matrix operations |
| **Matplotlib** | For displaying input/output images |

---

## 📂 Project Structure

```
Image-to-Pencil-Sketch/
│
├── pencil_sketch.py        # Main script
├── sample_input.jpg         # Sample input image
├── sample_output.png        # Generated pencil sketch
├── requirements.txt         # Dependencies
└── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/SHALINISAURAV/image-to-pencil-sketch.git
   cd image-to-pencil-sketch
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script**
   ```bash
   python pencil_sketch.py --image your_image.jpg
   ```

---

## 📝 Usage Example

```bash
python pencil_sketch.py --image sample_input.jpg
```

**Output:** A pencil sketch version of the input image is saved as `output_sketch.png` in the same folder.

---

## 📸 Sample Output

| Original Image | Pencil Sketch |
|---------------|---------------|
| ![Original](sample_input.jpg) | ![Sketch](sample_output.png) |

*(The above example uses the included sample image.)*

---

## 🧠 How It Works

1. Convert the image to **grayscale**.
2. Invert the grayscale image.
3. Apply **Gaussian blur** to the inverted image.
4. Blend the grayscale and blurred inverted image using **color dodge**.

---

## 🎯 Future Improvements

- Add a **GUI** or **web interface** for easier use.
- Allow multiple sketch styles (charcoal, ink, etc.).
- Batch processing for multiple images.

---

---

✨ *Made with Python & OpenCV by [SHALINI SAURAV]* ✨
