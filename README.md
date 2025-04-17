# AI_Powered_Web_Application
 
Step-by-Step Guide: AI-Powered Data Analysis Tool using Streamlit 
1. Project Setup 
1.1 Install Required Dependencies 
•	Python – 3.11 version – make sure you installed python 3.11 in your system and add it in your path 
•	Install pycharm or vs code  
•	Inside the pycharm or vs code create one requirements.txt file with the given libraries streamlit pandas==1.5.3 openai pandasai matplotlib seaborn speechrecognition python-dotenv openpyxl numpy==1.25.2 
pyaudio 
 
1.2 Create a .env File 
The .env file will securely store your OpenAI API key. Create this file in your project root directory and add: 
OPENAI_API_KEY=”your_openai_api_key” 
1.3 Create virtual environment and activate it  python -m venv myenv venv\Scripts\activate 
 
1.4 Installation of required library 
We have mentioned all required libraries in requirements.txt now we have to install it with the given command 
pip install -r requirements.txt 
1.5 Create  app.py  
Inside app.py write your all logic to build the project 
2. Technologies Used and Why 
1.	Streamlit - Used to create an interactive web-based UI for data analysis, making the tool accessible through a browser. 
2.	Pandas - Provides powerful data manipulation and analysis capabilities, allowing operations like filtering and aggregation. 
3.	PandasAI - An AI-powered wrapper around Pandas that integrates OpenAI to provide intelligent insights and suggestions. 
4.	OpenAI API - Used for AI-driven summarization, querying, and recommendations for handling data. 
5.	Matplotlib & Seaborn - Enable data visualization with various charting capabilities. 
6.	SpeechRecognition - Allows voice-based input for querying data, making the tool more interactive. 
7.	Python-Dotenv - Manages environment variables securely, ensuring API keys are not exposed in the code. 
8.	Openpyxl - Supports reading and writing Excel files for broader dataset compatibility. 
 
3.	How It Works 
   
1.	File Upload: Users can upload CSV or Excel datasets, which are then processed into a Pandas DataFrame (data size should be upto 200 mb only). 
  
2.	SmartDataframe Conversion: The dataset is wrapped using PandasAI to enable AI-powered queries and insights. 
  
3.	AI-Powered Summarization: OpenAI provides a concise summary of the dataset’s key aspects. 
  
4.	Handling Missing Values: AI suggests the best approach for handling missing data based on the dataset’s characteristics. 
  
Once missing values filled you can show cleaned dataset and download as well 
5.	AI Query System: Users can either type queries or use speech recognition to ask data-related questions. 
 
6.	Data Visualization: AI suggests the most relevant chart types, and users can generate and download visualizations. 
 
  
 

