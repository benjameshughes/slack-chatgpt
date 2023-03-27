# 🤖 Slack Chatbot

This is a simple chatbot app for Slack that allows users to interact with a ChatGPT API.

## 🚀 Getting Started

To get started, follow these steps:

1. Clone the repository to your local machine.
2. Install the dependencies using `npm install`.
3. Create a new Slack App and obtain the necessary credentials, such as the app token and the bot token.
4. Create a ChatGPT API account and obtain the API key.
5. Set up the environment variables in the `.env` file using the following format:
```
SLACK_APP_TOKEN=YOUR_APP_TOKEN_HERE
SLACK_BOT_TOKEN=YOUR_BOT_TOKEN_HERE
CHATGPT_API_KEY=YOUR_API_KEY_HERE
```
6. Start the app using `npm start`.

## 💬 Usage

Once the app is running, you can interact with it in Slack using slash commands. Use the `/chatgpt` command followed by your question to get a response from ChatGPT. For example:
```
/chatgpt What is the meaning of life?
```

The bot will then send a response with the answer to your question.

## 📝 Notes

This app is just a simple example and may not be suitable for production use. It is intended as a starting point for building your own chatbot apps with Slack and ChatGPT.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.


