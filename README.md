# Library Management System

## Project Overview
A well-renowned school requires the development of a **Library Management System**, accessible via a website. The system allows adding, categorizing, updating, and managing book collections efficiently. Users can borrow and return books while keeping track of transactions. The interface is user-friendly, ensuring smooth operations and easy access to library resources.

## Live Site Link
[Provide your deployed live site link here]

## Key Features
- **Authentication System**: Email/password-based login and registration with Google authentication.
- **User Roles**: Only authorized users can add, update, or borrow books.
- **Book Management**:
  - View all available books with search and filter functionalities.
  - Add new books with image, category, quantity, rating, and description.
  - Update book details (image, name, author, category, rating, etc.).
- **Borrowing System**:
  - Users can borrow books, with an automatic decrement in quantity.
  - Borrow button disabled when book quantity reaches zero.
  - Borrowed books displayed with return date.
  - Return functionality increases book quantity.
- **Protected Routes**:
  - `All Books`, `Add Book`, and `Borrowed Books` pages are private routes.
  - Unauthorized users are redirected to the login page.
- **Dynamic Page Titles**: Updates based on route changes.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop.
- **Loading State**: Displays a spinner while fetching data.
- **Toast Notifications**: Alerts for CRUD operations and user actions.
- **404 Page**: Custom error page for invalid routes.
- **JWT Authentication**: Secures API endpoints and user authentication.
- **Book Filtering & View Toggle**: 
  - Show only available books.
  - Toggle between card and table views.

## Deployment Guidelines
- Ensure the server is running without CORS/404/504 errors.
- Live site should be error-free on page reloads.
- Firebase domain authorization is required if using Netlify/Surge.
- Private routes should not redirect logged-in users to the login page upon reload.

## Technologies Used
### Client-Side:
- React.js
- Tailwind CSS
- React Router
- Firebase Authentication
- Axios
- React Hook Form
- Framer Motion (Optional Animation)
- Swiper.js (For Banners & Sliders)

### Server-Side:
- Node.js
- Express.js
- MongoDB with Mongoose
- JSON Web Token (JWT)

## Environment Variables
Create a `.env` file and add the following:
```
VITE_apiKey=AIzaSyBYr7ehEHDyz2v9wsO4fVSteWnVaCOxIAk
VITE_authDomain=library-auth-e40e1.firebaseapp.com
VITE_projectId=library-auth-e40e1
VITE_storageBucket=library-auth-e40e1.firebasestorage.app
VITE_messagingSenderId=831167534850
VITE_appId=1:831167534850:web:5f4b092239a74e4d66141b
```

## Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone [client_repo_url]
   git clone [server_repo_url]
   ```
2. **Navigate to the Directories**
   ```bash
   cd client
   cd server
   ```
3. **Install Dependencies**
   ```bash
   npm install
   ```
4. **Run the Client & Server**
   ```bash
   npm start (for client)
   npm run dev (for server)
   ```

## GitHub Repositories
- **Client**: https://library-management-syste-ac963.web.app/
- **Server**:(https://server-81x31vzr8-mahabub2030s-projects.vercel.app/)

## Optional Features (Highly Recommended)
- Implement animations using Framer Motion.
- Limit users to borrowing a maximum of 3 books at a time.
- Use Axios interceptors for network request handling.
- Implement Swiper.js for banners and sliders.
- Use React Hook Form for form handling.

## Contribution
Feel free to contribute by submitting pull requests. Make sure to follow best practices and write meaningful commit messages.

## License
This project is open-source and free to use.
## Reache me 
mahabubalam407557@gmail.com

---

**Developed with ❤️ for a seamless library management experience.**