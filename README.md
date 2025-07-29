# 🅿️ Interactive Car Parking Space Marker using OpenCV

This Python project provides a simple graphical interface to **manually mark** car parking spaces on a parking lot image using **OpenCV**. You can left-click to add rectangles representing parking spots and right-click to remove them. All positions are saved using `pickle` so you don’t lose your work between sessions.

---

## 📸 Features

- Left-click to add a parking space.
- Right-click to remove a parking space.
- Automatically saves marked positions using `pickle`.
- Live preview of the rectangles on the image.

---

## 🖥️ How It Works

The script opens a parking lot image (`carParkImg.png`) in a window. Using mouse events:
- **Left-click (LMB)** on a location to mark the **top-left corner** of a parking space rectangle.
- **Right-click (RMB)** on a marked rectangle to **remove** it.
- Parking spot size is customizable via `width` and `height`.

All marked positions are saved to a binary file `CarParkPos` using Python’s `pickle` module.

---

## 🧱 Prerequisites

Make sure you have Python 3 and OpenCV installed.

Install OpenCV:
```bash
pip install opencv-python
