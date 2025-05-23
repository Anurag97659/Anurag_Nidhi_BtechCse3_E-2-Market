
---

# E-2 Market

## Team Members
- Anurag Nidhi(2301010174)

## Project Description
**E-2 Market** is an online platform where users can buy and sell second-hand products with ease. The platform allows users to create accounts, manage profiles, post ads for used products, and explore items listed by others. Key features include user authentication, profile management, and a "forgot password" functionality that sends the password directly to the user's registered email. Future improvements include integrating a payment gateway for seamless transactions.

## Link to Video Explanation
[Click here to watch the project demo](https://drive.google.com/file/d/1sza5pt2CwfohmUNF2xhxIEC7fsveS_wf/view?usp=sharing)

## Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: Postman (for API testing), Nodemailer (for email functionality)

## Steps to Run/Execute the Project
1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/e2-market.git
   cd e2-market
   ```

2. **Install server dependencies**  
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies**  
   ```bash
   cd ../client
   npm install
   ```

4. **Setup environment variables**  
   Create a `.env` file inside the `server` folder with the following variables:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   EMAIL_USER=your_email@example.com
   EMAIL_PASS=your_email_password
   ```

5. **Run the server**  
   ```bash
   cd server
   npm run dev
   ```

6. **Run the client**  
   Open a new terminal:
   ```bash
   cd client
   npm start
   ```

7. **Access the Application**  
   Visit `http://localhost:3000` in your browser to use E-2 Market!

---

