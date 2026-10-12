# e-plantShopping - Paradise Nursery Shopping Application

**Repository Name:** `e-plantShopping`  
**Project Name:** Paradise Nursery Shopping Application

---

## 🌿 Project Overview

**Paradise Nursery (`e-plantShopping`)** is a responsive e-commerce web application designed for plant enthusiasts. The platform provides an intuitive and seamless shopping experience for browsing, selecting, and purchasing a wide variety of houseplants tailored to different indoor and outdoor needs.

Built with **React**, **Redux Toolkit**, and **Vite**, this application offers fast performance, dynamic cart management, and an aesthetically pleasing user interface.

---

## ✨ Features

- **Landing Page:** An inviting welcome screen with company background ("Where Green Meets Serenity") and a direct call-to-action button to explore the nursery.
- **Product Catalog:** A rich collection of houseplants grouped by category:
  - *Air Purifying Plants* (e.g., Snake Plant, Spider Plant, Peace Lily)
  - *Aromatic Fragrant Plants* (e.g., Lavender, Jasmine, Rosemary)
  - *Medicinal Plants* (e.g., Aloe Vera, Mint)
  - *Insect Repellent Plants*
  - *Low Maintenance Plants*
- **Product Details:** Each plant includes a thumbnail, name, description, unit price, and an "Add to Cart" button that dynamically indicates when an item is added.
- **Shopping Cart Management (Redux Toolkit):**
  - Displays total items in the navigation bar.
  - View selected items with thumbnail, unit price, and subtotal.
  - Increment (`+`) and decrement (`-`) item quantities.
  - Remove items from the cart.
  - Dynamic calculation of total cart amount.
- **Checkout & Navigation:** Quick actions to continue shopping or proceed to checkout.

---

## 🛠️ Tech Stack

- **Frontend Library:** React (v18)
- **State Management:** Redux Toolkit (`@reduxjs/toolkit` & `react-redux`)
- **Build Tool:** Vite
- **Styling:** CSS3 (Custom styles and responsive layouts)

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/e-plantShopping.git
   ```
2. Navigate into the project directory:
   ```bash
   cd e-plantShopping
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

Start the local development server:
```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173` (or the port specified in your terminal).

### Building for Production

```bash
npm run build
```

---

## 📁 Project Structure

```text
e-plantShopping/
├── public/              # Static assets
├── src/
│   ├── assets/          # Icons and images
│   ├── AboutUs.css      # About Us styling
│   ├── AboutUs.jsx      # About Us section component
│   ├── App.css          # App-level styling
│   ├── App.jsx          # Root component & navigation handling
│   ├── CartItem.css     # Cart page styling
│   ├── CartItem.jsx     # Cart item component with quantity controls
│   ├── CartSlice.jsx    # Redux slice for shopping cart state
│   ├── main.jsx         # Application entry point
│   ├── ProductList.css  # Product listing styling
│   ├── ProductList.jsx  # Catalog component with categorized plants
│   └── store.js         # Redux store configuration
├── index.html           # HTML template
├── package.json         # Project metadata and dependencies
├── vite.config.js       # Vite configuration
└── README.md            # Project documentation
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.