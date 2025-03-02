# Leon Casino Landing Page

## Folder Structure
```
LEON-CASINO/
│── assets/
│ ├── images/* # All images and icons
│── styles/
│ ├── components/ # Individual CSS files for different sections
│ │ ├── card.css
│ │ ├── cta.css
│ │ ├── registration.css
│ │ ├── slider.css
│ ├── main.css # Main stylesheet that imports component styles
│── index.html # Main HTML file
│── README.md # Project documentation
```
-   **Images** are inside `assets/images`, mostly using WebP for better compression.
-   **CSS is modular**, separating concerns (e.g., `card.css`, `cta.css`) inside `styles/components/`.
-   **If the project were bigger**, I would have used **HTML partials** for reusable components.

## 🎨 Styling Approach

-   **No strict framework** – I just **winged it** and made adjustments based on ChatGPT suggestions.
-   **CSS prefixes** were added using an **online CSS prefixes tool** to ensure cross-browser compatibility.
-   **Animations & Effects** are applied using CSS transitions and Alpine.js.

## 📷 Image Optimization

-   Used **WebP** format where possible to reduce load times.
-   Kept **JPEGs for larger images** when necessary.

**Overall, this project focuses on simplicity, lightweight assets, and smooth animations.**
