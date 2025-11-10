🐠 Aquarium Website

The Aquarium Website is a complete **full-stack web application** developed to provide an online shopping experience for aquarium enthusiasts. It allows users to browse, add to cart, and purchase aquarium-related products while providing admin and backend functionalities for product and order management. The project is designed with a clean, modern interface using React.js (Vite) for the frontend and a robust Node.js (Express + Prisma + MongoDB)backend to ensure seamless performance and scalability.  

This project includes all essential features such as authentication, OTP verification, cart and order handling, database integration, responsive design, and real-time updates — making it a perfect demonstration of a modern full-stack e-commerce system.  

The frontend is powered by React.js using Vite as the build tool for fast development and optimized deployment. It includes reusable components like Navbar, Hero Section, Cards, Product Details, Cart Section, and Checkout. The design is implemented using Tailwind CSS to ensure responsiveness across all devices. The routing between pages is managed using React Router DOM and API calls are integrated with the backend using Axios.  

The backend is developed with Node.js and  Express.js featuring a structured REST API architecture connected to a  MongoDB database through Prisma ORM. It handles all business logic, user authentication, OTP verification, product management, category organization, order storage, and secure user data operations. The backend is capable of handling dynamic API requests efficiently and is structured for future scalability.  

💡 Key Features

- 🛒 E-commerce Functionality – Add to Cart, Checkout, and Order Management.  
- 🔐 User Authentication & OTP Verification– Secure login and registration.  
- 🐠 Product Display & Details– View aquarium items, categories, and details.  
- 💳 Order & Payment Flow – Complete purchase cycle simulation.  
- 📦 Backend Integration – Real-time data fetched from the database.  
- 🧭 Responsive UI Design – Optimized for desktop and mobile using Tailwind CSS.  
- ⚙️ Modular Architecture – Clear separation of frontend and backend logic.  
- 🗄️ Database Connectivity – Prisma ORM connected to MongoDB for data storage.  
- 📈 Scalable API Design – Built with RESTful standards for future expansion.  

---

The frontend runs locally at:  
👉 http://localhost:5173/

The backend runs locally at:  
👉 http://localhost:3000/  

The main technologies and tools used in this project are:

Frontend Technologies:

React.js, Vite, Tailwind CSS, React Router DOM, Axios, JavaScript (ES6), HTML5, CSS3  

Backend Technologies: 

Node.js, Express.js, Prisma ORM, MongoDB, JWT Authentication, Nodemailer (for OTP), REST API architecture  

Development Tools:

VS Code, Git, GitHub, npm (Node Package Manager), Postman for API testing, and GitHub Actions for version control and CI/CD.  

Deployment Platforms (optional for future use):

Vercel (for Frontend) and Render or Railway (for Backend).  


To run the project locally on your Linux system:  

1. Clone your GitHub repository
   bash
   git clone https://github.com/coding-lax/Aquarium-website-.git
   cd Aquarium-website-
   
2. Setup the backend
   cd Backend
   npm install
   npm start
   This will start the backend server at http://localhost:3000

3. Setup the Frontend

cd ../FrontEnd
npm install
npm run dev
Once it compiles successfully, open http://localhost:5173 in your browser.
