# My Fake Store Project

## Introduction
This project is a simple web page that fetches product data from an online API (Fake Store API) and displays it in a clean, organized layout using HTML, TailwindCSS, and JavaScript. The main features of this project include a product search, a modal to show more details about each product, and links to social media in the footer.

## Features

### 1. **Header Section**
- **Logo**: On the far left, there's an image logo that represents the store.
- **Search Bar**: The search bar is placed in the center of the header, allowing users to type in product names and see matching products as they type.
- **Buttons**: There are three buttons on the right side of the header — Account, Orders, and a Shopping Cart icon — designed to simulate a real e-commerce website.

### 2. **Product Display**
- The main section of the page shows a grid of products fetched from the Fake Store API. Each product is displayed inside a card with the following details:
  - Product image
  - Product title
  - Product price
  - A "View Details" button

### 3. **View Details Modal**
- When you click on the "View Details" button, a modal (popup window) appears, showing more detailed information about the selected product, such as the image, title, description, and a random quantity.

### 4. **Live Search**
- As the user starts typing in the search bar, the list of products updates automatically to show only those that match the entered search term. This helps users find products quickly and easily.

### 5. **Footer Section**
- The footer includes links to Facebook, Twitter, and Instagram, with small icons for each social media platform. Each link takes you to the respective social media page.

## Styling
- I used **TailwindCSS** for styling, which allowed me to quickly create a responsive design.
- The **background image** gives the page a pleasant look, and the header, footer, and product cards all have a subtle transparency to make the text and content stand out.
- **Buttons** have a custom color (`#802c6e`), and they change to a slightly darker color when hovered over, giving them an interactive feel.

## Technologies Used
- **HTML**: For the structure of the page.
- **TailwindCSS**: For the design and layout.
- **JavaScript**: To fetch products from the Fake Store API, display them, and handle the live search and modal functionality.
- **Font Awesome**: For the shopping cart icon in the header.

## Summary
This project simulates a simple online store layout with key features like a product grid, search functionality, and a product details modal. It helped me practice integrating an API with frontend technologies and managing dynamic content on a webpage.
