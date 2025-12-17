# 🏨 Hotel Booking Website

A modern, responsive hotel booking website built with vanilla HTML, CSS, and JavaScript. Features a luxurious design with smooth animations, interactive elements, and a fully responsive layout optimized for all devices.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Mobile-friendly hamburger menu with smooth transitions
- **Booking Form**: User-friendly booking interface with arrival/departure date and guest selection
- **Room Showcase**: Beautiful room cards displaying three room types (Deluxe Suite, Family Suite, Luxury Penthouse) with pricing
- **Animated Sections**: Smooth scroll-reveal animations for enhanced user experience
- **Video Integration**: Embedded video section showcasing hotel amenities
- **Feature Highlights**: Interactive feature cards displaying hotel facilities and benefits
- **Food Menu**: Elegant menu section with food items and descriptions
- **Modern UI/UX**: Clean, luxury-themed design with carefully chosen color palette and typography

## 🚀 Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: 
  - CSS Custom Properties (Variables)
  - Flexbox & Grid Layout
  - Media Queries for responsiveness
  - Smooth transitions and animations
- **JavaScript (ES6+)**:
  - DOM manipulation
  - Event handling
  - Mobile menu toggle functionality
- **External Libraries**:
  - [ScrollReveal.js](https://scrollrevealjs.org/) - Scroll animations
  - [RemixIcon](https://remixicon.com/) - Icon library
  - [Google Fonts](https://fonts.google.com/) - Typography (Playfair Display & Poppins)

## 📁 Project Structure

```
hotel-website/
│
├── assets/
│   ├── about-1.jpg, about-2.jpg, about-bg.jpg
│   ├── header.jpg
│   ├── luxury.mp4
│   ├── menu-1.jpg through menu-9.jpg
│   ├── news-1.jpg, news-2.jpg, news-3.jpg
│   └── room-1.jpg, room-2.jpg, room-3.jpg
│
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── main.js             # JavaScript functionality
├── netlify.toml        # Netlify deployment configuration
└── README.md           # Project documentation
```

## 🎨 Design Highlights

- **Color Scheme**:
  - Primary: Deep Navy Blue (`#0f1a2c`)
  - Accent: Golden Yellow (`#f6ac0f`)
  - Text: Dark Slate (`#0f172a`) & Light Slate (`#64748b`)
  - Background: Off-white (`#f8fafc`)

- **Typography**:
  - Headings: Playfair Display (Elegant serif)
  - Body: Poppins (Modern sans-serif)

- **Layout**:
  - Mobile-first responsive design
  - Breakpoints: 480px, 768px, 1024px
  - CSS Grid & Flexbox for flexible layouts

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd hotel-website
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. **View the website**
   - Navigate to `http://localhost:8000` (or your chosen port)

## 📱 Responsive Breakpoints

- **Mobile**: < 480px (Single column layout)
- **Tablet**: 480px - 768px (Two column grid)
- **Desktop**: 768px - 1024px (Multi-column layouts)
- **Large Desktop**: > 1024px (Optimized spacing and layouts)

## 🌐 Deployment

The project is configured for deployment on **Netlify**:

- **Configuration**: `netlify.toml` includes redirect rules for SPA routing
- **Deploy**: Push to GitHub and connect to Netlify, or use Netlify CLI:
  ```bash
  netlify deploy --prod
  ```

## 🎯 Key Sections

1. **Header/Navigation**: Fixed navigation bar with logo and menu items
2. **Hero Section**: Full-width header with booking form overlay
3. **About Section**: Hotel information with feature cards
4. **Rooms**: Three room types with pricing and descriptions
5. **Video Intro**: Embedded video showcasing hotel amenities
6. **Features**: Six key features with icons and descriptions
7. **Menu**: Food menu items with images and descriptions
8. **Footer**: Contact information, services links, and social media icons

## 💡 JavaScript Features

- **Mobile Menu Toggle**: Opens/closes navigation menu on mobile devices
- **Icon Toggle**: Switches between hamburger and close icons
- **Scroll Animations**: Reveals content as user scrolls using ScrollReveal library
- **Smooth Scrolling**: Native smooth scroll behavior for anchor links

## 🎨 CSS Features

- **CSS Variables**: Centralized color and typography management
- **Flexbox & Grid**: Modern layout techniques for responsive design
- **Transitions**: Smooth hover effects and state changes
- **Media Queries**: Comprehensive responsive design across all breakpoints
- **Custom Animations**: Fade-in and slide-up effects

## 📝 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔮 Future Enhancements

- [ ] Backend integration for booking functionality
- [ ] Database integration for room availability
- [ ] Payment gateway integration
- [ ] User authentication and accounts
- [ ] Admin dashboard for room management
- [ ] Booking confirmation emails
- [ ] Multi-language support
- [ ] Dark mode toggle

## 👨‍💻 Development

This project was built using vanilla web technologies without any build tools or frameworks, making it lightweight and fast-loading. The codebase is clean, well-organized, and easy to understand, making it perfect for learning and further development.

## 📄 License

This project is open source and available for learning purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📧 Contact

For inquiries, please reach out through the contact information provided in the website footer.

---

**Built with ❤️ using HTML, CSS, and JavaScript**



