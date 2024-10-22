# Pizza Menu App

A simple React application that displays a dynamic pizza menu. The app showcases a list of pizzas with details like name, ingredients, price, and image, along with a footer that indicates whether the pizzeria is currently open based on the time. It demonstrates React components, props, conditional rendering, and basic state management.

## Features

- **Dynamic Menu**: Displays a list of pizzas with their ingredients, price, and photo.
- **Sold-Out Handling**: Conditionally renders "SOLD OUT" for unavailable pizzas.
- **Operational Hours**: Shows whether the pizzeria is open based on the current time and allows users to place an order during open hours.
- **Component-Based Structure**: Demonstrates the use of React components, props, and conditional rendering.

## Project Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pizza-menu-app.git
   cd pizza-menu-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open the app in your browser:
   ```
   http://localhost:3000
   ```

## Components

- **App**: Main container component that renders the header, menu, and footer.
- **Header**: Displays the app title.
- **Menu**: Shows the list of pizzas and handles conditional rendering based on the menu data.
- **Pizza**: Renders individual pizza details and handles sold-out state.
- **Footer**: Displays whether the pizzeria is open based on current time.
- **Order**: Component that shows the order button and opening hours when the pizzeria is open.

## Data

The pizza data is stored in an array called `pizzaData` in the following structure:

```javascript
const pizzaData = [
  {
    name: "Focaccia",
    ingredients: "Bread with italian olive oil and rosemary",
    price: 6,
    photoName: "pizzas/focaccia.jpg",
    soldOut: false,
  },
  // Additional pizza objects
];
```

## Customization

- **Add or Modify Pizzas**: You can add or modify pizzas by editing the `pizzaData` array in the code.
- **Operating Hours**: Adjust the `openHour` and `closeHour` constants in the `Footer` component to change the pizzeria's operational hours.

## Technologies Used

- React (with ReactDOM v18)
- JSX for component structure
- CSS for styling
