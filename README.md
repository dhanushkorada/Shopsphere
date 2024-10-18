# ShopSphere

ShopSphere is an e-commerce web application that allows users to browse, search, add, update, and delete products. The application is built using Spring Boot for the backend and React for the frontend.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Backend API](#backend-api)
- [Frontend](#frontend)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- View all products and product details.
- Add new products with images.
- Update existing product information.
- Delete products from the inventory.
- Search for products by keywords.

## Technologies Used

- **Backend**: Spring Boot, Java, JPA, Hibernate
- **Frontend**: React, Axios, React Router
- **Database**: H2 Database (or any other preferred database)
- **Image Upload**: MultipartFile for handling images

## Backend API

The backend API exposes various endpoints for product management. Below are the key endpoints:

- `GET /api/products`: Retrieve all products.
- `GET /api/product/{id}`: Retrieve a product by ID.
- `POST /api/product`: Add a new product (requires product details and an image).
- `PUT /api/product/{id}`: Update an existing product (requires updated product details and image).
- `DELETE /api/product/{id}`: Delete a product by ID.
- `GET /api/products/search`: Search for products by keyword.

## Notes:

1. **Update URLs and Paths**: Make sure to replace placeholder URLs (like `https://github.com/yourusername/ecom_project.git`) with the actual URL of your GitHub repository.
2. **Example Usage**: Adjust the example requests to fit your actual API structure.
3. **License**: Add or change the license section based on your project's licensing.
