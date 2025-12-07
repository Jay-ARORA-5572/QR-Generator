# QR Generator – Google-Only Version

A lightweight, responsive, HTML/CSS/JS-based QR generator that automatically generates a QR code for **[E-commerce-database](https://github.com/Jay-ARORA-5572/E-commerce-database)** on page load. Includes dark/light mode, downloads in multiple formats, and ZIP export.

## Features

### **1. Auto QR Generation**

* Automatically generates the QR code for **[E-commerce-database](https://github.com/Jay-ARORA-5572/E-commerce-database)** when the page loads.
* No input required; link is fixed and non-editable.

### **2. Download Options**

Users can download the generated QR code in:

* **PNG**

### **3. Responsive UI**

* Layout adapts automatically across mobile, tablet, and desktop screen sizes.
* QR code container scales properly on small screens.

### **4. Modern UI with Dark/Light Theme**

* Attractive **toggle switch** for theme switching.
* Smooth transitions between themes.
* Uses CSS custom properties for easy theme customization.

### **5. No External Backend**

* Fully client-side.
* Works offline once loaded.

##  Tech Stack

| Technology               | Purpose                                            |
| ------------------------ | -------------------------------------------------- |
| **HTML5**                | Structure and page layout                          |
| **CSS3**                 | Styling, theming, and responsive design            |
| **JavaScript (Vanilla)** | QR creation, downloads, theme toggle |
| **QRious**               | QR generation library                              |

## Project Structure

```
qr-generator/
│
├── qr-generator.html       # Main UI and entire application
├── README.md        # Documentation
└── assets/          # (Optional) Folder for future icons or resources
```

---

## 🚀 How to Use

1. Open the `index.html` file in any modern browser:

   * Chrome
   * Firefox
   * Edge
   * Safari

2. The page automatically generates a **QR code for my other project 'E-commerce-database'**.

3. Use the download buttons to export:

   * PNG

4. Toggle the Dark/Light switch to change themes.

## 📥 Download Options Explained

### **PNG**

Best for:

* Websites
* Presentations
* Image viewers

## Customization

### **Change the QR URL**

Inside `index.html`, update this line:

```html
<input type="text" id="text" value="https://github.com/Jay-ARORA-5572/E-commerce-database" readonly>
```

### **Customize Themes**

In the CSS:

```
:root { ... }          # Light theme colors  
body.dark { ... }      # Dark theme colors
```

You can modify:

* Background color
* Text color
* Card transparency
* Input background

## Browser Compatibility

Works on all modern browsers:

| Browser | Supported |
| ------- | --------- |
| Chrome  | ✔         |
| Firefox | ✔         |
| Edge    | ✔         |
| Safari  | ✔         |
| Opera   | ✔         |

## Acknowledgements

* **QRious** for QR code rendering

## Contact

For queries, improvements, or collaboration, feel free to reach out.
This project is beginner-friendly and open for learning purposes.
