# 🌐 AI-Agent Adviser

<p align="center">
  <a href="https://www.openai.com/" >
      <img alt="OpenAI's GPT-4 (AI-powered features)" src="https://img.shields.io/static/v1.svg?label=OpenAI&message=GPT-4&color=brightgreen" /></a>
  <a href="https://platform.openai.com/docs/assistants/overview" >
      <img alt="OpenAI Assistants API (Conversational AI)" src="https://img.shields.io/static/v1.svg?label=OpenAI&message=Assistants API&color=brightgreen" /></a>
  <a href="https://nodejs.org/" >
      <img alt="Node.js (JavaScript runtime)" src="https://img.shields.io/static/v1.svg?label=Node.js&message=JavaScript runtime&color=lightyellow" /></a>
  <a href="https://opensource.org/license/mit/">
      <img alt="License: MIT" src="https://img.shields.io/static/v1.svg?label=License&message=MIT&color=lightgreen" /></a>
</p>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [How It Works](#-how-it-works)
- [Installation](#-installation)
- [OpenAI API Key Setup](#-openai-api-key-setup)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

**AI-Agent Adviser** is an intelligent tool designed to help developers and project managers choose the best **technology stack** for their software projects. By leveraging **OpenAI's Assistants API**, it analyzes project descriptions and provides tailored recommendations, streamlining the decision-making process.

With **AI-Agent Adviser**, you can:
- Save time by avoiding extensive research.
- Receive expert advice for building scalable and efficient applications.
- Focus on executing your ideas instead of debating over technologies.

---

## 🚀 Features

- **AI-Powered Recommendations**: Generate customized technology stack advice based on project requirements.
- **Interactive Responses**: Conversational AI capabilities for natural interaction.
- **Extensible Design**: Built with a modular architecture using Node.js, Express.js, and OpenAI APIs.

---

## 🔨 How It Works

1. **User Input**: Provide a brief description of your project.
2. **AI Analysis**: The Assistant processes the input using GPT-4 and associated tools.
3. **Technology Recommendations**: Get a curated list of technologies, frameworks, and tools tailored to your project's needs.

#### Example Input:
*"I’m building an e-commerce platform that requires a responsive UI, secure payments, and scalable backend services."*

#### Example Output:
- **Frontend**: React.js, TailwindCSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Other Tools**: Stripe API for payments

---

## 📦 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/solutions-for-realvalue/AI-AgentAdviser.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd AI-AgentAdviser
   ```

3. **Install Dependencies**
   Install the necessary packages for both the frontend and backend:

   ```bash
   cd server && npm install
   cd ../client && npm install
   ```

---

## 🔑 OpenAI API Key Setup

An OpenAI API key is required to access the Assistants API. Sign up at [OpenAI][open-ai], set up billing, and generate an API key. Securely store this key and use it to configure your environment variables.

1. Create an `.env` file in the root of the project and add your OpenAI API key:

   ```bash
   OPENAI_API_KEY=your_api_key_here
   ```

2. Ensure your `.env` file is excluded from version control (.gitignore) for security.

---

## 🎯 Usage

1. **Build the Application**

   From the project directory:

   ```bash
   npm run build
   ```

2. **Start the Backend Server**

   ```bash
   cd server
   npm start
   ```

3. **Launch the Client Application**

   In a new terminal, navigate to the client directory and start the React application:

   ```bash
   cd client
   npm run preview
   ```

4. Navigate to `http://localhost:3000` in your web browser to start the application.

---

## 🤝 Contributing

We welcome contributions! Here’s how you can help:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add feature-name"
   ```

4. Push to your branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

For major changes, please open an issue first to discuss your ideas.

---

## 📜 License

This project is licensed under the [MIT License][mit-license]. See the LICENSE file for details.

[open-ai]: <https://openai.com/>
[mit-license]: <https://github.com/solutions-for-realvalue/AI-AgentAdviser/blob/main/LICENSE>
