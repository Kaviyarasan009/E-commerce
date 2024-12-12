# *ShopEZ*  

## *Description*  
ShopEZ is a full-stack e-commerce platform designed to simplify online shopping for users. Built with the MERN stack (MongoDB, Express.js, React.js, and Node.js), it provides a seamless shopping experience with features like product browsing, secure payments, and order management. The application also includes an admin dashboard for managing inventory, users, and orders efficiently.  

---

## *Features*  

### *User Features*  
- User registration and secure login (JWT-based authentication).  
- Product browsing with category and search filters.  
- Add products to the cart, adjust quantities, and place orders.  
- Secure online payments via integrated payment gateway (e.g., Stripe).  
- View order history and track order status.  

### *Admin Features*  
- Manage inventory: Add, update, or delete products.  
- Monitor and update order statuses.  
- Manage users and their roles.  

### *Additional Features*  
- Responsive design for all devices.  
- Real-time inventory updates.  
- Product ratings and reviews (upcoming feature).  

---

## *Technologies Used*  

### *Client*  
- React.js  
- Redux for state management  
- Axios for API communication  

### *Server*  
- Node.js  
- Express.js for building REST APIs  

### *Database*  
- MongoDB with Mongoose for schema modeling  

### *Authentication*  
- JSON Web Tokens (JWT) for secure user sessions  

### *Payment Gateway*  
- Stripe API for handling online transactions  

### *Deployment*  
- Client: Netlify or Vercel  
- Server: Heroku or Render  
- Database: MongoDB Atlas  

---

## *Installation and Setup*  

### *Clone the Repository*  
bash  
git clone https://github.com/your-repo/shopez.git  
cd shopez  
  

### *Server Setup*  
1. Navigate to the server directory:  
   bash  
   cd server  
     
2. Install dependencies:  
   bash  
   npm install  
     
3. Create a .env file with the following variables:  
   env  
   MONGO_URI=<Your MongoDB URI>  
   JWT_SECRET=<Your JWT Secret Key>  
   STRIPE_SECRET_KEY=<Your Stripe Secret Key>  
   PORT=5000  
     
4. Start the server:  
   bash  
   npm run dev  
     

### *Client Setup*  
1. Navigate to the client directory:  
   bash  
   cd ../client  
     
2. Install dependencies:  
   bash  
   npm install  
     
3. Start the client:  
   bash  
   npm start  
     

### *Access the Application*  
- Client: http://localhost:3000  
- Server API: http://localhost:5000  

---

## *Team Members*  
1. *Kaviyarasan S*  
   - Role: Server Developer (API development and database management)  

2. *Mithunraj P M*  
   - Role: Full-Stack Developer (Authentication, client-server integration)  

3. *Dinesh Kumar D*  
   - Role: Client Developer (UI/UX and Redux state management)  

4. *Divesh K*  
   - Role: Quality Assurance (Testing and Deployment)  

---

## *Challenges Faced*  
- Ensuring secure payment transactions using Stripe.  
- State management across multiple components in Redux.  
- Optimizing database queries for better performance.  

---

## *Future Enhancements*  
- Introduce AI-driven personalized product recommendations.  
- Add real-time order tracking functionality.  
- Implement a wishlist feature for users.  

---

## *License*  
This project is licensed under the MIT License.  

---
