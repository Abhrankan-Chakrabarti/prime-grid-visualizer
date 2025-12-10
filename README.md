# Prime Grid Visualizer

A fast, interactive **prime number grid visualizer** that runs entirely in your browser.
It uses an optimized Sieve of Eratosthenes and renders numbers using an HTML `<canvas>` for smooth performance even at large values of **n**.

### 🎨 Color Legend

* 🟩 **Prime** — Green
* 🟥 **Composite** — Red
* 🔵 **1 (Special)** — Neither prime nor composite
* ⬜ **Beyond n** — Grey

---

## 🔗 Live Demo

[https://abhrankan-chakrabarti.github.io/prime-grid-visualizer/](https://abhrankan-chakrabarti.github.io/prime-grid-visualizer/)

---

## 🚀 Features

* Adjustable **n**, **columns**, and **cell size**
* Optimized **Sieve of Eratosthenes** in JavaScript
* Canvas-based rendering for **high performance**
* Hover tooltip with number + classification
* **Jump to number** navigation with yellow highlight flash
* Auto-centering scroll when jumping
* **Compact statistics section**
  (Prime count, Composite count, Prime %, Column-wise distribution)
* **Export grid as PNG**
* Works fully offline
* Clean, responsive interface

---

## 📸 Screenshot

![Prime Grid Screenshot](screenshot.png)

---

## 📂 Project Structure

```
index.html   # Main application
README.md    # Documentation
```

---

## 🧠 How It Works

### 1. Prime Sieve

A fast implementation of the Sieve of Eratosthenes is used to classify every number up to **n**:

* `1` is treated as a **special case**
* Primes marked in green
* Composites in red
* Numbers beyond `n` in grey

### 2. Canvas Rendering

The grid is drawn using `<canvas>`, allowing:

* Smooth panning
* Fast updates even with thousands of cells
* PNG export capability

### 3. Jump Navigation

Entering a number:

* Scrolls to its cell
* Centers it in the view
* Highlights it briefly

Useful for exploring patterns in prime distribution.

---

## 🛠 Hosting on GitHub Pages

1. Go to **Settings → Pages**
2. Choose:

   * **Source:** Deploy from branch
   * **Branch:** `main`
   * **Folder:** `/` (root)
3. Save and open your published link.

---

## 📄 License

MIT License

---

## 👤 Author

**Abhrankan Chakrabarti**

---

## ⭐ Support the Project

If you enjoy this visualizer, please consider leaving a **star** ⭐ on GitHub!
