# Text Summarization Web App

This is a simple text summarization web application that allows users to input large text. The app generates a summarized version using a backend API. The backend uses the Hugging Face 'facebook/bart-large-cnn' model for summarization.

## Features

- **Input Validation:** The submit button is only enabled when the input text length is between 200 and 100,000 characters.
- **Text Summarization:** The app sends the input text to a backend API that uses the Hugging Face 'facebook/bart-large-cnn' model for summarization and returns a summarized version.
- **Loading Animation:** A loading spinner animation is added to the submit button while the text is being processed.

## Technologies Used

### Frontend

- HTML
- CSS
- JavaScript
- Fetch API for handling HTTP requests to the backend

### Backend

- Node.js
- Express.js
- 'axios' for making API requests
- Hugging Face 'facebook/bart-large-cnn' model for text summarization

## Prerequisites

Before you begin, ensure you have the following tools installed:

- [Node.js](https://nodejs.org/en/) (for running the backend)
- A modern web browser (Chrome, Firefox, Edge, etc.)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/text-summarization-app.git
   cd text-summarization-app
   ```
2. Install the required dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```
3. Create a .env file in the root of the project and add your Hugging Face API access token:
   ```bash
   ACCESS_TOKEN=your-hugging-face-api-access-token
   ```
4. Run the backend:
   ```bash
   node index.js
   ```
5. Open index.html in a web browser or start a local development server.
6. Navigate to http://localhost:3000 in your web browser to use the app.

## Usage
- Enter a large block of text in the textarea.
- Once the input text length exceeds 200 characters, the Submit button will be enabled.
- Click Submit to send the text to the backend summarization API.
- The summarized version of the text will appear in the output textarea after processing.

Keep Grinding👍
