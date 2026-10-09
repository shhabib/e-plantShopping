# e-plantShopping - Paradise Nursery

Welcome to **Paradise Nursery** (`e-plantShopping`), an intuitive and responsive houseplants e-commerce web application built using **React** and **Redux Toolkit**.

## 🌿 About the Project

**Paradise Nursery** is an online shopping platform designed for indoor plant enthusiasts. The application offers an engaging shopping experience featuring a curated collection of houseplants organized by plant categories (such as Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance).

### Key Features

- **Landing Page**:
  - Welcoming hero section with background imagery and nursery branding.
  - Informative **About Us** section describing the nursery's passion for quality and greenery.
  - Intuitive "Get Started" call-to-action button transitioning smoothly to the shopping catalog.

- **Product Listing Page**:
  - Organized houseplant catalog across multiple categories.
  - Detailed product cards showcasing thumbnails, botanical and common plant names, descriptions, and prices.
  - "Add to Cart" functionality that updates global state, disables the button, and provides instant visual feedback ("Added to Cart").
  - Persistent navigation bar with dynamic cart item counter badge.

- **Shopping Cart Page**:
  - Real-time calculation of total cart amount and total plant count.
  - Individual item subtotal calculation.
  - Quantity controls (`+` to increment, `-` to decrement) with automatic removal when count reaches zero.
  - "Delete" button to remove items directly.
  - "Continue Shopping" button returning effortlessly to the plant catalog.
  - "Checkout" button with notifications for upcoming checkout features.

- **State Management**:
  - Powered by **Redux Toolkit** (`@reduxjs/toolkit` and `react-redux`) with centralized state management in `CartSlice.jsx`.

---

## 🛠️ Built With

- **React** (v18)
- **Redux Toolkit** & **React-Redux**
- **Vite** (Build tool & development server)
- **CSS3** (Responsive styling and animations)
- **gh-pages** (GitHub Pages deployment)

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

5. Preview the production build locally:
   ```bash
   npm run preview
   ```

---

## 📦 Deployment to GitHub Pages

To deploy this project to GitHub Pages:

1. Update `base` in `vite.config.js` to match your repository name:
   ```javascript
   base: "/e-plantShopping/",
   ```

2. Run the deploy script:
   ```bash
   npm run deploy
   ```

---

## 📄 License

This project is licensed under the MIT License.