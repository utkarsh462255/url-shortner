# URL Shortener

A simple URL shortening service built using Node.js, Express, and MongoDB (Mongoose). It allows users to shorten long URLs and redirect to the original URL using a short identifier.

## Features

- Generate short URLs from long URLs.
- Store the URLs in a MongoDB database.
- Redirect to the original URL when accessing the short URL.
- Simple REST API to create and retrieve shortened URLs.
  
## Installation

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/) (v14+)
- [MongoDB](https://www.mongodb.com/)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/url-shortener.git

2. Navigate to the project directory:
    cd url-shortener

3. Install the dependencies:
    npm install

4. Create a .env file in the root directory and add your MongoDB URI:
    MONGODB_URI=mongodb://localhost:27017/urlshortener

5. Start the server:
    npm start
