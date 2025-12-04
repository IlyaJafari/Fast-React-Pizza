# 🍕 Fast React Pizza Co.

A modern pizza ordering application built with React, Redux Toolkit, and React Router. Users can browse the menu, add pizzas to their cart, place orders, and track delivery status—all without requiring authentication.

## ✨ Features

- **No Authentication Required**: Simply enter your name and start ordering
- **Dynamic Menu**: Pizza menu loaded from an external API
- **Cart Management**: Add, remove, and adjust pizza quantities
- **Order Placement**: Simple checkout process with name, phone, and address
- **GPS Location**: Optional geolocation for accurate delivery
- **Priority Orders**: Mark orders as priority for 20% additional fee
- **Order Tracking**: Track your order status using a unique order ID
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🛠️ Tech Stack

- **React** - UI library
- **Redux Toolkit** - State management
- **React Router v6** - Routing and navigation
- **Tailwind CSS** - Styling
- **Vite** - Build tool and dev server

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/IlyaJafari/Fast-React-Pizza.git
```

2. Navigate to the project directory:

```bash
cd Fast-React-Pizza
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

5. Open your browser and visit `http://localhost:5173`

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 🎯 How It Works

### Ordering Process

1. **Enter Your Name**: Start by providing your name on the home page
2. **Browse Menu**: View available pizzas with prices and ingredients
3. **Add to Cart**: Select pizzas and quantities
4. **Checkout**: Provide delivery details (phone, address)
5. **Optional Priority**: Mark order as priority for faster delivery
6. **Track Order**: Use your unique order ID to track delivery status

### Key Features Explained

#### Cart Management

- Add pizzas from the menu
- Increase/decrease quantities
- Remove items
- View total price in real-time

#### Order Priority

- Can be added during checkout or after order placement
- Adds 20% to the total order cost
- Ensures faster preparation and delivery

#### Order Tracking

- Each order receives a unique ID
- Search for your order using the ID
- View order status, estimated delivery time, and order details

## 🗂️ Project Structure

```
Fast-React-Pizza/
├── src/
│   ├── features/
│   │   ├── cart/          # Cart-related components and logic
│   │   ├── menu/          # Menu display components
│   │   ├── order/         # Order creation and tracking
│   │   └── user/          # User-related components
│   ├── services/          # API calls
│   ├── ui/                # Reusable UI components
│   ├── utils/             # Helper functions
│   ├── App.jsx            # Main app component
│   └── store.js           # Redux store configuration
├── public/
└── package.json
```

## 🔑 Core Technologies & Patterns

### Redux Toolkit

- Centralized state management for cart and user data
- Slice-based architecture for better organization
- Thunks for async operations

### React Router v6

- Declarative routing
- Loader functions for data fetching
- Action functions for form submissions
- `useFetcher` for non-navigational form submissions

### Tailwind CSS

- Utility-first styling approach
- Responsive design out of the box
- Custom theme configuration

## 🌐 API Integration

The app integrates with a pizza ordering API for:

- Fetching menu data
- Creating new orders
- Retrieving order details
- Updating order priority

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Ilya Jafari**

- GitHub: [@IlyaJafari](https://github.com/IlyaJafari)

---

Built with ❤️ as a learning project to practice React, Redux, and modern web development patterns.
