# 🌿 Paradise Nursery

Paradise Nursery is a responsive React-based shopping application for browsing and purchasing houseplants. The application allows users to explore a variety of indoor plants, add them to a shopping cart, update quantities, and view the total purchase cost before checkout.

## Features

* Beautiful landing page with a welcome message and "Get Started" button.
* Browse houseplants organized by categories.
* View plant images, names, prices, and descriptions.
* Add plants to the shopping cart.
* Prevent duplicate additions by disabling the "Add to Cart" button after an item is added.
* Shopping cart with:

  * Increase and decrease item quantity.
  * Remove items automatically when quantity reaches zero.
  * Live total number of items.
  * Real-time total price calculation.
* Navigation using React Router.
* Global state management using Redux Toolkit.
* Responsive design for desktop, tablet, and mobile devices.

## Technologies Used

* React
* React Router
* Redux Toolkit
* React Redux
* JavaScript (ES6+)
* HTML5
* CSS3

## Project Structure

```
src/
├── app/
│   └── store.js
├── components/
│   ├── Navbar.jsx
│   ├── PlantCard.jsx
│   ├── PlantList.jsx
│   └── CartItem.jsx
├── data/
│   └── plants.js
├── features/
│   └── cart/
│       └── cartSlice.js
├── pages/
│   ├── Landing.jsx
│   ├── Products.jsx
│   └── Cart.jsx
├── App.jsx
├── main.jsx
└── index.css
```

## Installation

1. Clone the repository.

```bash
git clone https://github.com/your-username/paradise-nursery.git
```

2. Navigate to the project directory.

```bash
cd paradise-nursery
```

3. Install dependencies.

```bash
npm install
```

4. Start the development server.

```bash
npm run dev
```

5. Open your browser and visit:

```
http://localhost:5173
```

## Usage

1. Open the application.
2. Click **Get Started** on the landing page.
3. Browse available houseplants.
4. Click **Add to Cart** to add a plant.
5. Open the shopping cart from the navigation bar.
6. Increase or decrease item quantities as needed.
7. Review the total cost before proceeding to checkout.

## Future Improvements

* User authentication
* Product search and filtering
* Wishlist functionality
* Secure payment gateway integration
* Order history
* Backend API integration
* Persistent shopping cart using local storage
* Product reviews and ratings

## License

This project is created for educational purposes and is available under the MIT License.

## Author

Developed as part of the **Paradise Nursery Shopping Application** project using React, Redux Toolkit, and React Router.
