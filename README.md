# Paradise Nursery Shopping Application

A modern, responsive e-commerce web application built with **React**, **Vite**, and **Redux Toolkit** for the online plant store **Paradise Nursery**. This project is completed as the final submission for the IBM course *"Developing Front-End Apps with React"*.

---

## 🌿 About the Project

**Paradise Nursery** is an online shopping platform where plant enthusiasts can explore and purchase a wide variety of houseplants. The application provides an intuitive and seamless user experience, allowing customers to browse categorized plants, view plant details and prices, add items to their shopping cart, adjust quantities, and see live pricing calculations powered by centralized Redux state management.

---

## ✨ Features

- **Interactive Landing Page**:
  - Full-screen high-resolution greenhouse background image.
  - Company branding: *"Welcome To Paradise Nursery - Where Green Meets Serenity"*.
  - Comprehensive "About Us" section detailing the nursery's mission and commitment to quality.
  - "Get Started" button with smooth transitions to the plant catalog.

- **Categorized Plant Catalog**:
  - 30 unique indoor and outdoor houseplants organized into 5 categories:
    1. *Air Purifying Plants* (Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera)
    2. *Aromatic Fragrant Plants* (Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth)
    3. *Insect Repellent Plants* (Oregano, Marigold, Geraniums, Basil, Citronella, Catnip)
    4. *Medicinal Plants* (Aloe Vera, Echinacea, Peppermint, Lemon Balm, Chamomile, Calendula)
    5. *Low Maintenance Plants* (ZZ Plant, Pothos, Cast Iron Plant, Succulents, Aglaonema, Jade Plant)
  - Each plant card displays a thumbnail image, plant name, description, unit price, and an "Add to Cart" button.
  - Buttons dynamically disable and display *"Added to Cart"* once the product is selected.

- **Dynamic Navigation Bar**:
  - Consistent navbar rendered on both product listing and cart views.
  - Direct links to **Home** (returns to landing page), **Plants** (returns to product grid), and **Cart**.
  - Dynamic shopping cart badge icon displaying real-time total item count.

- **Shopping Cart Management**:
  - Item details including thumbnail, name, unit price, quantity, and individual subtotal cost.
  - Quantity controls (`+` and `-`) that update totals in real time. Decreasing below 1 automatically removes the item.
  - Dedicated **Delete** button to remove specific plants from the cart.
  - Dynamically calculated **Total Cart Amount** and **Total Plants Count**.
  - **Continue Shopping** button to easily resume browsing.
  - **Checkout** button with an informative alert notification.

---

## 🛠️ Technologies Used

- **React 18** (Functional Components, Hooks: `useState`, `useEffect`)
- **Redux Toolkit** (`createSlice`, `configureStore`) & **React-Redux** (`useSelector`, `useDispatch`, `Provider`)
- **Vite** (Next-generation frontend tooling and fast dev server)
- **Vanilla CSS3** (Custom responsive layouts, flexbox, CSS transitions, media queries)
- **HTML5 & JavaScript (ES6+)**

---

## 📁 Project Structure

```text
e-plantShopping/
├── public/                 # Static public assets
├── src/
│   ├── assets/             # Images and media assets
│   ├── AboutUs.css         # Styling for AboutUs component
│   ├── AboutUs.jsx         # Company background, mission, and overview
│   ├── App.css             # Main styling, background image, and landing page
│   ├── App.jsx             # Main application container and landing view
│   ├── CartItem.css        # Styling for shopping cart page
│   ├── CartItem.jsx        # Shopping cart view with item management and totals
│   ├── CartSlice.jsx       # Redux Toolkit slice (addItem, removeItem, updateQuantity)
│   ├── ProductList.css     # Styling for navbar, categories, and plant cards
│   ├── ProductList.jsx     # Plant catalog with category groupings and navbar
│   ├── index.css           # Global resets and root styling
│   ├── main.jsx            # React root mount with Redux Provider
│   └── store.js            # Redux store configuration
├── index.html              # HTML5 entry point
├── package.json            # Project dependencies and npm scripts
├── vite.config.js          # Vite build configuration
└── README.md               # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 16 or newer recommended)
- [npm](https://www.npmjs.com/) (bundled with Node.js)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/arhaqx/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173/` (or the URL displayed in your terminal).

5. **Build for production**:
   ```bash
   npm run build
   ```

---

## 👤 Author

- **GitHub**: [@arhaqx](https://github.com/arhaqx)
- Course: *Developing Front-End Apps with React* (IBM / Coursera)