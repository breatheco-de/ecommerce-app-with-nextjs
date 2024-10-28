<!-- hide -->
# Build a Basic E-commerce App with Next.js!
<!-- endhide -->

## 🌱 How to start this project?

Do not clone this repository because we are going to use a different template.

> ⚠ You will need to have Node.js installed if you do it locally, but all of that is already installed on Codespaces or Gitpod!

## 📝 Instructions

### Step 1: Set Up the Project

- [ ] Set up the base project by following the steps given in the official Next.js documentation: [https://nextjs.org/docs/getting-started/installation](https://nextjs.org/docs/getting-started/installation).

- [ ] Follow the instructions in the repository's README to set up your development environment.

### Step 2: Plan the App Structure

- [ ] Define the pages your application will have, such as:

  - Main page displaying a list of products.
  - Product detail page.
  - Shopping cart.
  - Checkout page.

- [ ] Decide how you will structure the components and routes in Next.js.

### Step 3: Create the Product List

- [ ] Create a sample dataset for your products. You can create a `products.json` file with an array of objects representing the products.

```json
[
  {
    "id": 1,
    "name": "Product 1",
    "price": 19.99,
    "image": "/images/product1.jpg",
    "description": "Description of Product 1"
  }
  // ...more products
]
```

- [ ] In the main page (`pages/index.js`), import the product list and display each product with its name, image, and price.

### Step 4: Create the Product Detail Page

- [ ] Create a dynamic page for the product details in `pages/product/[id].js`.

- [ ] Use `getStaticPaths` and `getStaticProps` to generate static pages for each product.

### Step 5: Implement the Shopping Cart

- [ ] Use the `useState` or `useContext` hook to manage the shopping cart state.

- [ ] Create a context (`CartContext`) to share the cart state throughout the application.

- [ ] Wrap your application with the `CartProvider` in `_app.js`.

### Step 6: Create the Cart Page

- [ ] Create a `/cart` page that displays the products added to the cart.

- [ ] Allow the user to modify the quantity or remove products from the cart.

### Step 7: Create the Checkout Page

- [ ] Create a `/checkout` page where the user can enter their details and confirm the purchase.

- [ ] It is not necessary to process real payments; you can simulate the process.

### Step 8: Improve the User Interface

- [ ] Use CSS or a library like Tailwind CSS or Bootstrap to improve the design of your application.

- [ ] Ensure that the application is responsive and works well on different devices.

## Bonus Section

### Additional Features to Practice and Improve the Project

1. **Filtering and Search:** Implement functionalities to filter products by category and search by name.

2. **Quantity in Cart:** Allow the user to select the quantity of each product in the cart.

3. **Data Persistence:** Store the cart state in `localStorage` so it persists when the page is reloaded.

4. **User Authentication:** Implement a basic registration and login system.

5. **API Integration:** Connect your application with a real or simulated API to fetch the products.

6. **SEO Optimization:** Take advantage of Next.js's server-side rendering features to improve SEO.

7. **Pagination:** If you have many products, add pagination to the product list.

8. **Payment Processing:** Integrate a service like Stripe to process real payments.

Explore different enhancements to make your e-commerce application more complete and functional!
