# 🛒 Digi Store – E-Commerce Platform

## 📌 Main Content

- **Frontend (React.js)**:
  - Built using React with functional components
  - Responsive layout using simple CSS
  - Hosted on Netlify

- **Backend (Node.js, Express.js)**:
  - RESTful APIs built with Express
  - Authentication and middleware handling with JWT
  - Hosted on Render

- **Database (MongoDB Atlas)**:
  - Models managed using Mongoose
  - Secure data handling for products, users, orders, and OTPs

---

## 📖 About This Project

1. **Modern Tech Stack (MERN):**
   - Combines MongoDB, Express.js, React.js, and Node.js
   - Supports scalable and maintainable development

2. **OTP-Based Order Verification:**
   - Users must verify email via OTP before order is placed
   - Orders confirmed only after successful email verification

3. **QR Code Integration for Delivery:**
   - Orders include QR codes for delivery staff to scan
   - Secure status update after email re-verification

4. **Admin Dashboard:**
   - Admin can view, edit, delete products
   - Can manage orders by status (Pending, Confirmed, Cancelled, Delivered)

5. **Product & Slider Management:**
   - Admin can upload product and slider images using Cloudinary
   - Real-time product editing and slider updates

---

## 🎓 Skills Learned from this Project:

1. **Backend API Development:**
   - Built secure and scalable REST APIs
   - Implemented middlewares for role-based access control

2. **Authentication & Security:**
   - JWT used for stateless authentication
   - bcrypt used for secure password and OTP storage

3. **Email Integration with Nodemailer:**
   - Automated OTP emails for user verification
   - Order confirmation details sent to user's email

4. **Cloud Image Storage:**
   - Cloudinary used for efficient image hosting
   - Managed product and slider image URLs in the database

5. **Search Optimization & Debouncing:**
   - Implemented search suggestions using debounced input
   - Improved user experience and performance on product listing

6. **QR Code Usage in Delivery System:**
   - Integrated QR generation for each order
   - Delivery staff can scan and verify orders before marking as delivered
