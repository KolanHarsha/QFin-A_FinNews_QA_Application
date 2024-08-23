# QFin-A_FinNews_QA_Application_Powered-By-LLaMA2

https://github.com/user-attachments/assets/7bcdf605-5f87-4b8f-b9cc-9b1a1a0fcf7e

## **About The Application**
QFin is a state-of-the-art financial news Q&A application powered by LLaMA 2, designed to streamline the retrieval of information from financial news articles. By leveraging cutting-edge natural language processing and deep learning technologies, QFin enables users to input financial web links or paste URLs to receive precise and relevant answers to their queries. The application processes and analyzes news content in real-time, breaking down articles into manageable segments and embedding them with advanced language models. Offering clear and contextually accurate responses, QFin is an invaluable tool for investors, analysts, and finance professionals seeking to make informed decisions based on the latest news.

## **Softwares, Libraries & Frameworks**

<img src="https://github.com/KolanHarsha/DDos-detection-Using-Machine-Learning/assets/110462466/ec05c02a-389a-4363-8b8c-9b1ba8ca28b0" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/24c51ffd-6175-4d55-85f9-144ead36ea89" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/6dcda243-fcec-45d4-9d77-8d1107e96275" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/9dc00b20-f474-48cd-ac7e-337fa39ce1db" alt="python" width="150" height="100">
<img src="https://github.com/user-attachments/assets/1d4cecf4-23b9-4020-b069-ececad5575a5" alt="python" width="150" height="100">

## **Architecture**
![image](https://github.com/user-attachments/assets/6ae3f5ac-d7fa-4746-9016-b3291d7e45be)

## **How to Run**
1. The "llama2-inference.ipynb" file is designed to demonstrate the inference of  LLaMA-2 for question and answering.
2. The "qfin-app.ipynb" is the notebook which contains the code to run the Streamlit Application.
3. The "Faiss.pkl" is a pickle file to store the FAISS index.

### **Requirements**
```bash 
!pip install accelerate==0.33.0 transformers==4.31.0 tokenizers==0.13.3
!pip install bitsandbytes==0.40.0 einops==0.6.1
!pip install xformers==0.0.22.post7
!pip install langchain==0.1.4
!pip install faiss-gpu==1.7.1.post3
!pip install sentence_transformers
!pip install -q streamlit
!npm install localtunnel
```

Once the requirements are installed the application can be launched through jupyter notebook by executing the following:
```bash
!curl ipv4.icanhazip.com
```

When you run this command, you should see a simple output displaying the public IPv4 address of your machine, for example, "203.0.113.45".

```bash
!streamlit run QFin-App.py &>./logs.txt & npx localtunnel --port 8501

```
1. The command !streamlit run QFin-App.py &>./logs.txt & starts the Streamlit app and runs it in the background.
2. The npx localtunnel --port 8501 command creates a public URL that points to your local Streamlit app running on port 8501.
3. After successfully entering your IPv4 address, the Streamlit app should be accessible in your browser.

## **Contributors**
- Sai Harsha Vardhan Reddy, Kolan- skolan@horizon.csueastbay.edu, harsha62334@gmail.com

Thanks for reading!
