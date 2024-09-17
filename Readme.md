**Streamlit Q&A Chatbot using GROQ**

**\#How to create a Venv for Conda Environment if present**

**conda create -p venv python -y**

**else**

**\# for creating a virtual environment on macOS**

**python3 -m venv venv**

**\# Windows**

**\# You can also use \`py -3 -m venv venv\` or python3 -m venv venv**

**\#Activate your venv**

**source venv/bin/activate**

**\# for installing the requirements.txt**

**pip install -r requirements.txt**

**(or)**

**\# for hiding the logs**

**pip3 install -qqq -r requirements.txt**

**\# Create a .env file in the same folder as of app.py**

**\# The .env file should contain all the API TOKENS as mentioned below:
      LANGCHAIN_API_KEY=''
      GROQ_API_KEY=''
      OPENAI_API_KEY=''**

**\# Run the Streamlit Application:**

**\#Change your current working directory to the folders directory**

**And then run using:**

**Streamlit run app.py**

**You’ll observe a template(below) on your default browser:**

**![](1569bb2083d071295faa21de979dd6ad.png)**

<img width="1708" alt="Screenshot 2024-09-13 at 3 14 16 PM" src="https://github.com/user-attachments/assets/60be0ed6-51c8-4768-8b4a-3344e1a90c01">

**Enter your OpenAI API KEY and Select the respective Chat models.**

**Also Select the temperature and max_tokens parameters for the model.**

**You can play with the application by giving a prompt like below.**

**![](29cbed00733da941d55160a2b8b190b8.png)**

<img width="1710" alt="Screenshot 2024-09-13 at 3 18 25 PM" src="https://github.com/user-attachments/assets/0b0b7f95-29ee-4ffa-9223-fd4b2b97012a">

