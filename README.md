# AutoSage-App-Using-Gemini-Flash
1. Repository "About" Section (Short Description) AutoSage AI – An intelligent vehicle expert powered by Gemini 2.5 Flash and Streamlit. Identifies vehicles from images, provides tech specs, maintenance tips, and professional buyer's advice.
# 🚗 AutoSage AI: Vehicle Expert App

AutoSage is a cutting-edge AI application designed to provide comprehensive insights into two-wheeler and four-wheeler vehicles. Powered by **Google Gemini 2.5 Flash** technology and built with **Streamlit**, it acts as a digital vehicle consultant to help users make informed decisions.

## 🌟 Key Features
* **Instant Identification:** Upload any vehicle image to identify the exact brand, model, and variant.
* **Technical Deep-Dive:** Get detailed engine specs, fuel system types (Carbureted vs. Fuel-Injected), and performance data.
* **Buyer's Perspective:** Receive professional "Pros & Cons" and resale value estimates.
* **Reliability & Speed:** Built-in retry logic to handle API rate limits and high-speed processing.

## 📖 Practical Scenarios
AutoSage is designed to solve real-world problems:
1.  **Buying a New Motorcycle:** Compare specs, features, and pricing of different models instantly to stay within your budget.
2.  **Vehicle Maintenance Tips:** Receive proactive advice on seasonal maintenance (tire pressure, fluids, battery health) to keep your vehicle in top condition.
3.  **Finding Eco-Friendly Vehicles:** Identify electric, hybrid, or fuel-efficient options based on mileage and environmental impact.

## 🛠️ Tech Stack
* **Frontend:** Streamlit (Python-based Web Framework)
* **AI Model:** Google Gemini 2.5 Flash (Multimodal LLM)
* **Image Processing:** Pillow (PIL)
* **Environment Management:** Python-Dotenv

## 🚀 Getting Started

### Prerequisites
* Python 3.9+
* Google Gemini API Key (Get it from [Google AI Studio](https://aistudio.google.com/))

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/autosage-ai.git](https://github.com/your-username/autosage-ai.git)
    cd autosage-ai
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up your environment variables:**
    Create a `.env` file in the root directory and add your API key:
    ```env
    GOOGLE_API_KEY=your_actual_api_key_here
    ```

4.  **Run the application:**
    ```bash
    streamlit run app.py
    ```

## 📋 Project Structure
* `app.py`: Main application logic and Streamlit UI.
* `.env`: Secure storage for API credentials (ignored by git).
* `requirements.txt`: List of required Python libraries.

## 📄 License
This project is shared under the MIT License.
