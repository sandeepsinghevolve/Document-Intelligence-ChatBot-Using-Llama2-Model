# Gen AI Document-Intelligence-ChatBot-Using-Llama2-Model
With the help of ChatBot, we can get any information on the Document.
<br>
I have used the Llama2 llm model, Langchain Framework, Huggingface Hub, Pinecone Vector Database, Prompt Engineering, and Flask API.
<br>
Model Description : model_name_or_path = "TheBloke/Llama-2-7B-Chat-GGML"
<br>
                    model_basename = "llama-2-7b-chat.ggmlv3.q4_0.bin" # the model is in bin format.
<br>
Required Libraries:
<br>
ctransformers==0.2.5
<br>
sentence-transformers==2.2.2
<br>
pinecone-client
<br>
langchain==0.0.225
<br>
flask
<br>
pypdf
<br>
python-dotenv
<br>
huggingface_hub
<br>
numpy==1.23.
<br>
langchain_community
<br>
LlamaCpp
<be>
<br>
To Run this project First set "PINECONE_API_KEY" & "PINECONE_API_ENV" in the .env file and then open the VS code terminal and run "python app.py".
You will get one link like http://127.0.0.1:8080/ and there you can get any information on your uploaded documents in the data folder through the chatbot.
