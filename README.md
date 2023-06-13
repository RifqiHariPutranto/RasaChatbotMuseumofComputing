# Rasa Chatbot Museum Of Computing
Adding new chatbot feature to Museum of Computing Indonesia
# Rasa Installation
1. Clone or Download this repo to your devices
2. Change directory to Rasa/ and create virtual environment with : 
   `python -m venv venv`
4. Activate virtual environment in Command Prompt Window with : 
   `venv\Scripts\Activate`
5. Install Rasa and Spacy with comman below :\n
   `pip install rasa`
   `pip install spacy==2.3.8`
   `python -m spacy download en_core_web_md`
   `python -m spacy link en_core_web_md en`
6. Run rasa using :
   `rasa run` 
# Running Chatbot in Unity
1. Open unity project in `RasaChatbotMuseumofComputing/Unity/Rasa/` directory.
2. Click cplay and the chatbot will start and we can type to it.
# Reference Code
Checkout retrogeek46 work on rasa integration to unity at https://github.com/retrogeek46/Rasa-Unity
