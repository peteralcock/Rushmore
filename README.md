# "I saved Latin. What did you ever do?"
![Screenshot](public/rushmore-936098835.jpg?raw=true "Hero")

## Welcome to Rushmore
Teach yourself (and others) whatever you want. Hop on the Magic Schoolbus and instantly create your own lesson plans with AI. And then sell your courses online! This project is a SaaS web application that allows users to create AI-generated courses with ease. It features user authentication, course creation, subscriptions, and much more.

## Features
"I saved Latin. What did YOU ever do?"

### Highlights
- **Landing Page**: A modern SaaS-like landing page showcasing features, pricing, and testimonials.
- **Authentication**: Users can log in or register using their email.
- **Social Authentication**: Log in or register using Google and Facebook.
- **Welcome Email**: New users receive a welcome email after registration.
- **Forgot Password**: Users can recover their accounts via their email address.
- **Home**: View all AI-generated courses.
- **Night Mode**: Enable or disable night mode.
- **Create Course**: Users can create a course by:
  - Entering a course title
  - Optional sub-topics
  - Selecting the number of topics to generate
  - Choosing the type of course (Image or Video)
- **Generated Topics**: AI will generate a list of topics and sub-topics based on the user's input.
- **Course Types**:
  - **Video & Theory Course**: AI-generated courses containing video and theory content.
  - **Image & Theory Course**: AI-generated courses containing images and theory content.
- **AI Chat Bot**: Users can ask questions and clear doubts during the course via an AI chatbot.
- **Export/Download Course to PDF**: Export or download the entire course as a PDF.
- **Profile Management**: Users can manage their profile settings.
- **Course Certificates**:
  - Earn a course completion certificate and download it anytime.
  - Receive certificates via email.
- **Subscription Management**:
  - Choose from Free, Monthly, or Yearly pricing plans.
  - Manage subscription plans from the user's profile.
  - Payment methods include PayPal, Stripe, Paystack, Flutterwave, and Razorpay.
  - Users can enter their payment details and receive receipts via email.
  - Cancel, modify, or set up recurring payments for subscriptions.
- **Additional Pages**:
  - Features, About, Contact, Terms, Privacy, Cancellation, Refund, and Billing & Subscription pages are available.
- **Logout**: Log out from any session.
- **Responsive Design**: The web app is fully responsive and works on mobile devices and any screen size.

![Screenshot](/splash.png?raw=true "Preview")

### Admin Panel Features
- **Dashboard**: Admins can track the number of users, courses, recurring revenue, total revenue, paid/free users, and video/image courses.
- **Users**: View and manage all registered users.
- **Courses**: View and manage all courses created by users.
- **Paid Users**: View all paid users.
- **Admin Users**: View and manage all admin users.
- **Contact Messages**: View messages sent via the contact page.
- **Page Management**: Admins can edit the Terms, Privacy, Cancellation, Refund, and Billing & Subscription pages.

## Requirements

To run and develop this SaaS web application, you will need the following tools:

- **VS Code** – Free
- **Node.js** – Free
- **GIT** – Free
- **MongoDB** – Free
- **Gemini API** – Free
- **GitHub** – Free
- **Unsplash** – Free
- **PayPal** – Free
- **Razorpay** – Free
- **Paystack** – Free
- **Flutterwave** – Free
- **Google Login** – Free
- **Facebook Login** – Free
- **Render.com** – Free
- **Firebase Hosting (Optional)** – Free
- **Any Other Web Hosting (Optional)** – Paid

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables for authentication (Google, Facebook), payment methods (PayPal, Stripe, etc.), and MongoDB in an `.env` file:
   ```bash
   MONGO_URI=<your-mongo-uri>
   GOOGLE_CLIENT_ID=<your-google-client-id>
   GOOGLE_CLIENT_SECRET=<your-google-client-secret>
   FACEBOOK_APP_ID=<your-facebook-app-id>
   FACEBOOK_APP_SECRET=<your-facebook-app-secret>
   PAYPAL_CLIENT_ID=<your-paypal-client-id>
   PAYPAL_CLIENT_SECRET=<your-paypal-client-secret>
   STRIPE_SECRET_KEY=<your-stripe-secret-key>
   ```

5. Start the application:
   ```bash
   npm start
   ```





