# AIPix-MERN

![AIPix-MERN Logo](./assets/bestLogo.png)

AIPix-MERN is a web application that allows users to generate AI images using text prompts. The application leverages the MERN stack (MongoDB, Express.js, React.js, Node.js) to provide a seamless and interactive user experience.

## Features

- **AI Image Generation**: Generate stunning images using AI models based on user-provided text prompts.
- **Real-time Image Preview**: View generated images instantly in the browser.
- **Community Sharing**: Share your generated images with the community and explore creations by other users.
- **Responsive Design**: Enjoy a smooth experience on both desktop and mobile devices.


## Live Demo

Check out the live demo of the project [here](https://zingy-dasik-1cca41.netlify.app/).

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Model**: Integrated with Stability AI API for image generation

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/AIPix-MERN.git
    cd AIPix-MERN
    ```

2. Install dependencies for the server:
    ```bash
    cd server
    npm install
    ```

3. Install dependencies for the client:
    ```bash
    cd ../client
    npm install
    ```

4. Create a `.env` file in the `server` directory and add your MongoDB URI and API keys:
    ```env
    MONGODB_URI=your_mongodb_uri
    AI_API_KEY=your_ai_api_key
    ```

### Running the Application

1. Start the server:
    ```bash
    cd server
    npm start
    ```

2. Start the client:
    ```bash
    cd ../client
    npm start
    ```

3. Open your browser and navigate to `http://localhost:5173` to see the application in action.

## Contributing

We welcome contributions to improve the project. To contribute, please fork the repository, create a new branch, and submit a pull request.

## Acknowledgements

- Thanks to Stability AI for providing the AI model for effective image generation.
- Special thanks to the open-source community for their invaluable contributions.

