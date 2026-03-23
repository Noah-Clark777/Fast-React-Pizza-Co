
Fast React Pizza Co – Online Ordering App

A modern pizza ordering application that allows users to browse a dynamic menu, manage a shopping cart, and place orders through a seamless, real-world user flow.
This project focuses on scalable state management, API integration, and building a production-style e-commerce experience using React.



Features:
* Browse the dynamic pizza menu from an external API
* Add, remove, and update items in a shopping cart
* Place orders with delivery details
* Optional geolocation for address autofill
* Real-time UI updates with global state
* Track orders using a unique order ID
* Fully responsive design


Tech Stack:
* Frontend: React
* State Management: Redux Toolkit
* Routing: React Router
* Styling: Tailwind CSS
* Build Tool: Vite
* API: REST API (menu + order endpoints)


Architecture & Key Concepts:
* Global State with Redux Toolkit:
Centralized cart and user state for predictable updates and scalability
.
* Feature-Based Folder Structure:
Organized by domain (cart, menu, order, user) for maintainability.

* API Layer Abstraction:
All network requests are handled in a dedicated service layer to separate concerns.

* Async Data Handling:
Fetches menu data and submits orders using REST API calls.

* Routing & Navigation:
Multi-page flow with clean URLs for menu, cart, and order tracking.

* Form Handling & Validation:
Captures and validates user input for order creation.
