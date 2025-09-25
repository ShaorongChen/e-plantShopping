# Paradise Nursery - Plant Shopping App

A React-based e-commerce application for purchasing plants and gardening supplies.

## Features

- **Landing Page**: Welcome screen with call-to-action button
- **Product Listing**: Browse available plants and gardening products
- **Responsive Design**: Works on mobile and desktop devices
- **Smooth Transitions**: Animated page transitions between landing and product views

## Project Structure

```
src/
├── App.jsx              # Main application component
├── ProductList.jsx      # Component for displaying products
├── AboutUs.jsx          # About us section component
├── App.css              # Main styling file
└── index.js             # Entry point
```

## Getting Started

### Prerequisites

- Node.js (v20 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
2. Navigate to the project directory:
   ```bash
   cd 5-FrontEndWithReact/e-plantShopping
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

Start the development server:
```bash
npm run preview
```

The application will be available at `http://localhost:4173`

## Usage

1. **Landing Page**: View the welcome message and about us section
2. **Get Started Button**: Click to navigate to the product listing page
3. **Product List**: Browse available plants and gardening supplies
4. **Home Button**: Navigate back to the landing page from the product list

## Components

### App.jsx
Main application component that manages:
- State for showing/hiding product list
- Navigation between landing and product views
- Rendering of landing page and product list sections

### ProductList.jsx
Displays the collection of products with:
- Product cards
- Responsive grid layout
- Navigation back to home

### AboutUs.jsx
Shows information about the nursery:
- Company mission statement
- Values and services

## Styling

CSS is used for styling with:
- Flexbox for layout
- CSS transitions for animations
- Responsive design principles
- Clean, nature-inspired color scheme