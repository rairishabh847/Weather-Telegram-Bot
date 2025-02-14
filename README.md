
# Weather Bot Telegram - Nest.js

Weather Bot Telegram is a Telegram bot built using Nest.js that provides weather updates.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)

## Prerequisites

Before running the project, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [npm](https://www.npmjs.com/)

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/weather-bot-telegram.git
   ```

2. Navigate to the project directory and install dependencies:

   ```bash
   cd weather-bot-telegram
   npm install
   ```

3. Create a `.env` file in the project root and configure your environment variables:

   ```bash
   TELEGRAM_BOT_TOKEN=YOUR_TELEGRAM_BOT_TOKEN
   CITY=YOUR_DEFAULT_CITY
   MONGODB_URI=YOUR_MONGODB_CONNECTION_URI
   OPENWEATHERMAP_API_KEY=YOUR_OPENWEATHERMAP_API_KEY
   ```

4. Start the application:

   ```bash
   npm start
   ```

5. The Telegram bot is now running and ready to receive commands. 

