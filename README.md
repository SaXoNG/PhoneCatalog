# 📱 React Product Catalog
A modern, responsive e-commerce catalog built with React and TypeScript. This project showcases a fully functional product catalog with shopping cart, favorites, filtering, sorting, and more—perfect for your portfolio!

## Live Demo
Experience the live website:  [PhoneCatalog](https://saxong.github.io/PhoneCatalog/);

## ✨ Features
### Home Page:
- Dynamic product sliders for "Hot Prices" and "Brand New" items
- Category navigation (Phones, Tablets, Accessories)
- Smooth image carousel and transitions
### Product Catalog:
- Dedicated pages for Phones, Tablets, and Accessories
- Sorting (Newest, Alphabetically, Cheapest)
- Pagination and items-per-page selection
- Real-time search with debounced input
- Skeleton loaders for a polished UX
### Product Details:
- Detailed product view with images, specs, and descriptions
- Color and capacity selection
- "You may also like" recommendations
- Breadcrumb navigation and back button
### Shopping Cart:
- Add/remove products, adjust quantities
- Cart state persists in localStorage
- Checkout modal (demo)
- Cart icon with item count in header
### Favorites:
- Add/remove products to favorites
- Favorites state persists in localStorage
- Favorites icon with count in header
### Other:
- 404 Not Found and Product Not Found pages
- Sticky header and smooth navigation
- Responsive design and theme support
- Footer with GitHub link and "Back to top" button
- Internationalization (i18n) ready

## 🛠️ Tech Stack
- #### Frontend: React, TypeScript, SCSS (CSS Modules), Vite
- #### Routing: React Router
- #### State Management: React Context API
- #### Styling: Bulma, SCSS Modules, custom themes
- #### Icons: FontAwesome
- #### Testing: Cypress
- #### Utilities: i18next, classnames
- #### Build & Deploy: Vite, GitHub Pages

## 📦 Data & Assets
Product data and images are served from the /public/api and /public/img folders.
Easily extensible for new categories or product types.

## 🚀 Getting Started
### Clone the repo:
git clone https://github.com/SaXoNG/PhoneCatalog.git
### Install dependencies:
npm install
### Run the app locally:
npm start
### Build for production:
npm run build
### Run tests:
npm test

## 🖼️ UI/UX
Based on Figma designs-Original) with multiple color themes and dark mode support.
Smooth hover effects, transitions, and responsive layouts.

## 📚 Project Structure
src/components/ – Reusable UI components (ProductCard, ProductList, NavBar, etc.)
src/modules/ – Page-level modules (HomePage, Cart, Favourites, etc.)
src/context/ – React Contexts for global state (cart, favorites, products)
public/api/ – Product data in JSON format
public/img/ – Product and category images

## 📝 License
This project is licensed under the GPL-3.0 License.
Feel free to personalize this further with your name, contact info, or additional sections (e.g., "About Me" or "What I Learned"). Let me know if you want a shorter version or want to highlight specific features!
