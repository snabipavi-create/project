# User-Authentication-System-
GitHub README Content
# User Authentication System using Node.js and MongoDB
## Project Description
This project is a secure User Authentication System where users can register, 
login, and access protected pages. Passwords are hashed using bcrypt.js, and 
session management is implemented using express-session.
## Features
- User Registration with hashed passwords
- User Login and validation
- Session-based access control
- Logout functionality
- Protected Home Page
## Tools & Technologies
- Node.js, Express.js
- MongoDB, Mongoose
- bcrypt.js, express-session
- HTML, CSS
- VS Code


##Setup Instructions
 1. Clone the Repository
```bash.
git clone https://github.com/<your-username>/user-auth-system.git
cd user-auth-system
2. Install Dependencies
npm install
3. Start MongoDB
Make sure MongoDB server is running locally:
mongod
4. Run the Application
node server.js
Or, for automatic reload:
npx nodemon server.js
5. Open in Browser
Visit http://localhost:3000 to the application


Project Report
Content:
1. Project Title:
User Authentication System using Node.js and MongoDB
2. Abstract:
This project demonstrates a secure web-based user authentication system. Users can register, log 
in, and access protected pages. The system ensures password security using hashing and 
maintains session management to prevent unauthorized access.
3. Objectives:
• Implement a secure login and registration system.
• Protect user passwords using bcrypt.js.
• Maintain user sessions for authenticated access.
• Provide a simple and user-friendly interface for demonstration.
4. Scope:
• Can be extended to large-scale applications requiring secure authentication.
• Can integrate features like JWT, email verification, and password reset.
5. Tools & Technologies:
• Node.js, Express.js
• MongoDB, Mongoose
• HTML, CSS
• bcrypt.js, express-session
• VS Code, Chrome/Edge
6. System Architecture:
• Frontend: HTML/CSS forms for registration and login
• Backend: Node.js and Express handle API routes
• Database: MongoDB stores user data securely
• Session Management: express-session maintains login state
7. Methodology:
1. Set up project structure in VS Code.
2. Install dependencies (express, mongoose, bcryptjs, express-session).
3. Create MongoDB database and collection for users.
4. Build registration and login forms.
5. Hash passwords before saving to MongoDB.
6. Implement session management to track authenticated users.
7. Test all flows: registration, login, protected page access, and logout.
8.Conclusion:
The project successfully demonstrates a working authentication system with secure password 
storage and session management. It serves as a foundation for more advanced user management 
systems.
