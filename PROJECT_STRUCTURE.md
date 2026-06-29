# Stone Heritage Website Structure

## Project Overview
A modern, responsive website for Stone Heritage - a premium stone craftsmanship and design company in Mukteshwar, India.

## ✨ Features

### Pages
- **Home**: Hero section, services overview, and call-to-action
- **About**: Company history, team, and core values
- **Services**: Detailed service offerings and process
- **Contact**: Contact form and information
- **404**: Custom not found page

### Components
- **Header**: Responsive navigation with mobile menu
- **Footer**: Links, contact info, and social media
- **Hero**: Dynamic hero sections with images
- **Card**: Reusable card component for services

### Technology Stack
- React 19.1.0
- React Router DOM 7.6.3
- Tailwind CSS 4.1.11
- Framer Motion 12.34.0
- Material-UI Icons 7.2.0
- Vite 7.0.4

## 🎨 Styling
- Tailwind CSS for utility-based styling
- Framer Motion for smooth animations
- Custom animations for scroll effects
- Responsive design for all devices

## 🚀 Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## 📁 Project Structure

```
src/
├── components/
│   ├── Header.jsx      # Navigation header
│   ├── Footer.jsx      # Footer with links
│   ├── Hero.jsx        # Hero section
│   └── Card.jsx        # Reusable card
├── pages/
│   ├── Home.jsx        # Homepage
│   ├── About.jsx       # About page
│   ├── Services.jsx    # Services page
│   ├── Contact.jsx     # Contact page
│   └── NotFound.jsx    # 404 page
├── hooks/
│   └── useScrollAnimation.js
├── utils/
│   └── constants.js
├── App.jsx             # Main app component
├── App.css             # Global styles
└── main.jsx            # Entry point
```

## 🎯 Key Features

✅ Fully Responsive Design
✅ Smooth Animations & Transitions
✅ SEO Friendly Structure
✅ Fast Loading with Vite
✅ Modern UI/UX
✅ Contact Form
✅ Mobile Navigation Menu
✅ Professional Layout

## 📝 Notes

- Update contact information in `/pages/Contact.jsx`
- Replace placeholder images with actual company photos
- Update social media links in `Footer.jsx`
- Customize colors in `App.css` and Tailwind config

---

Built with ❤️ by Stone Heritage
