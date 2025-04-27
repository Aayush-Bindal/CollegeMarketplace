# College Marketplace 🎓🛍️

A **classified marketplace** specifically designed for college students. Buy and sell used items like **lab coats**, **calculators**, **notes**, and more within your college. Freshers can browse and buy, while only verified students with a `@college.edu` email can post items for sale. 

At night, the app transforms into a **Night Market** where students can buy and sell items **within their hostels**.

## Features 🌟

- **Login/Signup** using Google OAuth for `@college.edu` email verification (for posting listings).
- **Phone-based authentication** via Firebase OTP for easy login (for browsing/buying).
- **Item Listings**: Browse and search for items for sale, like books, lab coats, calculators, etc.
- **Night Market Mode** 🌙: At night, view items available in your specific hostel.
- **Listing Approval**: Only users with a verified `@college.edu` email can post listings.
- **User Profiles**: View and manage your items and preferences.

## Tech Stack 🔧

- **Frontend**: React (with Vite for fast development 🚀)
- **Backend**: Flask (Python 🐍)
- **Database**: PostgreSQL (scalable and relational 📊)
- **Authentication**:
  - Google OAuth2 for **college email verification** 📧
  - Firebase Phone Authentication for **OTP-based login** 📱
- **Hosting**:
  - Backend: Google Cloud or Heroku ☁️
  - Frontend: Vercel, Netlify, or Firebase Hosting 🔥

## Setup 🛠️

### Prerequisites 📝

- Python 3.7+
- Node.js and npm (for frontend)
- PostgreSQL (locally or cloud)
- Firebase Account (for OTP-based authentication)
- Google Firebase Project (for Google OAuth2 integration)

---

### Backend Setup (Flask) 🖥️

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/college-marketplace.git
   cd college-marketplace/backend
