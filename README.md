# 290045's - What Beats Rock? 🪨✂️🚀

A serverless, AI-powered clone of the popular game "What Beats Rock?", built entirely with HTML, CSS, and vanilla JavaScript. 

Unlike traditional Rock-Paper-Scissors games that use static rules, this game utilizes a Large Language Model (LLM) to dynamically judge whether any arbitrary user input beats the previous item. 

## 🎮 How to Play
1. Open the live link hosted on GitHub Pages.
2. Enter your personal OpenAI API Key to start the game.
3. The game starts with **Rock**. Type anything you think logically beats rock (e.g., "Paper", "Drill", "Black Hole").
4. If the AI determines your guess wins, your score increases, and the prompt updates to match your new item (e.g., *"What beats Black Hole?"*).
5. If you repeat an item or make a losing guess, it's Game Over!

## 🔒 Security & Privacy (No Backend)
Because this application is **100% serverless**, it does not possess a backend server or a database. 
* Your API key is **never sent to a third-party server** (except directly to OpenAI's official API endpoint).
* Your key is securely saved on your own computer using your browser's local storage (`localStorage`).

## 🛠️ Built With
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **AI Engine:** OpenAI API (`gpt-4o-mini`)
* **Hosting:** GitHub Pages

## 🚀 Setup & Local Deployment
If you want to run this locally on your own computer instead of GitHub Pages:

1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Open the directory:
   ```bash
   cd what-beats-rock
   ```
3. Double-click the `index.html` file to open it directly in any web browser.
