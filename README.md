# DAY-6---DEPLOYMENT-PREPARATION-AND-STAGING-ENVIRONMENT-SETUP
Date Completed: January 21, 2025
Project Repository: https://github.com/Tahaimran56/NikeEcommerce
Live URL: https://nike-ecommercetaha.vercel.app/

1. Project Overview
The Nike Ecommerce project is an online shopping platform where users can browse products, add items to their cart, and proceed to checkout. The project integrates modern tools and technologies such as Next.js, Sanity CMS, and Tailwind CSS for a fully functional, responsive, and dynamic user experience.

2. Key Features
1. Dynamic Product Pages: Displays products dynamically from Sanity CMS.
2. Cart Functionality: Add, remove, and update items in the cart.
3. Responsive Design: Fully responsive for all devices.
4. Checkout Process: Integrated billing, shipping, and payment flow.
5. Order History: Stores and displays user order history.
6. Environment-Specific Variables: Managed securely through .env and deployed to Vercel.

3. Technologies Used
- Frontend Framework: Next.js (App Router)
- Styling: Tailwind CSS
- Backend CMS: Sanity.io
- Deployment: Vercel
- State Management: React's Context API
- Version Control: Git and GitHub

4. Development Steps
Step 1: Project Initialization
- Created the project directory and initialized it with Next.js.
- Installed dependencies: npm install next react react-dom tailwindcss @sanity/client
- Set up Tailwind CSS for styling.

Step 2: Sanity CMS Integration
- Created a Sanity project for managing products.
- Set up schemas for Product data type.
- Integrated Sanity into the project with API keys.

Step 3: Navbar Component
- Designed a responsive Navbar with links to key pages (Home, Products, Cart, Wishlist, Help, Profile).
- Added a dynamic badge to the Cart link to display the number of items in the cart.

Step 4: Product Pages
- Products Grid: Displayed a list of products fetched from Sanity.
- Dynamic Product Pages: Used dynamic routing to create individual pages for products with details such as name, price, and description.

Step 5: Cart Functionality
- Implemented a Cart Context API to manage cart state globally.
- Features added: Add products to the cart, remove products from the cart, display total price and quantity, navigate to the checkout page from the cart.

Step 6: Checkout Flow
- Created a three-step checkout process: Billing Address, Shipping Address, Payment Details.
- Final submission shows a success message with order details.

Step 7: Profile Page
- Designed a profile page to display user details, saved addresses, and order history.

Step 8: Deployment to GitHub
- Initialized Git and created a GitHub repository.
- Followed Git commands to push code.

Step 9: Deployment to Vercel
- Deployed the application to Vercel.

5. Challenges Solved
- Remove Button Issue: Fixed the functionality to allow removal of specific products from the cart.
- Dynamic Badge on Cart: Implemented a real-time badge showing the number of items in the cart.
- Checkout Process: Integrated a fully functional multi-step checkout system.
- Build Errors: Resolved missing module imports and file path issues.
- Sanity Data Testing: Used testsanity.js for debugging data fetch from Sanity.

6. Commands Used
Local Development: npm run dev
Build and Production: npm run build
Git Commands: git init, git add ., git commit -m "Initial commit", git push -u origin main

7. Final Outputs
GitHub Repository: https://github.com/Tahaimran56/NikeEcommerce
Live Deployment: https://nike-ecommercetaha.vercel.app/

8. Future Enhancements
1. User Authentication: Add login/signup functionality.
2. Real Payment Integration: Integrate Stripe or PayPal.
3. Search and Filter: Add search and filtering capabilities to the product page.
4. Improved Order Management: Allow users to track orders and manage returns.


# Save the PDF to a file
output_file = "/mnt/data/Nike_Ecommerce_Project_Documentation.pdf"
pdf.output(output_file)
