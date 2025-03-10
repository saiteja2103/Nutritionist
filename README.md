# Nutritionist App

## Overview
The **Nutritionist App** is a web-based tool built using **Streamlit** and **Google Gemini AI** to analyze meals, chat with a nutritionist, track nutrition, and prepare diet plans. It leverages AI-powered image analysis and text processing to provide personalized dietary recommendations.

## Features
1. **Analyze Meal**: Upload a meal image and get a detailed nutritional breakdown, including calories and macro/micronutrients.
2. **Chat with Nutritionist**: Ask nutrition-related questions and get AI-powered responses.
3. **Track Nutrition**: Keep track of your daily nutritional intake.
4. **Prepare Diet Plan**: Generate a personalized diet plan based on user preferences and dietary restrictions.

## Technologies Used
- **Python**
- **Streamlit** (Frontend UI)
- **Google Gemini AI** (Generative AI for meal analysis and chatbot responses)
- **PIL (Pillow)** (For image processing)
- **Matplotlib & NumPy** (For data visualization)
- **Googletrans** (For text translation)
- **SpeechRecognition** (For voice input, optional)
- **MongoDB** (Planned for data storage)

## Installation
### Prerequisites
Ensure you have Python installed (preferably 3.8+). You also need a Google Gemini API key.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/nutritionist-app.git
   cd nutritionist-app
   ```
2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up your `.env` file with the Google Gemini API key:
   ```sh
   echo "API_KEY=your_google_gemini_api_key" > .env
   ```

## Running the App
Start the Streamlit app by running:
```sh
streamlit run main.py
```

## Deployment
To deploy on **Streamlit Cloud**:
1. Push your code to GitHub.
2. Go to [Streamlit Cloud](https://share.streamlit.io/).
3. Deploy your GitHub repo.

## Troubleshooting
- If you encounter errors related to `asyncio.run()`, ensure that `translate_text()` is not an async function.
- Ensure all dependencies are installed (`pip install -r requirements.txt`).
- If the app crashes on Streamlit Cloud, check the logs in the **Manage App** section.

## Future Enhancements
- **MongoDB integration** for user data persistence.
- **Google Fit/Apple Health integration** for tracking nutrition data.
- **Voice input improvements** for better user experience.

## License
MIT License

## Contact
For questions or contributions, reach out to **SAI**.

