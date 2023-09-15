# DALL-E CLONE

## Description
This is a full-stack MERN AI image generation app that allows users to use AI to generate an image and share it to the community. Users can either enter a prompt or use a randomized prompt to generate an image leveraging the power of OpenAI. Additionally, the application allows users to share the image generated to a shared database and search for images based on the prompts.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)

## Technologies Used
* HTML, CSS, JavaScript
* React
* MongoDB
* Node.js
* Express.js
* Tailwind CSS
* Vite
* OpenAI's DALL-E Model
* Cloudinary

## Installation
To run DALL-E Clone App locally, follow these steps:

1. Clone the repository: `git clone https://github.com/jojaaku/dall-e.git`
2. Navigate to the client directory: `cd client`
3. Install dependencies: `npm install`
4. Start the development server: `npm run dev`
5. Create a new terminal and navigate to the server directory: `cd ../server`
6. Install dependencies: `npm install`
7. Configure environment variables by creating a `.env` file (see [Configuration](#configuration) for details).
8. Start the development server: `npm start`

## Usage
Once the app is running, open your web browser and navigate to `http://localhost:5173` to access DALL-E Clone App. You can enter prompts, generate images, share it to the community, and even search and download images.

## Features
- Generate images through prompts.
- Randomize prompts.
- Upload generated images.
- Search for images generated by anyone.
- Download uploaded images.
- Responsive design.

## Configuration
To configure Awesome Web App, create a `.env` file in the project root directory and add the following variables:

OPENAI_API_KEY=your_openai_api_key  
MONGODB_URL="your_mongodb_url"  
CLOUDINARY_CLOUD_NAME="your_cloudinary_cloud_name"  
CLOUDINARY_API_KEY="your_cloudinary_api_key"  
CLOUDINARY_API_SECRET="your_cloudinary_api_secret"  
