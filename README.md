# E-Commerce_follow_along

This project is a full-stack e-commerce platform developed using the MERN stack: MongoDB, Express.js, React.js, and Node.js. It integrates scalable APIs, secure authentication, and robust product management functionalities to provide a seamless user experience.


1. User Authentication
The e-commerce platform includes secure login and registration functionalities with JSON Web Tokens (JWT). This ensures that user sessions are properly managed, and sensitive data is accessed only by authorized individuals.

Register: Enables new users to sign up.
Login: Authenticates users and provides a secure session using JWT tokens.

2. Product Management
The product management system allows administrators to add, update, retrieve, and delete products efficiently.

Add Product: Allows adding new products with necessary details.
Update Product: Enables updating product details such as price, description, or images.
Retrieve Products: Provides an easy way to fetch product listings.
Delete Product: Removes products from the database when necessary.

3. Order Management
The platform offers a comprehensive system to manage customer orders, ensuring a seamless purchasing experience.

Create Order: Allows users to place orders for products.
Update Order: Provides options to update order details (e.g., shipping address, quantity).
View Order: Facilitates viewing order history and status.

4. RESTful APIs
The e-commerce platform uses RESTful API design, which organizes interactions between the client and server into standard HTTP methods (GET, POST, PUT, DELETE). This ensures a clean and scalable communication process with the database.
Each endpoint is designed to handle specific tasks, such as retrieving product data or managing user accounts.

5. Scalable Backend
The backend of the e-commerce platform is developed using Node.js and Express.js, making it highly efficient in handling multiple concurrent requests. This allows for fast performance even with a growing user base.

6. Responsive Frontend
The frontend is built using html, css, java script React.js, providing a dynamic and responsive user interface. React.js enhances user interaction by offering components that handle views efficiently, resulting in a smoother, faster, and more intuitive experience for customers.

#### Milestone 1: Initialize Project Repository  

This milestone focused on setting up the GitHub repository to serve as the central hub for the e-commerce project's development. By creating the repository and initializing it with a README file, the project gained a clear starting point with version control, ensuring organization and collaboration as the development progresses.

#### Milestone 2: Project Setup and Login Page 
This milestone focused on establishing the foundational structure and core functionalities of the project. 

Key tasks included:
1. **Structuring the Project:** Created a clear folder hierarchy to organize frontend and backend components efficiently.
2. **Frontend Setup:** Initialized a React app and configured Tailwind CSS for streamlined styling.
3. **Backend Setup:** Built a Node.js server to handle API requests and backend logic.
4. **Development Tools:** Integrated optional extensions to enhance productivity.
5. **Login Page:** Designed and developed a functional, styled login page as the first user-facing feature of the application.

#### Milestone 3: Backend Structure and Server Setup  

This milestone focused on setting up the backend infrastructure and establishing a robust foundation for server-side operations. 

Key tasks included:  
1. **Organizing Backend Files:** Created a structured hierarchy for routes, controllers, models, middleware, and utilities to ensure scalability and maintainability.  
2. **Server Setup:** Built a backend server using Node.js and Express, configured to listen on a designated port.  
3. **Database Integration:** Connected MongoDB for efficient data storage and verified the connection between the server and database.  
4. **Error Handling:** Implemented clear error messages to enhance debugging and provide better feedback for users.  

This milestone establishes a functional backend and prepares the project for future development.  

#### Milestone 4: User Management and File Upload  

This milestone focuses on implementing user data handling and file upload functionality. 

Key achievements include:  
1. **User Model:** Defined a blueprint for storing user data in the database, ensuring a consistent structure for user-related information.  
2. **User Controller:** Developed logic to manage user operations such as adding new users and retrieving user information.  
3. **File Upload Setup:** Integrated and configured Multer to enable file uploads (e.g., user profile images) and store them efficiently in the application.  

By completing this milestone, the application now supports user management and file uploads, enhancing its core functionality.  

#### Milestone 5: Signup page and Validation  

This milestone focuses on creating a user-friendly Sign-Up page and implementing essential form validation. Key tasks include:  

1. **Frontend UI:** Designed a clean and intuitive Sign-Up page where users can provide their details (Name, Email, Password) to create an account.  
2. **Form Validation:** Ensured user inputs are validated before submission, checking for proper email formats and secure passwords to prevent errors and maintain data integrity.  

By completing this milestone, the application now has a functional and secure user registration interface.  


#### Milestone 6: User Data Security and Password Encryption  

This milestone focused on enhancing user data security by implementing password encryption and securely storing user information in the database.  

**Key tasks included:**  

1. **Password Encryption:**  
   - Integrated `bcrypt` to hash user passwords during the signup process.  
   - Ensured that only the hashed password is stored in the database, enhancing security.  

2. **Storing Complete User Data:**  
   - Implemented secure storage of user details such as name, email, and other necessary information.  
   - Ensured that sensitive data is handled appropriately while keeping passwords encrypted.  

This milestone strengthens the security of user authentication, preventing unauthorized access to sensitive information. 

#### Milestone 7: User Authentication and Login  
This milestone focused on implementing a secure login system by verifying user credentials and ensuring proper authentication.  

**Key tasks included:**  

1. **Create Login Endpoint:**  
   - Developed an API endpoint to accept user credentials (email/username and password).  
   - Retrieved the corresponding user from the database for authentication.  

2. **Validate Password:**  
   - Used `bcrypt` to hash the entered password.  
   - Compared the hashed input with the stored hashed password to authenticate users.  

This milestone enhances security by ensuring only authenticated users gain access.  


#### Milestone 8: Product Card Component and Display  

This milestone focused on designing and implementing a reusable card component to display products effectively on the products page.  

**Key tasks included:**  

1. **Create the Card Component:**  
   - Designed a reusable card component with props for product details (e.g., name, image, price).  
   - Ensured a visually appealing layout to enhance user experience.  

2. **Design the Homepage Layout:**  
   - Implemented a grid or flexbox layout for structured product display.  
   - Used mapping to dynamically render multiple product cards with unique details.  

This milestone improves product presentation, creating a clean and user-friendly browsing experience. 

Here’s your README update for Milestone 9:  

---

#### Milestone 9: Product Creation Form  

This milestone focuses on building a form to collect product details and handle multiple image uploads.  

**Key Objectives:**  
1. **Form Implementation:** Designed a structured form to input essential product details.  
2. **Image Upload:** Enabled multiple image uploads for each product.  
3. **Data Storage:** Ensured product details are saved in the database for display on the product homepage.  

**Additional Considerations:** 
- Implementing admin access to restrict product uploads.  
- Creating a shop profile for users who can upload products.  

This milestone establishes a foundation for product management in the e-commerce platform.

### Milestone 10: Product Schema & API Endpoint  

This milestone focuses on defining the product schema and creating an API endpoint to validate and store product details in MongoDB.  

**Key Objectives:**

1. **Product Schema:**  
   - Define the product data structure using Mongoose.  
   - Implement field validations (e.g., required fields, data types).  

2. **API Endpoint:**  
   - Build a POST endpoint to receive and store product details.  
   - Validate input before saving to MongoDB.  

**Additional Considerations:**
- Implement admin access for product uploads.  
- Allow only shop-profile users to upload products.  

This milestone ensures data integrity and establishes backend functionality for product management.

### Milestone 11: Dynamic Product Display  

This milestone makes the home page dynamic by fetching and displaying product data from MongoDB.  

#### Key Tasks:  
- Create an API endpoint to fetch all product data.  
- Implement a function to receive and display data in the frontend.  
- Use the product card component for dynamic rendering.  

This ensures smooth data flow between backend and frontend.