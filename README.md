<div align="center">
<pre>
<img src="/public/banner.png">
</pre>
</div>

<div align="center" style="line-height: 1;">
  <a href="https://www.deepseek.com/"><img alt="Homepage"
    src="https://github.com/deepseek-ai/DeepSeek-V2/blob/main/figures/badge.svg?raw=true"/></a>
  <a href="https://api-docs.deepseek.com/"><img alt="Chat"
    src="https://img.shields.io/badge/%20DeepSeek-API%20-536af5?color=536af5&logoColor=white"/></a>
  <a href="https://mongodb.com"><img alt="MongoDB"
    src="https://img.shields.io/badge/-MongoDB-4DB33D?style=flat&logo=mongodb&logoColor=FFFFFF"/></a>
  <a href="https://github.com/deepseek-ai/DeepSeek-V3/blob/main/LICENSE-CODE"><img alt="Code License"
    src="https://img.shields.io/badge/Code_License-MIT-f5de53?&color=f5de53"/></a>
  <a href="https://nextjs.org/"><img alt="NEXT.JS"
    src="https://img.shields.io/badge/%20NextJS-Vercel%20-536af5?color=536af5&logoColor=white"/></a>
</div>




# Overview
### This is a language model based on OpenAI. It uses DeepSeek API to generate a response to user's prompt. It uses clerk to authenticate user's email accounts and MongoDB to store user's information and the QawinAI responses. Secure to use. No information is gained. Beta version. Currently, still under development.
> [!Important]
> - Make sure to sign-up before using, otherwise, you can't send a prompt!
> - It works slowly since It's not directly connected to DeepSeek DB.
> - If it doesn't respond. API run out of tokens.

## How it works & Features:
- **Sign-up** with your email
- Type your prompt to in the **PromptBox**
- **Make sure to signup** to be able to send prompts
- QawinAI takes the prompt and analyze it
- It generates a **response** with the help of **API**
- It sends back the **response** to the user
- You can **copy** the response
- Chat is **created** when user prompts
- Chat can be **deleted** or its name can be **renamed**
- ***Other features are currently under development***

## Prerequisites
- NodeJS
- NextJS
- ReactJS
- MongoDB
- tailwindCSS
- npm package
- assets
## requirements.txt
```json
"@clerk/nextjs": "^6.12.9",
"axios": "^1.8.4",
"mongoose": "^8.13.0",
"next": "15.2.3",
"openai": "^4.89.0",
"prismjs": "^1.30.0",
"react": "^19.0.0",
"react-dom": "^19.0.0",
"react-hot-toast": "^2.5.2",
"react-markdown": "^10.1.0",
"svix": "^1.62.0"
```

## Installation

1. To create the application, run the following command:

```bash
npx create-next-app@latest
```

To install the project and necessary dependencies, follow these steps:

1. Clone this repository in the same directory as your application:

   ```bash
   git clone https://github.com/mrbekacs/QawinAI-with-DeepSeek-API.git
   ```

2. Install the required libraries:

   ```bash
    nmp install -r requirements.txt
   ```
3. In the directory, create .env file to store following keys:

   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
   CLERK_SECRET_KEY=your_secret_key
   MONGODB_URI=your_MongoDB_URI
   SIGNING_SECRET=your_secret_key
   DEEPSEEK_API_KEY=your_API_key
   ```
4. To run your application locally, run the following command:
 ```bash
   npm run dev
 ```
5. Visit: ***http://localhost:3000***


