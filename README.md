# 🛍️ ShopCorner E-Commerce Landing Page

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---
[banner](/images/banner.jpg)

A modern, responsive e-commerce landing page showcasing products across multiple categories including electronics, home appliances, home decor, and fashion.

---

## 📋 Table of Contents
- [Features](#features)
- [File Structure](#file-structure)
- [Color Palette](#color-palette)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Page Sections](#page-sections)
- [Dependencies](#dependencies)

---

## ✨ Features

- 🎨 **Modern UI Design** - Clean and intuitive interface with smooth animations
- 🛒 **Shopping Cart Integration** - Quick access cart icon in navigation
- 🔍 **Search Functionality** - Product search bar with icon
- 📱 **Responsive Navigation** - Menu icon for mobile-friendly experience
- 💳 **Product Showcase** - Multiple product categories with discount badges
- 🏷️ **Sale Banners** - Eye-catching promotional images
- 🎯 **Interactive Elements** - Hover effects on products and buttons
- 💬 **Customer Support** - Help section with chat functionality
- 📞 **Footer Contact** - Social media links and contact information

---

## 📁 File Structure

```
e-comm-landing-page/
│
├── project2.html          # Main HTML file
├── project2.css           # Stylesheet file
├── project2.png           # Logo image
│
├── Images/
│   ├── sale.jpg           # Sale banner 1
│   ├── sale2.jpg          # Sale banner 2
│   ├── sale3.jpg          # Sale banner 3
│   ├── iphone.png         # iPhone product image
│   ├── laptop.png         # Laptop product image
│   ├── headphones.png     # Headphones product image
│   ├── keyboard.png       # Keyboard product image
│   ├── ac.png             # Air conditioner image
│   ├── washing.png        # Washing machine image
│   ├── ref.png            # Refrigerator image
│   ├── tv.png             # Television image
│   ├── wall hanging.png   # Wall hanging image
│   ├── wall pictures.png  # Wall pictures image
│   ├── jhoomer.png        # Chandelier image
│   ├── lights.png         # Lights image
│   ├── clothes.png        # Clothing banner
│   └── shoes.png          # Shoes banner
│
└── README.md              # Project documentation
```

---

## 🎨 Color Palette

| Color Name | Hex Code | Usage |
|------------|----------|-------|
| **Background Cream** | `#F1EFEB` | Main background color |
| **Primary Blue** | `#4379DB` | Navigation background overlay |
| **Accent Red** | `#FF0000` | Discount badges, buttons |
| **Dark Gray** | `#444242` | Text and borders |
| **Light Coral** | `#DD8677` | Navigation shadow |
| **Sky Blue** | `#4476D4` | Search button hover |
| **Purple Accent** | `#8C6DC5` | Help section text |
| **Warning Red** | `#EE3737` | Help section heading |

### Additional Colors
- **White**: `#FFFFFF` - Product cards, text
- **Black**: `#000000` - Footer, text, hover states
- **Light Gray**: `#918686` - Borders and subtle elements

---

## 🛠️ Technologies Used

### Core Technologies
- **HTML5** - Semantic markup structure
- **CSS3** - Styling and animations
- **JavaScript** - Via Ionicons for interactive elements

### External Libraries & Resources
- **Google Fonts** - Sofia font family
- **Font Awesome 4.7.0** - Icons (home, cart)
- **Ionicons 7.1.0** - Modern icon set (search, social media)

---

## 🚀 Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Local web server (optional, for development)

### Installation Steps

1. **Clone or Download the Project**
   ```bash
   git clone <repository-url>
   cd e-comm-landing-page
   ```

2. **Verify File Structure**
   - Ensure all HTML, CSS files are in the root directory
   - Ensure all images are in their respective locations

3. **Open the Project**
   - Simply open `project2.html` in your browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

4. **Access the Website**
   - Direct file: `file:///path/to/project2.html`
   - Local server: `http://localhost:8000/project2.html`

---

## 📄 Page Sections

### 1. **Navigation Bar**
- Logo and branding
- Menu items: Home, Profile, Categories, About us, Contact us
- Shopping cart icon
- Search bar with icon
- Hamburger menu icon

### 2. **Sale Banner Section**
- Three promotional images showcasing current sales
- Hover zoom effect for interactivity

### 3. **Electronics & Gadgets**
Products featured:
- Apple iPhone 13 (128GB) - 17% off
- Asus TUF Gaming Laptop - 25% off
- Kotion G-2000 Gaming Headphones - 32% off
- Logitech Gaming Keyboard - 29% off

### 4. **Home Appliances**
Products featured:
- Voltas Air Conditioner - 27% off
- Samsung Washing Machine - 12% off
- Samsung Refrigerator - 19% off
- LG Smart Television - 20% off

### 5. **Home Decor**
Products featured:
- Star Wall Hanging - 10% off
- Wall Pictures Decor - 17% off
- Chandelier - 16% off
- LED Holder Socket - 13% off

### 6. **Fashion Section**
- Clothing: Up to 60% off
- Shoes: Up to 40% off
- Limited time offers with countdown

### 7. **Help Section**
- Search query input
- "Chat with us" button for customer support

### 8. **Footer**
- Terms of service
- Copyright information
- Contact phone number
- Social media links (Facebook, WhatsApp, Instagram, Twitter, LinkedIn)

---

## 📦 Dependencies

### CDN Links Used
```html
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css?family=Sofia" rel="stylesheet">

<!-- Font Awesome -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">

<!-- Ionicons -->
<script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
```

---

## 🎯 Key CSS Features

- **Flexbox Layouts** - For responsive product grids
- **Hover Animations** - Smooth transitions on interactive elements
- **Transform Effects** - Scale and rotate animations
- **Box Shadows** - Depth and elevation effects
- **Custom Styling** - Unique design elements throughout

---

## 💡 Future Enhancements

- [ ] Add responsive design for mobile devices
- [ ] Implement functional shopping cart
- [ ] Add product filtering and sorting
- [ ] Create individual product detail pages
- [ ] Integrate payment gateway
- [ ] Add user authentication
- [ ] Implement backend database
- [ ] Add product reviews and ratings
- [ ] Create wishlist functionality
- [ ] Add newsletter subscription

---

## 🙏 Acknowledgments

- Font Awesome for icon library
- Ionicons for modern icons
- Google Fonts for typography
- All product images and sale banners (ensure proper licensing)

---

**Happy Shopping! 🛍️**
