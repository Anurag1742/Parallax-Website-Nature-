
# 🌌 Parallax Website

This project is a simple **Parallax Website** built using **HTML & CSS**. It creates a modern scrolling effect where background images move at a different speed than foreground content, giving a sense of depth and immersion.

---

## 📂 Project Structure

```
parallax-website/
├── index.html
├── style.css
└── images/
    ├── image1.png
    ├── image2.png
    ├── image3.png
```

* **index.html** → Main structure of the webpage
* **style.css** → CSS styling for parallax effect, text overlays, and sections
* **images/** → Background images used in parallax

---

## 🎨 Features

✅ Parallax background images (`image1.png`, `image2.png`, `image3.png`)
✅ Smooth scrolling sections
✅ Overlay text with background highlight
✅ Light & dark themed sections
✅ Fully responsive design

---

## 🖼️ How It Works

* **Parallax Effect** is achieved by using:

```css
background-attachment: fixed;
background-position: center;
background-size: cover;
```

* **Overlay Text** can be styled with:

```css
.ptext {
    position: absolute;
    top: 50%;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 27px;
    letter-spacing: 8px;
    text-transform: uppercase;
}
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Place your background images in the **images/** folder.
3. Make sure `style.css` references your image file names correctly:

   ```css
   .pimg1 { background-image: url(images/image1.png); }
   .pimg2 { background-image: url(images/image2.png); }
   .pimg3 { background-image: url(images/image3.png); }
   ```
4. Open **index.html** in your browser to view the parallax effect.

---

## 📌 Notes

* Replace `image1.png`, `image2.png`, and `image3.png` with your own images.
* Adjust **min-height** in CSS to control section height.
* You can add more `.pimgX` classes to extend the design.

---
