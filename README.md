# Amazon Clone

This project is an Amazon-inspired e-commerce web application built for educational purposes. It demonstrates core e-commerce features such as product listings, shopping cart, checkout, order tracking, and more, using modern JavaScript and modular code organization.

## Features

- **Product Listing:** Browse a variety of products with images, ratings, and prices.
- **Shopping Cart:** Add, remove, and update product quantities in the cart.
- **Checkout:** Review your order, select delivery options, and view payment summary.
- **Order Tracking:** Track your orders after purchase.
- **Order History:** View past orders.
- **Responsive Design:** Optimized for desktop and mobile devices.
- **Unit Tests:** Includes Jasmine tests for core functionality.

## Project Structure

```
amazon-clone-main/
├── amazon.html                # Main storefront page
├── checkout.html              # Checkout page
├── orders.html                # Orders history page
├── tracking.html              # Order tracking page
├── backend/
│   └── products.json          # Product data (mock backend)
├── data/
│   ├── cart.js                # Cart logic
│   ├── cart-class.js          # OOP cart implementation
│   ├── cart-oop.js            # Alternative OOP cart
│   ├── deliveryOptions.js     # Delivery options data
│   ├── orders.js              # Orders data and logic
│   └── products.js            # Products data and logic
├── images/                    # Images and icons
├── scripts/
│   ├── amazon.js              # Main page JS
│   ├── checkout.js            # Checkout page JS
│   ├── checkout/              # Checkout-related modules
│   └── utils/                 # Utility functions (e.g., money formatting)
├── styles/
│   ├── pages/                 # Page-specific CSS
│   └── shared/                # Shared CSS (header, general)
├── tests/
│   ├── lib/                   # Jasmine testing framework
│   ├── data/                  # Data module tests
│   ├── utils/                 # Utility tests
│   └── tests.html             # Jasmine test runner
└── README.md                  # Project documentation
```

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/amazon-clone.git
   cd amazon-clone-main
   ```

2. **Open in your browser:**
   - Open `amazon.html` for the storefront.
   - Open `checkout.html`, `orders.html`, or `tracking.html` for respective features.

3. **Run Tests:**
   - Open `tests/tests.html` in your browser to run the Jasmine test suite.

## Dependencies

- [Jasmine](https://jasmine.github.io/) for unit testing (included in `tests/lib/`).
- [Day.js](https://day.js.org/) via CDN for date handling.

## Notes

- All data is stored in-memory or in JSON files for demonstration; there is no real backend.
- This project is for learning and demonstration only and is not intended for production use.

## License

This project includes the Jasmine testing framework, which is MIT licensed. See `tests/MIT.LICENSE` for details.

---

Inspired by [Amazon.com](https://amazon.com) for educational purposes
