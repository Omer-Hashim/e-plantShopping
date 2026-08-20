# Paradise Nursery - Houseplant Shopping Application
Paradise Nursery is an interactive e-commerce web application built with **React** and **Redux Toolkit**. Users can explore various categories of houseplants, view detailed plant information, manage a dynamic shopping cart in real time, and process cart updates smoothly.

## Features

### 1. Landing Page
- Styled landing section with background imagery and nursery branding.
- Concise overview of the company vision and a **Get Started** button linking directly to the plant shop.

### 2. Product Listing
- **Categorized Selection:** Displays multiple categories of plants (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance).
- **Plant Cards:** Displays plant image thumbnails, names, descriptions, and unit prices.
- **Dynamic Buttons:** Clicking "Add to Cart" updates global state, disables the button, and changes its status to "Added to Cart".

### 3. Header & Navigation
- **Persistent Header:** Appears on both the product catalog and cart screens.
- **Live Cart Badge:** Displays the total count of all items accumulated in the cart in real time.
- Navigation controls to seamlessly switch between the catalog and cart views.

### 4. Shopping Cart Management
- **Total Item & Cost Calculation:** Displays overall quantity and dollar total for all plants in the cart.
- **Item Subtotals:** Automatically calculates cost per plant type based on unit cost and quantity.
- **Quantity Controls:** Includes `+` (increment) and `-` (decrement) buttons. Decreasing quantity to zero automatically removes the item.
- **Remove & Checkout Actions:** Delete button to clear items, a mock Checkout option, and a "Continue Shopping" button returning to the product grid.

## Tech Stack
- **Frontend Framework:** React (Vite)
- **State Management:** Redux Toolkit & React-Redux
- **Styling:** CSS3
- **Deployment:** GitHub Pages (`gh-pages`)

The repository URL: https://github.com/Omer-Hashim/e-plantShopping/tree/main
