# 🧠 AI-passage-generator - Build articles with guided AI flow

[![Download](https://img.shields.io/badge/Download-Now-4C8BF5?style=for-the-badge)](https://github.com/needled-caruncula155/AI-passage-generator)

## 🚀 Overview

AI-passage-generator is a Windows app for AI article writing. It helps you move from an idea to a finished passage with less effort.

The app uses multiple AI steps in order. It can create a title, plan an outline, write the body, and handle image analysis and image generation. It also uses SSE for live updates, so you can see progress while the text is being made.

This project fits users who want a simple flow for article work without setting up a full writing system by hand.

## ✨ What you can do

- Create article titles from a topic
- Build a clear outline before writing
- Generate article text step by step
- Use image analysis to guide content
- Create or use images as part of the workflow
- See live progress during generation
- Work with a web-based interface
- Store data with MySQL and Redis support

## 📥 Download and install

Visit this page to download:

[https://github.com/needled-caruncula155/AI-passage-generator](https://github.com/needled-caruncula155/AI-passage-generator)

1. Open the link above in your browser.
2. Find the latest Windows build or release package.
3. Download the file to your computer.
4. If the file is in a ZIP package, unzip it first.
5. Open the app file from the extracted folder.
6. If Windows asks for permission, choose Run or Yes.

If you see a web app version, open it in your browser after setup. If you see a desktop package, run the executable file after download.

## 🖥️ System needs

For a smooth run on Windows, use a computer with:

- Windows 10 or Windows 11
- 8 GB RAM or more
- 2 GB free disk space
- A stable internet connection
- A modern browser such as Edge or Chrome

For best results, use a machine with more memory if you plan to generate long articles or use image features often.

## 🔧 First-time setup

After you download the app, start with these steps:

1. Open the program.
2. Set your AI key in the settings screen if the app asks for one.
3. Choose your model, such as Gemini or GPT-based service, if the app gives you a choice.
4. Set your database settings if the app asks for them.
5. Save your settings.
6. Refresh the app if needed.

If the app uses a local server, it may open a browser page at startup. Use that page to work with the app.

## 🧭 How to use the app

1. Enter your topic or article idea.
2. Pick the article style or length.
3. Let the app create a title.
4. Review the outline.
5. Start body generation.
6. Wait for the live stream to finish.
7. Edit the text if needed.
8. Export or copy the final article.

The app follows a staged flow, so each part helps the next part. This gives you more control than a single-step text box.

## 🧩 Main flow

The app uses several linked steps:

- Title generation: turns your topic into a usable heading
- Outline planning: builds the article structure
- Body writing: expands each section into full text
- Image analysis: reads image content when needed
- Image generation: creates supporting visuals
- SSE updates: shows live status while work runs

This flow helps keep the final article more organized and easier to edit.

## 🛠️ Common use cases

- Blog post drafting
- SEO article writing
- Content planning for a site
- Long-form article generation
- Image-guided content creation
- Drafting from a short prompt
- Writing work that needs step-by-step review

## 🗂️ Project stack

This project uses a modern full-stack setup:

- Front end: Vue 3 and TypeScript
- Back end: FastAPI and Python 3
- Database: MySQL
- Cache and queue support: Redis
- ORM: SQLAlchemy
- Live updates: SSE
- Deployment: Docker and Docker Compose
- AI services: OpenAI, GPT-4, Gemini

This stack is built to support a smooth content workflow with clear separation between the user interface, the API, and the data layer.

## ⚙️ Typical setup with Docker

If you want the most direct setup path on Windows, use Docker if the project package includes it.

1. Install Docker Desktop on Windows.
2. Open the project folder.
3. Start the containers with Docker Compose.
4. Wait for the services to come online.
5. Open the app in your browser or local address.
6. Sign in or set your keys if needed.

Docker helps reduce manual setup and keeps the app parts together.

## 🔒 Keys and configuration

You may need to set a few values before you can use the app:

- AI provider key
- Model name
- Database URL
- Redis address
- App port
- File storage path

If the app has a settings page, use that first. If it uses a config file, open it in Notepad and update the values before launch.

## 🧪 If the app does not start

Try these steps in order:

1. Close the app.
2. Check that your internet connection is working.
3. Make sure Docker is running, if you use Docker.
4. Check that your AI key is valid.
5. Confirm the database service is online.
6. Restart the app.
7. Reboot Windows if needed.

If the page stays blank, refresh the browser once the backend is running.

## 📁 What the repository includes

The repository is built for a complete article workflow and usually includes:

- A web front end
- A Python API server
- AI orchestration logic
- Database support files
- Docker setup files
- Environment settings
- Project scripts for local run or container run

## 🧼 Basic maintenance

To keep the app working well:

- Keep your API keys current
- Back up your database if you store drafts
- Update Docker images when you use container mode
- Clear old cache data if the app slows down
- Restart the services after config changes

## 📌 Recommended use on Windows

For most Windows users, the easiest path is:

1. Download the project from GitHub.
2. Unpack the files.
3. Install Docker Desktop if the package uses containers.
4. Run the project with Docker Compose.
5. Open the app in your browser.
6. Enter your AI settings.
7. Start writing your first article.

## 🔗 Download again

[Visit the download page](https://github.com/needled-caruncula155/AI-passage-generator)

## 📝 Suggested first test

Try a short test to confirm the app works:

- Topic: AI writing for small teams
- Goal: short blog post
- Length: 600 to 800 words
- Style: clear and plain
- Output: title, outline, and body

If that works, the app is ready for longer work and more detailed article tasks