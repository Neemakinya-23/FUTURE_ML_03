# FUTURE_ML_03
Tesco's online grocery chatbot

## Overview
This chatbot is designed to answer frequently asked questions (FAQs) related to Tesco's grocery services. It utilizes a dataset containing Tesco FAQs and employs NLP techniques for improved response accuracy.

## Features
- **Predefined FAQ Dataset**: Uses a structured dataset with common questions and answers.
- **Fuzzy Matching**: Enhances response selection based on user queries.
- **Interactive Chat**: Provides real-time chatbot interaction.
- **Web Scraping (Optional)**: Can be expanded to fetch live Tesco FAQs.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas**
- **RapidFuzz** (for fuzzy string matching)
- **ChatterBot** (for chatbot implementation)

## Installation
### Prerequisites
Ensure you have the following installed on your system:
- Python 3.7+ recommended
- Flask
 Installation and Setup

1. Clone the repository
```
   sh
   git clone https://github.com/Neemakinya-23/FUTURE_ML_03
   cd chatbot
```
```

3. Create a virtual environment (optional but recommended)
   sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
```
```   

4. Install dependencies
   sh
   pip install flask
 ```
```  
5. Run the Flask server
   sh
   python app.py  
```
```
6. Open the chatbot in a browser
   - Visit http://127.0.0.1:5000/ in your web browser.
```

# Project Structure
```
chatbot/
    static/
        styles.css  # CSS for styling the chatbot UI
    templates/ index.html # Main HTML file
 app.py  # Flask backend
 Tesco_ grocery_FAQ'S.csv  # Dataset
`chatbot.py# model 

 API Endpoint
- The chatbot communicates with the Flask backend via the /predict endpoint.
- The frontend sends a message, and the server processes it and returns a response.
```

## Usage
1. **Load the Dataset**
   - The chatbot uses a dataset of Tesco FAQs stored in a CSV file.
   
2. **Run the Chatbot**
   - Open and execute the Jupyter Notebook or run the script.

```bash
jupyter notebook My_chatbot.ipynb
```

3. **Chat with the Bot**
   - Ask questions related to Tesco services.

```
You: Where do you deliver?
Bot: We deliver to most UK residential addresses.
```

![Tesco Preview](Tesco_%20grocery_chatbot.png)



## Customization
- Add more FAQs to improve chatbot knowledge.
- Modify NLP logic for better response accuracy.
- Integrate web scraping for live FAQ updates.

## License
This project is open-source under the **MIT License**.

## Contribution
Feel free to fork this repository and contribute improvements!



