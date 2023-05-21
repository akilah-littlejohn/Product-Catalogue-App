# Product-Catalogue-App

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/angular-2fzmkj)




# Angular FakeStore Product Catalogue

This project is an Angular-based web application that fetches and displays product data from the FakeStore API. The application consists of two main components: `ProductListComponent` and `ProductDetailComponent`, orchestrated by the `FakeStoreService` service.

## Components

### ProductListComponent

This component displays a list of products fetched from the FakeStoreService. It presents relevant information about each product, such as its image, title, and price. Users can interact with the products in the list, such as clicking on a product to view its details.

### ProductDetailComponent

This component showcases detailed information about a specific product. It receives the product details from the FakeStoreService and displays them, including the product image, title, description, price, and other relevant information. Users can navigate to this component by clicking on a product in the ProductListComponent.

## Service

### FakeStoreService

This service is responsible for interacting with the FakeStore API. It includes methods to fetch product data and categories from the API. The service acts as a bridge between the Angular application and the external API.

## Getting Started

1. Install Node.js and npm if they are not already on your machine.

2. Install Angular CLI globally on your machine by running `npm install -g @angular/cli`.

3. Clone the repository to your machine using `git clone`.

4. Navigate to the project directory and install dependencies using `npm install`.

5. Start the development server with `ng serve`.

6. Visit `http://localhost:4200` in your browser.

## Project Goals

1. Implement FakeStoreService to fetch product data and categories from the FakeStore API.
2. Display a list of products in the ProductListComponent using data fetched from the FakeStoreService.
3. Create the ProductDetailComponent to show detailed information about a specific product retrieved from the FakeStoreService.

## Bonus Goals

1. Implement lazy loading for the ProductDetailComponent to load it only when the user navigates to view specific product details.
2. Implement error handling for API requests, displaying appropriate error messages or fallback content in case of failures.

