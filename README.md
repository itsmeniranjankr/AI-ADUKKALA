# 🍳 AI Adukkala - Kerala Recipe Generator

**AI Adukkala** (AI Kitchen) is a smart, single-page web application that acts as your personal Kerala Master Chef. Simply enter the ingredients you have on hand, and the app will leverage the power of the Google Gemini API to generate a unique, authentic Kerala-style recipe for you in seconds.

This project was built to solve the common kitchen dilemma: "What can I cook with the ingredients I already have?"

![AI Adukkala Screenshot](https://placehold.co/800x400/fefce8/111827?text=AI+Adukkala+App)

---

## ✨ Features

* **AI-Powered Recipe Generation:** Get creative and authentic Kerala recipes based on your available ingredients.
* **Simple & Intuitive UI:** A clean, mobile-friendly interface that's easy for anyone to use.
* **Dynamic Content:** Every recipe is generated on the fly, providing a unique experience every time.
* **Structured Output:** Recipes are neatly formatted with a name, a clear ingredient list, and step-by-step instructions.
* **Compact & Portable:** The entire application is contained within a single HTML file, making it easy to host or use offline.

---

## 🚀 How to Set Up and Run

This project is self-contained in a single `index.html` file but requires a Google Gemini API key to function.

### Prerequisites

* A modern web browser (like Chrome, Firefox, or Edge).
* A Google Gemini API Key.

### Getting Your API Key

1.  **Visit Google AI Studio**: Go to [https://aistudio.google.com/](https://aistudio.google.com/) and sign in with your Google account.
2.  **Get API Key**: Click the **`< > Get API key`** button.
3.  **Create API Key**: In the new window, click **"Create API key in new project"**.
4.  **Copy Your Key**: Copy the generated API key to your clipboard.

### Configuration

1.  Open the `index.html` file (the code for the app).
2.  Navigate to the `<script>` section at the bottom of the file.
3.  Find the following line:
    ```javascript
    const GEMINI_API_KEY = "YOUR_API_KEY_HERE"; 
    ```
4.  **Replace** `"YOUR_API_KEY_HERE"` with the actual Gemini API key you copied. Make sure to keep the key inside the double quotes.
5.  Save the file. You can now open `index.html` in your browser to run the application locally.

---

## 📋 How to Use

1.  **Enter Ingredients:** In the text box, type the ingredients you have available. Be as specific as you like (e.g., "chicken, coconut milk, onions, ginger, green chilies").
2.  **Generate:** Click the **"Generate Recipe"** button.
3.  **Enjoy:** The AI will take a moment to think and then display a complete recipe for you to follow!

---

## 🛠️ Technologies Used

* **HTML5**
* **Tailwind CSS** for styling.
* **JavaScript** for application logic.
* **Google Gemini API** for the core AI and recipe generation.
* **Font Awesome** for icons.
* **Google Fonts** for typography.
