# GoCamping

GoCamping is a full-stack web application that allows users to share and review campgrounds. The app provides an interactive platform for outdoor enthusiasts to explore, rate, and discuss their favorite camping locations.

## Features

- User Authentication: Sign up, log in, and log out functionality using secure authentication.
- Campground Management: Create, edit, and delete campgrounds with descriptions, locations, and images.
- Reviews and Ratings: Users can leave reviews and ratings for campgrounds.
- Image Uploads: Integrates with Cloudinary for image storage and management.
- Responsive Design: Mobile-friendly and accessible user interface.
- Error Handling: Custom middleware for error handling and validation.

## Tech Stack

- **Back-End**: Node.js, Express.js
- **Front-End**: HTML, CSS, JavaScript, EJS (Embedded JavaScript templates)
- **Database**: MongoDB, Mongoose
- **Authentication**: Passport.js
- **Image Storage**: Cloudinary
- **Version Control**: Git

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/light0-0/GoCamping.git
   cd GoCamping

2. **Install dependencies:**

   ```bash
   npm install
   
3. **Set up environment variables:**

   ```bash
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_KEY=your_cloudinary_key
   CLOUDINARY_SECRET=your_cloudinary_secret
   DATABASE_URL=your_mongodb_url
   SESSION_SECRET=your_secret

4. **Run the application:**

   ```bash
   node app.js

5. **Visit the application:**

   Open your browser and visit http://localhost:3000.

## Usage
- Create an Account: Sign up to create a personal account.
- Add Campgrounds: Share your favorite camping spots by adding new campgrounds with descriptions and images.
- Review Campgrounds: Leave reviews and ratings for campgrounds you've visited.
- Edit or Delete: Modify your campgrounds or delete them if needed.

## Project Structure
- app.js: Main application file to set up the server.
- models/: Contains Mongoose models for campgrounds and reviews.
- routes/: Defines routes for campgrounds, reviews, and user authentication.
- controllers/: Handles the logic for different routes.
- views/: EJS templates for rendering pages.
- public/: Static files such as CSS and client-side JavaScript.
- middleware.js: Custom middleware for error handling and validation.
- cloudinary/: Configuration for image storage with Cloudinary.
- utils/: Utility functions used throughout the project.

## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## Acknowledgments
- The Web Developer Bootcamp by Colt Steele for initial inspiration.
- Express.js
- MongoDB
- Cloudinary

## Contact
For any questions or feedback, feel free to reach out to me at Bhagathardik1000@gmail.com.
