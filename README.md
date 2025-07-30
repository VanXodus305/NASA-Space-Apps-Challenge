# 🌌 Celestial Echoes - James Webb Space Telescope Explorer

<div align="center">
  
![James Webb Space Telescope](https://img.shields.io/badge/🛰️%20JWST-Explorer-blue?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-14.2.13-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=for-the-badge&logo=tailwindcss)

**A stunning interactive web application showcasing the wonders of the James Webb Space Telescope**

[🚀 Live Demo](#) | [📖 Documentation](#features) | [🛠️ Installation](#installation)

</div>

---

## 🌟 Overview

**Celestial Echoes** is an immersive web experience that brings the cosmos to your fingertips. Built for the NASA Space Apps Challenge, this application showcases high-resolution images from the James Webb Space Telescope (JWST) with detailed astronomical data, interactive features, and a captivating user interface that mirrors the beauty of space exploration.

### ✨ Key Highlights

- 🎯 **Interactive Image Gallery** - Browse 50+ high-resolution JWST images with smooth hover effects
- 🔍 **Detailed Image Viewer** - Explore astronomical data including instruments, observation IDs, and mission details
- 📱 **Responsive Design** - Seamless experience across desktop, tablet, and mobile devices
- 🎵 **Ambient Audio** - Optional space-themed background music for enhanced immersion
- 🎨 **Stunning UI/UX** - Modern design with cosmic gradients, glowing effects, and smooth animations
- 🛰️ **3D Model Showcase** - Interactive Blender-created 3D model of the JWST

---

## 🚀 Features

### 🖼️ **Image Gallery**

- **Dynamic Loading**: Fetches real-time data from JWST API
- **Smart Filtering**: Automatically filters out thumbnail images
- **View Toggle**: Switch between condensed and expanded gallery views
- **Hover Effects**: Interactive cards with description overlays
- **Loading States**: Elegant loading animations while fetching data

### 🔬 **Detailed Image Analysis**

- **Instrument Information**: Complete details about JWST instruments used
- **Observation Data**: Unique observation IDs and program information
- **Mission Context**: Background information about each space mission
- **High-Resolution Viewing**: Full-size image viewing with external links

### 🎛️ **Interactive Navigation**

- **Responsive Navbar**: Context-aware navigation with page indicators
- **Audio Controls**: Built-in music player with play/pause functionality
- **Quick Links**: Direct access to NASA resources and external content
- **Smooth Scrolling**: Seamless navigation between sections

### 🎨 **Visual Excellence**

- **Cosmic Gradients**: Space-inspired color schemes and backgrounds
- **Glow Effects**: Strategic lighting effects for enhanced visual appeal
- **Video Backgrounds**: High-quality space footage for immersive experience
- **Animated Elements**: Subtle animations and transitions throughout

### 📊 **State Management**

- **Redux Toolkit**: Efficient state management for image data
- **Real-time Updates**: Dynamic content updates without page refreshes
- **Data Persistence**: Maintains selected image state across navigation

---

## 🛠️ Technology Stack

### **Frontend Framework**

- **Next.js 14.2.13** - React framework with server-side rendering
- **React 18** - Component-based UI library
- **JavaScript/JSX** - Modern ES6+ syntax

### **Styling & Design**

- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **SCSS/Sass** - Enhanced CSS with variables and mixins
- **Bootstrap 5.0.1** - Additional UI components
- **Custom CSS** - Specialized animations and effects

### **State Management**

- **Redux Toolkit 2.2.7** - Simplified Redux state management
- **React Redux 9.1.2** - React bindings for Redux

### **HTTP & API**

- **Axios 1.7.7** - Promise-based HTTP client
- **JWST API** - Real-time telescope data integration

### **Additional Libraries**

- **React Icons 5.3.0** - Comprehensive icon library
- **Framer Motion 11.11.1** - Animation library
- **Classnames 2.3.1** - Conditional CSS class utility

---

## ⚡ Installation

### **Prerequisites**

- Node.js 18+
- npm, yarn, pnpm, or bun package manager

### **Quick Start**

1. **Clone the repository**

   ```bash
   git clone https://github.com/VanXodus305/NASA-Space-Apps-Challenge.git
   cd NASA-Space-Apps-Challenge
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application

### **Available Scripts**

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server
npm run lint     # Run ESLint for code quality
npm run test     # Run tests
```

---

## 🌐 API Integration

The application integrates with the **JWST API** to fetch real-time telescope data:

- **Endpoint**: `https://api.jwstapi.com/all/type/jpg`
- **Authentication**: API key-based authentication
- **Data**: High-resolution images with metadata
- **Filtering**: Automatic exclusion of thumbnail images
- **Processing**: Data transformation for optimal display

---

## 🎨 Design Philosophy

### **Cosmic Aesthetics**

- Deep space color palette with blues and purples
- Gradient overlays mimicking nebulae and star fields
- Subtle glow effects representing celestial bodies

### **User Experience**

- **Intuitive Navigation**: Clear visual hierarchy and logical flow
- **Performance First**: Optimized loading and smooth interactions
- **Accessibility**: Responsive design for all devices
- **Immersive Content**: Video backgrounds and ambient audio

### **Technical Excellence**

- **Modern React Patterns**: Hooks, functional components, and best practices
- **Optimized Performance**: Image optimization and lazy loading
- **Clean Code**: Modular components and separation of concerns
- **Scalable Architecture**: Redux for state management and component reusability

---

## 🔧 Configuration

### **Environment Variables**

Create a `.env.local` file for any sensitive configurations:

```bash
NEXT_PUBLIC_JWST_API_KEY=your_api_key_here
```

### **Tailwind Customization**

The project includes custom Tailwind configurations for:

- Space-themed color palette
- Custom animations and keyframes
- Responsive breakpoints
- Utility classes for cosmic effects

---

## 🚀 Deployment

### **Vercel Deployment (Recommended)**

1. Connect your GitHub repository to Vercel
2. Configure environment variables in Vercel dashboard
3. Deploy with automatic CI/CD pipeline

### **Manual Deployment**

```bash
npm run build    # Build the application
npm run start    # Start production server
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### **Development Guidelines**

- Follow existing code style and conventions
- Add comments for complex functionality
- Test your changes thoroughly
- Update documentation as needed

---

## 📄 License

This project is part of the NASA Space Apps Challenge and is open for educational and non-commercial use.

---

## 🙏 Acknowledgments

- **NASA** for the incredible James Webb Space Telescope mission
- **JWST API** for providing accessible telescope data
- **Space Apps Challenge** for inspiring cosmic innovation
- **Open Source Community** for the amazing tools and libraries

---

<div align="center">

### 🌌 **"Exploring the cosmos, one image at a time"** 🌌

**Made with ❤️ for space exploration and discovery**

[![Next.js](https://img.shields.io/badge/Built%20with-Next.js-000000?style=flat&logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled%20with-Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss)](https://tailwindcss.com/)
[![React](https://img.shields.io/badge/Powered%20by-React-61DAFB?style=flat&logo=react)](https://reactjs.org/)

</div>
