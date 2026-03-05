#clone this repository by running this command
- git clone https://github.com/Piyushkohlii/Medical-Chatbot-LLMs-LangChain-Pinecone-Flask-AWS.git

#project setup
- installing python 3.10 for the requirements.txt
- creating virtual environment variable (venv) with the python version 3.10
- activating it
- then pip install -r requirements.text

#generate api key of pinecone and chatgroq
- setup account in pinecone and chatgroq and create api key
- add both in the env file

#run the following command to store embeddings in pinecone
- python store_index.py

#run this command to run and start the whole project
- python app.py

#then search localhost:"your_port_number"