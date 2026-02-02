# Empire: E-Commerce Streetwear Website

Empire is a modern online shopping platform built to deliver a seamless and stylish streetwear fashion experience. The system allows customers to browse urban-inspired apparel, purchase securely, and engage with exclusive drops and curated collections.

---

## Introduction

Empire is designed to provide a convenient and user-friendly platform where customers can shop for streetwear apparel. It focuses on culture, exclusivity, creativity, and lifestyle through:

- Limited drops  
- Exclusive collaborations  
- Lookbooks and fashion inspiration  

The system uses **native PHP (custom MVC)**, **MySQL**, and **JavaScript** to ensure security, flexibility, and smooth performance.

---


## Technologies Used

### **Backend**
- PHP (Native)
- Custom MVC Framework
- MySQL Database

### **Frontend**
- HTML  
- CSS  
- JavaScript  
- Bootstrap

### **Hosting**
- **Netlify** (static landing page hosting)

---

## System Description

Empire is designed to deliver a clean and modern shopping experience.

### **User-Side Features**
- Secure login & registration with **OTP email verification**  
- Username and password validation  
- Product browsing with search, filters, and sorting  
- Product details with images, description, price, sizes, stock  
- Add to cart & wishlist  
- Checkout system  
- Order tracking & order history  
- User profile editing  
- Settings with privacy pages  
- Notifications for order status  

### **Admin-Side Features**
- Dashboard overview  
- Product management (add/edit/update/delete)  
- Category management  
- Customer management  
- Orders management  
- Inventory monitoring  
- Analytics & sales reports  

---

## Security Features

### Authentication & Security
- **Turnstile Captcha Protection**
  - Cloudflare Turnstile integration on login and registration forms
  - Intelligent bot detection with invisible challenges for legitimate users
  - Privacy-focused approach without tracking
  - Prevents brute-force and automated attacks

- **OTP Email Verification**
  - One-time password sent via email during registration
  - Email address verification requirement
  - Enhanced account security

- **Password Security**
  - Secure password hashing using bcrypt algorithm
  - Salted password storage

- **Session Management**
  - Secure session handling
  - Automatic session expiration
  - Protected against session hijacking

- **Rate Limiting**
  - Limited login attempts
  - Turnstile captcha enforcement after failed attempts
  - Protection against credential stuffing attacks

  ### Admin Management & Disciplinary Actions
- **User Account Management**
  - **Account Blocking**: Temporary restriction of user access with specified duration
  - **Account Deactivation**: Permanent removal of user access and privileges
  - **Action Logging**: Comprehensive audit trail of all admin disciplinary actions
  - **Reason Documentation**: Mandatory reason specification for all disciplinary actions

---

## Test Accounts (Demo Login Credentials)

The following accounts are provided for testing and evaluation of the system:

### **Admin Account**
- **Email:** admin321@gmail.com  
- **Password:** 123  

### **User Account**
- **Email:** renz@gmail.com  
- **Password:** gabpogi123  

> *Note: These credentials are for demonstration purposes only and should not be used in a production environment.*

---


## Website URL

**Static Landing Page (Netlify):**  
https://empire-landingpage.netlify.app/

---


## Source Codes

Google Drive Link:  
https://drive.google.com/drive/folders/1vCeMzyiYxKFgwDoxfqsXmaNiDuG0rM50?usp=sharing

---

## Authors

- Gabriel Winfred Vargas  
- Renz Alvarez  
- Mandy Francisco  
- James Duran  

Course: **IT31WM – Web Development Management**

