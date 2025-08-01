# Wanderlust - Travel Destination Platform

A full-stack web application for discovering and sharing travel destinations. Built with Node.js, Express, MongoDB, and EJS templating.

## Features

- User Authentication (Signup, Login, Logout)
- Browse travel destinations
- Create, view, update, and delete listings
- Add and manage reviews for destinations
- Image uploads using Cloudinary
- Interactive maps with Mapbox
- Responsive design

## Tech Stack

- **Backend**: Node.js, Express
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: Passport.js
- **Frontend**: EJS templating with EJS-Mate
- **Styling**: Custom CSS
- **Cloud Storage**: Cloudinary for image hosting
- **Maps**: Mapbox integration

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB Atlas account (or local MongoDB instance)
- Cloudinary account
- Mapbox access token

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd majorproject
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add the following environment variables:
   ```
   ATLASDB_URL=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_KEY=your_cloudinary_key
   CLOUDINARY_SECRET=your_cloudinary_secret
   MAPBOX_TOKEN=your_mapbox_access_token
   SECRET=your_session_secret
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
majorproject/
├── controllers/     # Route controllers
├── init/           # Database initialization scripts
├── models/         # Mongoose models
├── public/         # Static files (CSS, JS, images)
├── routes/         # Route definitions
├── utils/          # Utility functions
├── views/          # EJS templates
├── .env            # Environment variables
├── .gitignore      # Git ignore file
├── app.js          # Main application file
├── cloudConfig.js  # Cloudinary configuration
├── middleware.js   # Custom middleware
├── package.json    # Project dependencies
└── schema.js       # Joi validation schemas
```

## Available Scripts

- `npm start` - Start the development server
- `npm test` - Run tests (currently not configured)

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Built with ❤️ using Node.js and Express
- Icons from [Font Awesome](https://fontawesome.com/)
- Maps by [Mapbox](https://www.mapbox.com/)
- Image hosting by [Cloudinary](https://cloudinary.com/)
