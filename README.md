# Build Full-ECommerce Website By Next.js, PostgreSQL  and Tailwind css

|                |                                                          |
| -------------- | -------------------------------------------------------- |
| Tech           | Next.js, PostgreSQL, Nodejs |
| UI             | Tailwind                           |
| Database       | PostgreSQL                   |
| Payment        | PayPal                                   |
| Authentication | Auth.js, Google Auth                      |
| Others         | uploadthing, resend           |
.app/)



## Features of this application

- creating e-commerce website pages by next.js server components
- designing header, footer, sidebar, menu and search box by shadcn and tailwind
- quick view products in modals using nextjs parallel routes with intercepting routes
- create database models by drizzle orm and postgres database
- handling form inputs by react-hook-forms and zod data validator
- updating data by server actions without using any api
- managing shopping cart using http cookies on server side
- handling authentication and authorization by next-auth
- creating customer dashboard to update profile and track orders
- and implement a fully-functional admin dashboard with beautiful charts and handling products, orders and users

- More Features
User Authentication
Users can sign up as either a seller or a buyer.
Authentication and session management implemented for login and sign-up processes.
Passwords are securely hashed, and input is validated and sanitized.
Seller Functionality
Sellers can:
Add products with details like name, category, description, price, and discount.
Edit or delete their products.
Sellers are restricted to managing only their own products.
Buyer Functionality
Buyers can:
Search for products by name or category.
Add products to their cart and remove them    as needed.
Input Validation and Sanitization
All user inputs are validated and sanitized before being stored in the database to ensure security and data integrity.
Error Handling
Proper error handling and meaningful error messages for various scenarios such as invalid inputs, unauthorized access, and non-existent resources.
Custom error pages for client-side routing.

## Run Locally

 Create .env.local File

   - duplicate .env.example and rename it to .env.local

 Setup PostgreSQL

   - Vercel PostgreSQL
     - Create database at https://vercel.com/docs/storage/vercel-postgres
     - In .env.local file update POSTGRES_URL to db url
   - OR Local PostgreSQL
     - Install it from https://www.postgresql.org/download
     - In .env.local file update POSTGRES_URL to db url

Install and Run

   ```shell
     npm install
     npm run dev
   ```

Seed Data

   ```shell
     npx tsx ./db/seed
   ```

Admin Login

   - Open http://localhost:3000
   - Click Sign In button
   - Enter admin email "admin@example.com" and password "123456" and click Sign In


Deployment Link-https://sethcram.pythonanywhere.com/BestBuySearch/login/


Outlook of the website
![image](https://github.com/user-attachments/assets/42601128-b949-43eb-8d8a-53401ea3304e)



