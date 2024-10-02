
# Honnbites

**Honnbites** is a fast and efficient food ordering platform built using the MERN stack, tailored for the vibrant food culture of the Konkan coast. With a clean UI and seamless user experience, it's designed for speed and simplicity, offering local residents an intuitive way to order food from their favorite restaurants.

## Features

- **Lightning-Fast**: Optimized for quick order placement and browsing.
- **Tailored for Konkan Coast**: Focused on serving local tastes and preferences.
- **Responsive Design**: Mobile-first approach, ensuring smooth usability on any device.
- **Secure Payments**: Integrated with Stripe for safe and fast transactions.
- **Customizable UI**: Styled with ShadCN components and Tailwind CSS for a modern look and feel.
- **Real-Time Order Tracking**: Keep users updated with real-time status of their orders.
- **User Authentication**: Secure login and sign-up process with JWT.
- **Admin Panel**: Manage restaurants, orders, and users efficiently.

## Tech Stack

- **Frontend**:
  - React.js
  - Tailwind CSS (for styling)
  - ShadCN (for custom UI components)
  - TypeScript (for type safety)
  
- **Backend**:
  - Node.js
  - Express.js
  - TypeScript (for type safety)

- **Database**: 
  - MongoDB (NoSQL database)
  
- **Payment Gateway**:
  - Stripe (for handling secure payments)

- **Authentication**:
  - JWT (JSON Web Token)

- **Deployment**: 
  - Hosted on render

## Installation and Setup

### Backend

1. Clone the backend repository:
   ```bash
   git clone https://github.com/Aaronvern/HonnBites-Backend.git
   cd backend
   ```

2. Install server dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file in the root of the backend directory with the following:
     ```bash
     MONGO_URI=<your-mongodb-uri>
     JWT_SECRET=<your-jwt-secret>
     STRIPE_SECRET_KEY=<your-stripe-secret-key>
     STRIPE_PUBLISHABLE_KEY=<your-stripe-publishable-key>
     ```

4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend

1. Clone the frontend repository:
   ```bash
   git clone https://github.com/Aaronvern/HonnBites-Frontend.git
   cd frontend
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

3. Start the frontend server:
   ```bash
   npm start
   ```

## Usage

1. **Homepage**: Users can browse through a list of restaurants and dishes available in the Konkan region.
2. **Order Placement**: Select dishes, add them to the cart, and checkout using Stripe for secure payment.
3. **Order Tracking**: Real-time updates on the order status, from confirmation to delivery.
4. **Admin Panel**: Manage restaurant listings, menu items, and order statuses.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements, suggestions, or bug fixes.

## License

This project is licensed under the MIT License.
