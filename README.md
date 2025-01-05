
# GEMINI-SERVER

GEMINI-SERVER is a simple tool that allows you to interact with **Gemini AI** locally via a chatbot interface hosted on your machine. The tool provides a web-based interface to communicate with Gemini AI, enabling you to generate text content in real time. It is designed to run on a local server and can be accessed through your browser.

### Features

- **Gemini AI Access**: Interact with Gemini AI and generate content directly from your browser.
- **Simple Setup**: Install and run the server locally with minimal configuration.
- **Chatbot Interface**: A simple and intuitive user interface to interact with the AI.
- **Responsive**: Works seamlessly on both desktop and mobile devices.

---

## How to Install and Use GEMINI-SERVER

### Prerequisites

Make sure you have **Node.js** and **npm** installed on your system. You can check if you have them installed by running the following commands:

```bash
node -v
npm -v
```

If you don’t have Node.js installed, you can download it from [here](https://nodejs.org/).

or you can download it directly in the terminal with the following command:

With Termux:

```bash
pkg install nodejs
```
With Linux:

```bash
sudo apt install nodejs npm
```

### Installation

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/yourusername/gemini-server.git
    cd gemini-server
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Start the server**:

    ```bash
    node server.js
    ```

4. **Access the chatbot** by navigating to `http://localhost:3000` in your browser.

### API Key Configuration

The first time you run the server, it will prompt you to enter your Gemini API Key. You can obtain the API key from [Google AI Studio](https://aistudio.google.com/app/apikey). Follow the instructions to generate a new API key and enter it in the terminal when prompted.

The key will be saved locally, so you won’t need to re-enter it the next time you run the server.

### Usage

Once the server is running, you can interact with Gemini AI via the **chatbot** interface on your browser. Type your prompt in the input box, and the AI will generate content in response.

### Troubleshooting

- If you encounter issues with API Key configuration, ensure that you have entered a valid key. If the key is missing or invalid, the tool will prompt you to enter a new one.
- Ensure that your local server is running on `http://localhost:3000`. If it is not, check for errors in the terminal and ensure all dependencies are installed correctly.

---

## License

This project is open source and available under the [MIT License](LICENSE).
