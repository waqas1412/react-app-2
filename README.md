# 🍽️ Food Order App

A modern, responsive food delivery application built with React that allows users to browse delicious meals, add them to cart, and manage their orders seamlessly.

![React](https://img.shields.io/badge/React-18.0.0-blue?style=for-the-badge&logo=react)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![CSS Modules](https://img.shields.io/badge/CSS%20Modules-Enabled-green?style=for-the-badge&logo=css3)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Features

- 🍕 **Delicious Meal Selection** - Browse a curated collection of high-quality meals
- 🛒 **Shopping Cart** - Add items to cart with quantity management
- 💰 **Real-time Pricing** - Dynamic price calculations and total updates
- 🎨 **Modern UI/UX** - Clean, responsive design with smooth animations
- 📱 **Mobile Responsive** - Optimized for all device sizes
- ⚡ **Fast Performance** - Built with React 18 for optimal performance
- 🔄 **State Management** - Efficient cart state management with Context API

## 🚀 Live Demo

[![Demo](https://img.shields.io/badge/Live%20Demo-View%20App-green?style=for-the-badge)](https://your-demo-link.com)

## 📸 Screenshots

<div align="center">
  <img src="screenshot-desktop.png" alt="Desktop View" width="400"/>
  <img src="screenshot-mobile.png" alt="Mobile View" width="200"/>
</div>

## 🛠️ Tech Stack

- **Frontend Framework:** React 18
- **Styling:** CSS Modules
- **State Management:** React Context API + useReducer
- **Build Tool:** Create React App
- **Testing:** Jest + React Testing Library

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/food-order-app.git
   cd food-order-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🏗️ Project Structure

```
src/
├── components/
│   ├── Cart/           # Shopping cart components
│   ├── Layout/         # Header and layout components
│   ├── Meals/          # Meal display components
│   └── UI/             # Reusable UI components
├── store/              # Context and state management
├── assets/             # Images and static files
└── App.js              # Main application component
```

## 🎯 Key Components

### 🍽️ Meals Section
- **MealsSummary:** Hero section with app description
- **AvailableMeals:** Displays meal cards with pricing
- **MealItem:** Individual meal component with add to cart functionality

### 🛒 Cart System
- **Cart:** Modal overlay for cart management
- **CartProvider:** Context provider for cart state
- **HeaderCartButton:** Cart icon with item count badge

### 🎨 UI Components
- **Card:** Reusable card component
- **Modal:** Overlay modal system
- **Input:** Form input components

## 🔧 Available Scripts

| Script | Description |
|--------|-------------|
| `npm start` | Runs the app in development mode |
| `npm test` | Launches the test runner |
| `npm run build` | Builds the app for production |
| `npm run eject` | Ejects from Create React App |

## 🧪 Testing

```bash
# Run tests in watch mode
npm test

# Run tests with coverage
npm test -- --coverage
```

## 📱 Responsive Design

The application is fully responsive and optimized for:
- 📱 Mobile devices (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1024px+)

## 🎨 Styling

- **CSS Modules** for component-scoped styling
- **Responsive design** with mobile-first approach
- **Smooth animations** for enhanced user experience
- **Modern color scheme** and typography

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Create React App](https://create-react-app.dev/)
- Icons and styling inspiration from modern design systems
- React community for best practices and guidance

## 📞 Contact

- **GitHub:** [@yourusername](https://github.com/yourusername)
- **Email:** your.email@example.com
- **LinkedIn:** [Your Name](https://linkedin.com/in/yourprofile)

---

<div align="center">
  <p>Made with ❤️ and ☕</p>
  <p>If you find this project helpful, please give it a ⭐</p>
</div>
