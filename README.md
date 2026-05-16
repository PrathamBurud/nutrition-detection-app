# 🥗 AI Nutrition Detection App

A smart, AI-powered web application that analyzes images of food and accurately estimates portion sizes, calories, and macronutrients (Protein, Fat, Carbs) using **Groq** and the **Llama Vision Model**.

## ✨ Features

- **📸 Image Analysis**: Simply upload a photo of your meal (JPG, PNG, WEBP).
- **🧠 Chain-of-Thought Reasoning**: The AI is programmed to "think" before it estimates, identifying exact items and portion sizes to provide highly accurate nutritional data rather than guessing.
- **⚡ Blazing Fast**: Powered by Groq's insanely fast inference engine.
- **📊 Detailed Macros**: Get a complete breakdown of Calories, Protein, Fat, and Carbs for every individual item detected on the plate.
- **🎨 Beautiful UI**: A clean, modern interface designed for ease of use.

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI Integration**: Groq API (Llama 4 Vision)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- A [Groq API Key](https://console.groq.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/prathamburud09-design/nutrition-detection-app.git
   cd nutrition-detection-app
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   Create a `.env` file in the root directory and add your Groq API key:
   ```env
   GROQ_API_KEY=your_api_key_here
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

6. **Open your browser**
   Navigate to `http://127.0.0.1:5000` to start analyzing your meals!

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
