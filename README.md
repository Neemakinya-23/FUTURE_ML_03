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
Ensure Python is installed (Python 3.7+ recommended). Install required dependencies:

```bash
pip install pandas rapidfuzz chatterbot chatterbot_corpus
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

