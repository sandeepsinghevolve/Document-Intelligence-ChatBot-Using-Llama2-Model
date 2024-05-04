# Document-Intelligence-ChatBot-Using-Llama2-Model
With the help of ChatBot, we can get any information on the Document.
I have used the Llama2 llm model, Langchain Framework, Huggingface Hub, Pinecone Vector Database, Prompt Engineering, and Flask API.
Model Description : model_name_or_path = "TheBloke/Llama-2-7B-Chat-GGML"
                    model_basename = "llama-2-7b-chat.ggmlv3.q4_0.bin" # the model is in bin format.
Required Libraries: 
ctransformers==0.2.5
sentence-transformers==2.2.2
pinecone-client
langchain==0.0.225
flask
pypdf
python-dotenv
huggingface_hub
numpy==1.23.
langchain_community
LlamaCpp

To Run this project First set "PINECONE_API_KEY" & "PINECONE_API_ENV" in the .env file and then open the VS code terminal and run "python app.py".
You will get one link like http://127.0.0.1:8080/ and there you can get any information on your uploaded documents in the data folder through the chatbot.
