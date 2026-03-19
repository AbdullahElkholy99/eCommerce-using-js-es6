# E-Commerce Product Page

A modern and responsive e-commerce product page built using HTML, CSS, and JavaScript ES6.
This project demonstrates dynamic product rendering, filtering, and a clean UI similar to real-world online stores.

---

## Features

* Product Listing Page
* Dynamic Product Details Page
* Image Gallery with Preview Switching
* Color Picker UI
* Quantity Selector (+ / -)
* Add to Cart Animation
* Filters (Category, Price, Colors, Size)
* Fully Responsive Design
* Reviews Section UI

---

## Project Structure

```
project/
│
├── HTML/
│   ├── casual.html
│   └── casual-details.html
│
├── CSS/
│   └── style.css
│   └── casual-details..css
│   └── casual.css
│   └── hero-section.css
│   └── nav-bar.css
│   └── normalize.css
│   └── footer.css
│
├── JS/
│   ├── script.js
│   └── casual-details.js
│   └── casual.js
│   └── nav-bar.js
│
├── Images/
│   └── (product images)
├── index.html
│
└── README.md
```

---

## How It Works

### Product Navigation

Clicking a product card redirects to:

```
casual-details.html?id=PRODUCT_ID
```

### Fetching Data

Product data is fetched dynamically from:

```
https://dummyjson.com/products/{id}
```

### Rendering

JavaScript dynamically injects:

* Product title
* Images
* Price and discount
* Description
* Rating

---

## Technologies Used

* HTML5
* CSS3 (Flexbox, Grid, Animations)
* JavaScript (ES6+)
* DummyJSON API

---

## Responsive Design

The layout adapts to:

* Desktop: Grid layout
* Tablet: Mixed layout
* Mobile: Vertical stack

---

## UI Highlights

* Smooth hover effects
* Animated buttons
* Interactive filters
* Clean modern layout
* Subtle shadows and transitions

---

## Future Improvements

* Real Cart with LocalStorage
* Wishlist Feature
* User Authentication
* Payment Integration
* Dynamic Review System
* Search Functionality

---

## Author

Abdullah Ali Elkholy

---

## License

This project is open-source and free to use.
