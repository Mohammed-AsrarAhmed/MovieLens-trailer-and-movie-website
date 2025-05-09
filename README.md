# MovieLens-trailer and movie website
The project provides features like movie browsing, detailed movie information, user ratings, and YouTube trailer integration.

1. **Clone the repository:**
git clone https://github.com/your-username/ MovieLens-trailer-and-movie-website
cd MovieLens-trailer-and-movie-website

Install server dependencies:
npm install

> ⚠️ **Important:**  
> Replace `your_mongodb_connection_string_here` with your actual MongoDB connection string.  
> You can get this from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) if you're using a cloud database, or use your local MongoDB URI like:  
> `mongodb://localhost:27017/movielens`

# From app
npm start
This uses concurrently to run both React and Node.js servers together.
 
