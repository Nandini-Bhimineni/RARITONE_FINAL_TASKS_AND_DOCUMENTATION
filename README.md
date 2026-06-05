RARITONE BACKEND SYSTEM

Summer Internship 2026
whole project Link : https://github.com/Nandini-Bhimineni/Raritone-Project-Backend

A scalable and modular backend system developed for the Raritone virtual fashion platform using Node.js, Express.js, MongoDB, and Cloudinary.

The project provides authentication, product management, user management, virtual try-on support, avatar management, order processing, and future AI integration capabilities.


---

Project Overview

Raritone is a virtual fashion platform designed to improve online shopping experiences through:

Personalized Shopping

Virtual Try-On Support

Avatar Management

Product Recommendations

User Measurements

AI-Ready Architecture



---

Technology Stack

Backend

Node.js

Express.js


Database

MongoDB

Mongoose


Authentication

JWT

Google OAuth


Cloud Services

Cloudinary

Multer


Security

Helmet

Rate Limiting

Validation Middleware


Tools

Git

GitHub

Postman



---

Project Structure

Raritone-Project-Backend/
│
├── config/
│   ├── cloudinary.js
│   └── db.js
│
├── controllers/
│   ├── authController.js
│   ├── avatarController.js
│   ├── cartController.js
│   ├── googleAuthController.js
│   ├── imageController.js
│   ├── measurementController.js
│   ├── orderController.js
│   ├── productController.js
│   ├── profileController.js
│   ├── tryOnController.js
│   ├── wardrobeController.js
│   └── wishlistController.js
│
├── middleware/
│   ├── authMiddleware.js
│   ├── errorMiddleware.js
│   ├── roleMiddleware.js
│   ├── uploadMiddleware.js
│   └── validate.js
│
├── models/
│   ├── Avatar.js
│   ├── cart.js
│   ├── Image.js
│   ├── measurement.js
│   ├── order.js
│   ├── product.js
│   ├── ProductMapping.js
│   ├── Profile.js
│   ├── TryOn.js
│   ├── user.js
│   ├── Wardrobe.js
│   └── Wishlist.js
│
├── routes/
│   ├── authRoutes.js
│   ├── avatarRoutes.js
│   ├── cartRoutes.js
│   ├── imageRoutes.js
│   ├── measurementRoutes.js
│   ├── orderRoutes.js
│   ├── productRoutes.js
│   ├── profileRoutes.js
│   ├── tryOnRoutes.js
│   ├── wardrobeRoutes.js
│   └── wishlistRoutes.js
│
├── validators/
│   ├── authValidator.js
│   ├── avatarValidator.js
│   ├── loginValidator.js
│   ├── productValidator.js
│   ├── registerValidator.js
│   └── tryOnValidator.js
│
├── utils/
│   ├── cloudinaryUpload.js
│   └── generateToken.js
│
├── uploads/
├── app.js
├── server.js
├── package.json
└── README.md


---

Modules Implemented

Authentication Module

Features:

User Registration

User Login

JWT Authentication

Refresh Tokens

Google OAuth

Role-Based Access Control



---

Product Module

Features:

Add Product

Update Product

Delete Product

View Products

Search Products



---

Wishlist Module

Features:

Add To Wishlist

Remove From Wishlist

View Wishlist



---

Wardrobe Module

Features:

Add Wardrobe Item

View Wardrobe

Delete Wardrobe Item



---

Profile Module

Features:

View Profile

Update Profile

Preferences Management



---

Cart Module

Features:

Add To Cart

View Cart

Remove Cart Items



---

Order Module

Features:

Create Orders

View Orders

Update Order Status



---

Measurement Module

Features:

Save Measurements

Retrieve Measurements

Delete Measurements



---

Avatar Module

Features:

Create Avatar

View Avatar

Delete Avatar

User Avatar Management



---

Virtual Try-On Module

Features:

Try-On Request Handling

Future AI Integration Support

Avatar-Based Workflow



---

Product Mapping Module

Features:

Product Relationships

Recommendation Support

Similar Product Mapping



---

Security Features

JWT Authentication

Google OAuth

Helmet Security

Rate Limiting

Protected Routes

RBAC

Validation Middleware



---

Database Relationships

User

Profile

Wishlist

Cart

Orders

Measurements

Avatar


Product

Wishlist

Cart

Orders

ProductMapping



---

Testing

Testing Tool

Postman


Testing Performed

CRUD Operations

Authentication Testing

API Validation

Route Testing

Error Handling



---

Final Internship Deliverables

Submitted Documents

✅ Presentation (PPT)

✅ Technical Documentation

✅ Project Summary Report

✅ Key Learnings Report

✅ Challenges & Solutions Report

✅ Suggestions for Raritone Report

✅ Updated GitHub Repository

✅ README Documentation


---

Team Contributions

Nandini Bhimineni

Team Lead

Backend Integration

Cart Module

Order Module

Measurement Module

Avatar Module

Product Mapping Module

Database Relationships

API Testing & Verification

Cloud Infrastructure Research

Scalability Planning

Documentation Coordination


Vagdevi Malineni

Authentication Module

JWT Security

RBAC

Profile Module

Wardrobe Module


Bharath Kumar

Authentication Support

Wishlist Module

API Validation

Security Enhancements


Vishnu Vardhan Reddy

Wishlist Module

Virtual Try-On Module

Authentication Support


Meka Hrishi Teja Chowdary

Product Module

Product APIs

Order Module

Virtual Try-On Module


Nainisha Bandari

Profile Module

Wardrobe Module

User Preferences



---

Future Enhancements

AI Avatar Generation

AI Virtual Try-On

Recommendation Engine

Redis Caching

Docker Deployment

Kubernetes

AWS Deployment

Real-Time Notifications



---

Conclusion

The Raritone Backend System successfully provides a secure, scalable, and modular backend foundation for a virtual fashion platform while preparing the system for future AI-powered features, advanced personalization, and cloud scalability.
