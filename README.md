# CS Fashion Shop

A modern, responsive fashion e-commerce website built with HTML, CSS, and JavaScript.

## Features

- 🏠 **Home Page** - Welcome section with navigation
- 🛍️ **Shop Section** - Browse products by categories (Men, Women, Kids)
- 🛒 **Shopping Cart** - Add/remove products with quantity management
- 👥 **About Us** - Company information and social links
- 📞 **Contact Us** - Contact form for customer inquiries
- 🔐 **Authentication** - Sign Up and Login pages
- 🌙 **Dark Mode** - Toggle between light and dark themes
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices

## Project Structure

```
Project CS/
├── index.html              # Sign Up page
├── Home/
│   ├── home.html          # Home page
│   ├── home.css           # Home styles
│   └── logo.jpg           # Company logo
├── Shop/
│   ├── shop.html          # Shop page
│   ├── shop.css           # Shop styles
│   ├── shop.js            # Shop functionality
│   ├── background.avif    # Shop background
│   └── imgs/              # Product images
├── Cart/
│   ├── cart.html          # Cart page
│   ├── cart.css           # Cart styles
│   └── cart.js            # Cart functionality
├── About Us/
│   ├── about.html         # About Us page
│   ├── about.css          # About styles
│   └── background.mp4     # Background video
├── Contact/
│   ├── contact.html       # Contact page
│   └── contact.css        # Contact styles
├── Login/
│   ├── login.html         # Login page
│   ├── register.js        # Registration form
│   ├── login.js           # Login functionality
│   └── style.css          # Login styles
└── footer/
    └── footer.css         # Footer styles
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Responsive styling with flexbox/grid
- **JavaScript (ES6+)** - Client-side functionality
- **Font Awesome** - Icon library
- **Google Fonts** - Typography

## How to Use

1. Clone the repository
2. Open `index.html` in a web browser
3. Navigate through the site using the navigation menu
4. Add products to cart and manage quantities
5. Use the contact form to get in touch

## Features Explanation

### Login System

- Sign Up: Create new account with validation
- Login: Access account (username: username, password: 6+ characters)
- Form validation for email and password

### Shopping Cart

- LocalStorage integration for cart persistence
- Add/remove products
- Update quantities
- View cart summary with total price
- Clear cart functionality

### Product Categories

- Men's Section
- Women's Section
- Kids' Section
- Search functionality to navigate sections

### Responsive Design

- Mobile-first approach
- Breakpoints for tablets and desktops
- Touch-friendly interface

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Notes

- Cart data is stored in browser's localStorage
- No backend server required
- All images should be in the `Shop/imgs/` directory
- Video file `background.mp4` should be in `About Us/` folder

## Author

CS Fashion Shop Team

## License

© 2025 CS Fashion Shop. All Rights Reserved.
