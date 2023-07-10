# Fast React Pizza Co.

This is a React application that showcases a menu of delicious pizzas offered by Fast React Pizza Co. It provides a user-friendly interface to view the available pizzas, their ingredients, prices, and images. Customers can easily place an order online or visit the restaurant during opening hours.

## Features

- View a variety of authentic Italian pizzas.
- Each pizza is accompanied by a mouthwatering image, a name, a list of ingredients, and its price.
- Pizzas that are sold out are indicated accordingly.
- Place an order online with just a click of a button.
- Check the opening hours of the restaurant.

## Installation

1. Clone the repository:

   ```
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```
   cd react-pizza-app
   ```

3. Install the dependencies:

   ```
   npm install
   ```

4. Start the development server:

   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` to view the application.

## Usage

- Upon launching the application, you will be greeted with the header displaying the restaurant name.
- The menu section showcases a list of pizzas available.
- Each pizza is represented by an image, name, ingredients, and price.
- If a pizza is sold out, it will be visually marked as such.
- You can place an order by clicking the "Order" button in the footer section.
- The footer also displays the restaurant's opening hours.

## Customize

You can customize the application by modifying the `pizzaData` array in the `index.js` file. Each pizza object in the array represents a different pizza and contains the following properties:

- `name`: The name of the pizza.
- `ingredients`: The list of ingredients used in the pizza.
- `price`: The price of the pizza.
- `photoName`: The filename of the pizza image located in the `pizzas` directory.
- `soldOut`: A boolean value indicating whether the pizza is sold out or not.

You can add, remove, or modify the pizza objects in the array to reflect your desired menu.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

Please ensure that your code adheres to the existing code style and includes appropriate tests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- The pizza images used in this application are for illustrative purposes only and belong to their respective owners.

Feel free to explore, enjoy, and order some mouthwatering pizzas from Fast React Pizza Co.!
