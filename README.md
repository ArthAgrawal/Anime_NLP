# Anime_NLP
A short series of NLP related tasks on Anime Data 

The first task was to create a simple content classifier. I used a decision tree model and achieved a 92% accuracy. The code and results are shown in the code uploaded.


The second task was to Perform a basic sentiment analysis on user comments for “The Difference Between Manga And Manhwa”. I used TextBlob library and used it to categorize comments into positive, negative and neutral and printed the percentage of each.


The last task was to make a chatbot: Firstly I made a simple chatbot using NLTK.


The second chatbot I made was an LLM. This is an interesting model as it uses langchain and groq. The model inputs any PDF and can make a chatbot to chat with that PDF. Hence, I copied all the content from the site given in the assignment(https://animemangatoon.com/castle-swimmer-unveiling-new-prophecy/) and made it a PDF.


This PDF was given to the model and a chatbot was made out of it. the only necessity for this chatbot to run are the libraries used in the code(for which I have provided a requirements.txt) and a Groq API Key which is free of cost.


Here are the results of the ChatBot when asked some questions
<img width="1697" alt="Screenshot 2024-10-10 at 8 03 51 PM" src="https://github.com/user-attachments/assets/16cff54d-21af-47c5-accb-3018106183ff">
<img width="1691" alt="Screenshot 2024-10-10 at 8 04 11 PM" src="https://github.com/user-attachments/assets/82c2c983-2b0e-4487-b937-eb7507b41309">
<img width="1642" alt="Screenshot 2024-10-10 at 8 04 19 PM" src="https://github.com/user-attachments/assets/3311491f-f2f3-4246-a95d-20e07a438c36">
<img width="1689" alt="Screenshot 2024-10-10 at 8 04 35 PM" src="https://github.com/user-attachments/assets/63468bb9-48ea-4b10-bf37-f3a0e0cab517">
<img width="1677" alt="Screenshot 2024-10-10 at 8 04 44 PM" src="https://github.com/user-attachments/assets/a173ef1f-ead0-4042-befe-402116737978">
