# EliteCart


# Next.js eCommerce Application

## Introduction
This is a complete eCommerce application built using **Next.js**, **Tailwind CSS**, and **Clerk** for authentication. It includes a full-fledged shopping experience, cart functionality, order processing, and a seller dashboard.


## 📸 Screenshots / Demo  

![Screenshot 2025-03-26 092706](https://github.com/user-attachments/assets/c86d850e-7e25-4616-8ded-f79dc2905388)



![Screenshot 2025-03-26 092910](https://github.com/user-attachments/assets/cc5e280d-3fdd-4a81-9e4f-2cb3593f67a5)



![Screenshot 2025-03-26 092955](https://github.com/user-attachments/assets/b0c25c98-18db-449d-a96a-bb5be97eef2f)

## Tech Stack
- **Next.js** - Server-side rendering and static site generation
- **Tailwind CSS** - Utility-first CSS framework
- **Clerk** - Authentication and user management

- **Redux Toolkit** - State management for cart and authentication

## Features
### Customer
- Browse and search for products
- View product details with images and pricing
- Add products to cart and update quantities
- View order history and order details

### Authentication
- Sign up, login, and logout with Clerk
- Role-based access control (Customer, Seller)

### Seller Dashboard
- Add, edit, and remove products
- Manage inventory and stock levels
- View and manage customer orders
- Track order fulfillment status

## Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/mohankumar01012005/EliteCart
   cd ecommerce-nextjs
   ```
2. **Install dependencies**
   ```sh
   npm install  # or yarn install
   ```
3. **Set up environment variables**
   Create a `.env.local` file and add the necessary credentials:
   ```env
   NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_key
   CLERK_API_KEY=your_clerk_backend_key
   DATABASE_URL=your_database_url
   ```
4. **Run the development server**
   ```sh
   npm run dev  # or yarn dev
   ```

## Deployment
- **Vercel** - Recommended for deployment


## Contact
For inquiries, visit https://github.com/mohankumar01012005/EliteCart.

