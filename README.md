# WhatsApp-Bot (By SimplyLife)
> **Official Guide:** [https://www.youtube.com/@SimplyLife-vps](https://www.youtube.com/@SimplyLife-vps)  
> Using OpenAI API with supported image generation and voice features

## 1. Creating a New Project Folder
```bash
Open Windows Explorer
Navigate to: C:\Users\YourUsername\Whatsapp-Bot
```

## 2. Download Node.js and FFmpeg

Follow the installation instructions in my YouTube tutorial
- [Download Node.js here](https://nodejs.org/en/download)
- [Download FFmpeg here](https://www.gyan.dev/ffmpeg/builds/)
- After installation, restart all and reopen terminal windows to apply changes correctly
```bash
node -v
```
```bash
npm -v
```
```bash
ffmpeg -version
```
## 3. Top up your OpenAI Credit

- [Sign Up OpenAi here](https://auth.openai.com/create-account)
- [Go To Billing Page here](https://platform.openai.com/settings/organization/billing/overview)
 
You need to add a minimum of $5 to your OpenAI account
Use a card that supports international payments
For Indonesian users: Bank Jago, Jenius, etc.

## 4. Make .env file
```bash
OPENAI_API_KEY=YourOpenAiAPIhere
```
Make sure to save the .env file in the same directory as your project

## 5. Download System.js
- [Download System.js here](https://drive.google.com/file/d/17cZyMIW5qHLF99CzK__vUBK9AU7UOPeG/view?usp=sharing)
- Save the system.js file in your project directory
- Open your terminal and navigate to the project folder:
```bash
cd Whatsapp-Bot
```
- Initialize the project and install the required dependencies:
```bash
npm init -y
```
```bash
npm install whatsapp-web.js qrcode-terminal axios sharp form-data fluent-ffmpeg dotenv
```

## 6. Lauch your Ai Assistant
```bash
node system.js
```

## 7. To stop just close your terminal / Ctrl + C
## 8. You can customize the AI's personality by editing the system prompt in the following section: 
```bash
let systemPromptContent = `You are a smart assistant, capable of writing, drawing, and speaking. You communicate in both Indonesian and Javanese languages.`;
```
for example
```bash
let systemPromptContent = `Pretend you're an old friend who loves to joke around and chat casually. You are a smart assistant who can write, draw, speak in spanish and frace. Be fun, relaxed, and friendly in your responses.`;
```
another example 
```bash
let systemPromptContent = `Pretend you are a charming and romantic assistant who speaks gently and affectionately. You often use poetic expressions and compliments. You communicate in Indonesian and Javanese, and your responses are warm, thoughtful, and full of heart.`;
```
or You can customize it however you like, depending on your preferences.
