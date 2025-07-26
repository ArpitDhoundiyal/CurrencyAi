💱 AI-Powered Currency Converter App (Using Gemini)

A sleek and intelligent currency converter Android app powered by Google's Gemini AI. This app goes beyond traditional dropdowns and fields — just ask in natural language, and the AI will handle the rest!

🚀 Features

🌍 Convert currencies using real-time exchange rates

🧠 AI Agent (Gemini) for natural language understandinge.g., "Convert 50 USD to INR", "How much is €100 in Yen?"

📱 Beautiful Jetpack Compose UI

⚡ Fast, responsive, and beginner-friendly architecture

☁️ Integrated with REST API for live exchange rates

🛠️ Tech Stack

Android – Kotlin, Jetpack Compose

Gemini AI Agent – Natural language query understanding

MVVM Architecture

Retrofit – For fetching real-time exchange rates

Hilt – Dependency Injection

Coroutines & Flow – Asynchronous data handling

🤖 How the AI Agent Works

User types or speaks a natural language querye.g., "What's 75 CAD in INR?"

Gemini AI parses the request to extract:

Source Currency (CAD)

Target Currency (INR)

Amount (75)

Exchange rate API fetches current conversion rate

App displays the final converted amount


📦 Installation

Clone this repo:

git clone https://github.com/your-username/ai-currency-converter.git
cd ai-currency-converter

Open in Android Studio

Add your API keys:

Exchange Rate API Key

Gemini API Key (if using secured setup)

Run on emulator or device

🔑 API Keys Setup

Create a local.properties file (or use environment variables):

EXCHANGE_API_KEY=your_api_key
GEMINI_API_KEY=your_gemini_api_key

🧠 Example Prompts to Try

"Convert 100 USD to INR"

"How much is 50 Euros in Pounds?"

"I have 10,000 Yen, what is it in Canadian Dollars?"

🧪 Future Enhancements

🌐 Multi-language support

🎧 Voice command integration

📈 Historical currency data

📉 Currency trends & graphs

🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you'd like to change.

📄 License

MIT License - See LICENSE for details.

👨‍💻 Author

Made with 💙 by Your Arpit

