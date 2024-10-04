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
    ```bash
    cd url-shortener

4. Install the dependencies:
   ```bash
   npm install

6. Create a .env file in the root directory and add your MongoDB URI:
    ```bash
    MONGODB_URI=mongodb://localhost:27017/urlshortener

8. Start the server:
   ```bash
    npm start
