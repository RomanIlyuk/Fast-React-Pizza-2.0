# 🍕 Fast React Pizza Co

## Modern Pizza Ordering Web Application built with React

## 📖 Project Description

Fast React Pizza Co is a modern single-page application (SPA) that allows users to order pizza online.

The project was developed as one of the largest applications in the React course by Jonas Schmedtmann and focuses on practicing real-world React development patterns.

The application simulates a complete pizza ordering workflow:

1️⃣ Browse the pizza menu
2️⃣ Add pizzas to the cart
3️⃣ Adjust quantities
4️⃣ Create an order
5️⃣ Track the order status

The goal of the project was to gain practical experience with:

modern React architecture

state management

routing

API integration

scalable project structure

## 🚀 Live Features

## 🍕 Dynamic Pizza Menu

The application fetches the pizza menu from an external API and displays available pizzas.

Each pizza contains:

name

description

price

image

availability status

## 🛒 Shopping Cart

Users can manage their cart easily.

Cart functionality includes:

adding pizzas

removing pizzas

increasing quantity

decreasing quantity

calculating total price

The cart state is managed globally with Redux Toolkit.

## 📦 Order Creation

Users can place an order by entering:

name

phone number

address

The order is sent to the API using a POST request.

🔎 Order Tracking

After placing an order, the application generates an order ID.

Users can track their order and see:

order status

delivery estimation

ordered items

## 🧰 Tech Stack

## ⚛️ Frontend

React

React Hooks

Component-Based Architecture

## 🧠 State Management

Redux Toolkit

createSlice

configureStore

useSelector

useDispatch

Redux is used to manage:

cart state

order information

pricing logic

## 🧭 Routing

The project uses React Router for client-side navigation.

Features used:

Nested routes

Dynamic routes

Route loaders

Route actions

Form submissions

Pages implemented:

Home Page

Menu Page

Cart Page

Create Order Page

Order Status Page

## 🌐 API Integration

The application communicates with an external API.

API functionality includes:

fetching pizza menu

creating orders

retrieving order data

Data fetching is implemented using:

fetch

async / await

React Router loaders

## 🎨 Styling

Styling is implemented using Tailwind CSS, a modern utility-first CSS framework.

Tailwind features used:

Flexbox layouts

Responsive design

Utility classes

Typography utilities

Spacing utilities

Hover and focus states

## 🧠 Key React Concepts Practiced

This project focuses on several important React concepts used in production applications.

Component Architecture

The UI is built with reusable components.

Examples:

Button

Loader

Header

MenuItem

CartItem

State Management

Two types of state are used:

Local State

Used for:

form inputs

UI interactions

Managed with:

useState
Global State

Used for:

cart data

order data

Managed with:

Redux Toolkit
Data Fetching

The project uses modern React Router data APIs.

Implemented features:

Route loaders

Route actions

Async data fetching

## Project Structure

The application follows a feature-based architecture which improves scalability and maintainability.

src
│
├── features
│ │
│ ├── cart
│ │ ├── Cart.jsx
│ │ ├── CartItem.jsx
│ │ ├── CartOverview.jsx
│ │ ├── DeleteItem.jsx
│ │ ├── EmptyCart.jsx
│ │ ├── UpdateItemQuantity.jsx
│ │ └── cartSlice.js
│ │
│ ├── menu
│ │ ├── Menu.jsx
│ │ └── MenuItem.jsx
│ │
│ ├── order
│ │ ├── CreateOrder.jsx
│ │ ├── Order.jsx
│ │ ├── OrderItem.jsx
│ │ ├── UpdateOrder.jsx
│ │ └── SearchOrder.jsx
│ │
│ └── user
│ ├── UserName.jsx
│ ├── CreateUser.jsx
│ └── userSlice.js
│
├── services
│ ├── apiGeocoding.js
│ └── apiRestaurant.js
│
├── ui
│ ├── AppLayout.jsx
│ ├── Button.jsx
│ ├── Error.jsx
│ ├── Header.jsx
│ ├── Home.jsx
│ ├── LinkButton.jsx
│ └── Loader.jsx
│
├── utils
│ └── helpers.js
│
├── App.jsx
├── main.jsx
├── store.js
└── index.css

This structure separates logic by application features, which is a common practice in modern React applications.

## 🛠 Installation

1️⃣ Clone the repository

### git clone https://github.com/RomanIlyuk/Fast-React-Pizza-2.0

2️⃣ Navigate to the project folder

### cd fast-react-pizza-co

3️⃣ Install dependencies

### npm install

4️⃣ Start development server

### npm run dev

The app will run locally on:

### http://localhost:5173

## 🎯 Learning Outcomes

By building this project, I practiced:

building real-world React applications

using Redux Toolkit for global state

implementing React Router for navigation

handling API requests

structuring scalable React projects

styling with Tailwind CSS

## 👨‍💻 Author

Developed as part of the React Course by Jonas Schmedtmann.

# ⭐ If you like this project, consider giving it a star on GitHub.
