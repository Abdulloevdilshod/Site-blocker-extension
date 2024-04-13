<h1 align="center">A Site Blocker Extension</h1>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

## <a name="introduction">🤖 Introduction</a>

Easy Block is a simple and effective Chrome browser extension that allows users to effortlessly manage access to web pages. 
With this extension, you can block websites by adding URLs to a blacklist, preventing these pages from opening in your browser, ensuring a controlled and safe browsing experience.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Vite
- Tailwind CSS
- NestJS

## <a name="features">🔋 Features</a>

👉 **Block web pages via URL**

👉 **Easy addition and removal of sites from the list**

👉 **Customize the list of blocked sites directly through the extension's web-site interface**

👉 **Safe browsing experience free from unwanted and distracting websites**

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en) >= 18.17.0
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone git@github.com:AbdulloevDilshod/Site-blocker-extension.git
cd Site-blocker-extension
```

**Installation**

Install the project dependencies using npm:

```bash
cd client, server, extension
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
DATABASE_URL=your_db_url
JWT_SECRET=your_jwt_secret
```

Replace the placeholder values with your actual credentials

**Running the Project**

```bash
cd ./client npm run dev
cd ./extension npm run dev
cd ./server npm run start:dev
```
**Add extension to the Chrome**

- Open [chrome://extensions/](chrome://extensions/) in your Chrome browser
- Turn on dev mode on right side
- And click on Load Unpacked and find ./extensions/dist file and open it
- Finally you can panage the extension from extension bar in browser

Open [http://localhost:3000/](http://localhost:3000/) in your browser to view the project.
