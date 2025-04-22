# DF Dance Company - Landing Page

This is a responsive and animated landing page developed for the DF Dance Company.

## 🛠️ Technologies Used
- **HTML5**
- **CSS3** (with Tailwind CSS framework)
- **JavaScript** (Vanilla)
- **Mercado Pago Integration** (Checkout Pro)

## ✨ Features
- Responsive layout for desktop and mobile
- Interactive image carousel (gallery and team members)
- Rotating animated text titles
- Scroll and button-based section navigation
- Contact form with formspree integration
- Product plans with Mercado Pago buttons

## 📁 Structure
```
├── index.html          # Main landing page file
├── style.css           # Custom styles for animations and layout
├── /src/images         # All images used (logo, team, gallery)
└── /scripts            # JavaScript files for interactions
```

## 📦 Setup
1. Clone or download the repository
2. Open `index.html` in a web browser

## 💳 Payments
To enable Mercado Pago buttons:
- Go to [Mercado Pago Developers](https://www.mercadopago.com.br/developers)
- Generate a Checkout Pro `preference_id`
- Replace `SEU_ID_DE_PREFERENCIA` in each form inside the **Pagamento** section

## 🔧 Customization
You can:
- Add or remove team members in the `#equipe` section
- Update image gallery or carousel timing
- Customize the pricing plans

## 📬 Contact
This project includes a contact form via [Formspree](https://formspree.io). To make it work:
- Replace the form `action` with your personal Formspree endpoint.

---
Made with ❤️ for DF Dance Company.
