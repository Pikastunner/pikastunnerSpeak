# PikastunnerSpeak Chatbot

PikastunnerSpeak is an interactive AI chatbot that can respond to user prompts through text and speech. It features a retro Windows XP-like interface and a video of Pikastunner that synchronizes mouth movements with the generated speech.

## Features

- **Text Commands**: Communicate with Pikastunner through various text commands.
- **Speech Synchronization**: Pikastunner's mouth movements are synchronized with the generated speech.
- **Interactive Interface**: A terminal-like interface mimics the classic command prompt experience.

## Commands

- `echo <message>`: Displays the message in the terminal.
- `help`: Provides information about available commands.
- `clear`: Clears the command history in the terminal.
- `awake`: Wakes up Pikastunner, enabling interactions.
- `sleep`: Puts Pikastunner to sleep, disabling interactions.
- `text <message>`: Sends a text message to Pikastunner and gets a text response.
- `speak <message>`: Sends a text message to Pikastunner and gets a speech and text response.

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/PikastunnerSpeak.git
   cd PikastunnerSpeak

2. Install the dependencies:

    ```bash
    Copy code
    npm install

3. Start the development server:

    ```bash
    Copy code
    npm start

4. Open your browser and navigate to http://localhost:3000.

# Backend Server
Ensure you have the backend server running, which handles the chatbot's responses. The backend server should be set up to listen for POST requests at http://localhost:5000/generate.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgements
Thanks to the creators of the CMU Pronouncing Dictionary for the phoneme data.
Inspired by retro Windows XP interfaces and classic command prompt experiences.
Enjoy interacting with PikastunnerSpeak! If you have any questions or feedback, feel free to reach out.
