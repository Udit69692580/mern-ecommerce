**MERN E-Commerce Application**
This is a full-stack e-commerce application built using the MERN stack (MongoDB, Express.js, React, and Node.js). The application supports user authentication, product management, cart functionality, order processing, and more. It is designed to be fully functional with a deployed frontend and backend.
**Features**
User Authentication: Login, Registration, and Token-based Authentication.
Product Management: Admins can add, update, and delete products.
Shopping Cart: Add/remove items and manage quantities.
Order Management: Place orders, view order history.
Search and Reviews: Search products and leave reviews.
Secure Payments: Integrated with PayPal for payment processing.
**Deployment**
The application is deployed using:
    Frontend: https://mern-ecommerce-1-9zff.onrender.com
    Backend: https://mern-ecommerce-scun.onrender.com
**Prerequisites**
Before setting up the application locally, ensure you have the following installed:
Node.js (v14 or later)
MongoDB
Git
**Local Setup Instructions**
1. Clone the Repository:-git clone <repository-url>
cd <repository-folder>
2. Setup Backend:- cd backend
-npm install 
3.Create a .env file in the backend directory and add the following:-
MONGO_URL=mongodb+srv://<username>:<password>@cluster.mongodb.net/<dbname>
PORT=5000
CLIENT_BASE_URL=http://localhost:5173
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
PAYPAL_CLIENT_ID=your-paypal-client-id
PAYPAL_CLIENT_SECRET=your-paypal-client-secret
4.Start the backend server:-npm start
5.The backend should now be running on http://localhost:5000
**3. Setup Frontend**
   1.Navigate to the frontend folder:-cd frontend
   2.Install dependencies:npm install
   3.Create a .env file in the frontend directory and add the following:-VITE_API_URL=http://localhost:5000
   4.Start the frontend development server:-npm run dev
   5.The frontend should now be running on http://localhost:5173.
 **4.Create a paypal account**
   Make sure you have a paypal account to perform transaction and use that mailID only.
  ** 5.Create a cloudinary account to upload immage**
