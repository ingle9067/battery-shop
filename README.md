# 🔋 Battery Store (AJ Batteries)

A responsive, front-end e-commerce website for a battery shop. Customers can browse batteries for cars, motorcycles, laptops, and mobile phones, add items to a cart or wishlist, and place orders. The project is built with plain HTML, CSS, and JavaScript, so it needs no backend or build step.

## ✨ Features

- **Home page** with a hero carousel and a product showcase
- **Product catalog** with Quick View modal
- **Shopping cart** with a "Save for later" option
- **Wishlist** to keep track of favourite products
- **User registration & login** (stored in the browser)
- **Order history** page
- **Admin dashboard** to add and manage products
- **Contact page**
- **Responsive design** built with Bootstrap 5, for desktop and mobile

## 🛠️ Tech Stack

| Area | Technology |
| --- | --- |
| Markup | HTML5 |
| Styling | CSS3, [Bootstrap 5.3](https://getbootstrap.com/) |
| Logic | Vanilla JavaScript (ES6) |
| Data storage | Browser `localStorage` |
| Icons / Fonts | Font Awesome, Google Fonts (Roboto) |

## 📁 Project Structure

```
battery-store/
├── index.html          # Home page
├── product.html        # Product listing
├── cart.html           # Shopping cart
├── wishlist.html       # Wishlist
├── login.html          # Login / register
├── order-history.html  # Past orders
├── contact.html        # Contact form
├── admin.html          # Admin dashboard
├── images/             # Product and banner images
└── README.md
```

## 🚀 Getting Started

### Option 1: Open directly

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/battery-store.git
   cd battery-store
   ```
2. Double-click `index.html`, or open it in your browser.

### Option 2: Run with a local server (recommended)

Using VS Code, install the **Live Server** extension, right-click `index.html`, and choose **Open with Live Server**.

Or with Python:

```bash
python -m http.server 8080
```

Then visit <http://localhost:8080>.

## 🌐 Live Demo

Hosted with GitHub Pages: `https://<your-username>.github.io/battery-store/`

## 📝 How It Works

This is a front-end-only project. All data (user account, cart, wishlist, and products added by the admin) is saved in your browser's `localStorage`. This means:

- Data stays on your device and is not shared between users or browsers.
- Clearing browser data will reset the store.
- Passwords are stored in plain text in `localStorage`. This is acceptable for a demo or learning project, but **not suitable for production**.

## 🔮 Future Improvements

- Add a real backend (Node.js / Express, or Firebase) and a database
- Secure authentication with hashed passwords
- Payment gateway integration
- Product search, filters, and sorting
- Real order management for the admin

## 🤝 Contributing

Contributions are welcome. Fork the repo, create a feature branch, and open a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
GitHub: [@your-username](https://github.com/your-username)
