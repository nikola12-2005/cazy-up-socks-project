# Cozy Up Socks

A responsive front-end e-commerce project for a fictional sock subscription brand, built with a product listing, product details, shopping cart, and payment flow.

**Live demo:** https://nikola12-2005.github.io/cazy-up-socks-project/

## Pages

### Product List
Displays available products in a responsive grid, each with an image, title, short description, and a "View Details" button leading to the full product page.

- **Design choice:** a grid layout keeps products organized and consistent across devices, with large images and short descriptions to draw attention.
- **Built with:** Bootstrap for the responsive grid, Font Awesome for icons.

### Product Details
Shows products side by side (Colourful Stripes and Funky Dots), each with a large image, a detailed description, and an "Add to Cart" button.

- **Design choice:** separate boxes for each product keep the layout clean and easy to scan. The Add to Cart button sits inside a light blue container so it stands out.
- **Built with:** Bootstrap for the responsive layout, JavaScript for the Add to Cart action (confirms with an alert).

### Shopping Cart
Lists everything added to the cart with quantity controls and a remove option, plus a running total and a button through to checkout.

- **Design choice:** a simple, table-style layout keeps details easy to read, with quantity and remove controls placed right next to each product.
- **Built with:** JavaScript to update quantities and remove items dynamically, Bootstrap for responsiveness.

### Payment
A form for cardholder name, card number, expiry date and CVV, with a submit button.

- **Design choice:** fields are presented one after another so it's clear what's needed at each step, keeping the page uncluttered.
- **Built with:** Bootstrap for the responsive form, JavaScript for validation. (This is a demo form, no real payment processor is connected.)

## Design summary
The site aims for an intuitive, clear purchasing flow from browsing to checkout, staying responsive and interactive across desktop, tablet, and mobile.

## Tech stack
HTML, CSS, JavaScript, Bootstrap 5

## Screenshots
_(add a `screenshots` folder to this repo with your images, then reference them here, e.g.)_

![Product list](screenshots/product-list.png)
![Payment page](screenshots/payment.png)
