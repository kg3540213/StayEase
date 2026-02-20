# StayEase

StayEase is a full-stack web application designed to simplify the process of finding, listing, and reviewing vacation rentals. Built with Node.js, Express, and EJS, StayEase provides a seamless experience for both property owners and travelers.

## Features

- **User Authentication:** Secure signup and login for users.
- **Listings Management:** Create, edit, view, and delete property listings.
- **Reviews:** Users can leave reviews and ratings for listings.
- **Advanced Seeding:** Pre-populated data for listings, users, and reviews for easy testing and demonstration.
- **Responsive UI:** Modern, mobile-friendly interface using EJS templates and custom CSS.
- **Category Filtering:** Browse listings by categories.
- **Error Handling:** Custom error pages and robust error management.

## Project Structure

```
app.js                  # Main application entry point
cloudConfig.js          # Cloud configuration (e.g., for image uploads)
middleware.js           # Custom middleware functions
package.json            # Project dependencies and scripts
schema.js               # Data validation schemas
controllers/            # Route controllers for listings, reviews, users
init/                   # Database seeding scripts
models/                 # Mongoose models for MongoDB
public/                 # Static assets (CSS, JS, images)
routes/                 # Express route definitions
utils/                  # Utility functions and custom errors
views/                  # EJS templates for UI
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kg3540213/StayEase.git
   cd StayEase
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables as needed (e.g., MongoDB URI, cloud configs).
4. Seed the database (optional, for demo data):
   ```bash
   node init/seedUsers.js
   node init/seedListingsAndReviews.js
   ```
5. Start the server:
   ```bash
   npm start
   ```
6. Visit `http://localhost:3000` in your browser.

## Folder Details
- **controllers/**: Business logic for listings, reviews, and users.
- **init/**: Scripts to initialize and seed the database.
- **models/**: Mongoose schemas for MongoDB collections.
- **public/**: Static files (CSS, JS, images).
- **routes/**: Express route handlers.
- **utils/**: Helper functions and custom error classes.
- **views/**: EJS templates for rendering UI.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

