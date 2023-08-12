# AI Image Generation with MERN Stack and Tailwind CSS

![Project Banner](/client/src/assets/Screenshot%202023-08-12%20at%203.25.40%20PM.png)

Welcome to the AI Image Generation project repository! This repository houses a MERN (MongoDB, Express.js, React, Node.js) stack application that leverages the power of the OpenAI API to generate AI images. The project also utilizes Tailwind CSS for streamlined and responsive user interface design. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to showcase the seamless integration of the MERN stack with the OpenAI API to generate stunning AI images. The project's user interface is designed using Tailwind CSS, providing an efficient and visually appealing experience.
## Features

- AI image generation using OpenAI API.
- User-friendly web interface built with React and Tailwind CSS.

## Technologies

- **MongoDB**: A popular NoSQL database used for storing application data.
- **Express.js**: A web application framework for building robust APIs with Node.js.
- **React**: A JavaScript library for building user interfaces.
- **Node.js**: A JavaScript runtime environment for server-side programming.
- **OpenAI API**: Harness the capabilities of the OpenAI API to generate AI images.
- **Tailwind CSS**: A utility-first CSS framework for creating responsive designs with minimal effort.

...

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- Node.js and npm: Make sure you have Node.js and npm (Node Package Manager) installed.
- MongoDB: Set up a MongoDB database to store application data.

### Installation

```bash
git clone https://github.com/your-username/ai-image-generation.git
cd ai-image-generation

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Create a .env file in the server directory and add your OpenAI API key
echo "OPENAI_API_KEY=your_openai_api_key_here" > server/.env

# Start the development server for the server
cd ../server
npm start

# In a separate terminal window, start the React development server for the client
cd ../client
npm start


