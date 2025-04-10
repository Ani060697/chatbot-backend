# chatbot-backend

A smart chatbot built using Python and sentence transformers, created as part of the Hack Catalyst hackathon. This bot helps prospective students get answers to common questions related to college admissions, placement, scholarships, and welfare schemes.

features:
💬 Natural language question-answering

📁 Uses a manually curated CSV dataset

🔍 Built with sentence-transformers for semantic search

🌐 No external APIs – works offline

📊 Integrated with a dashboard for placement statistics

🛠️ Technologies Used
Python 🐍

Sentence Transformers (from Hugging Face)

Pandas

Streamlit (for dashboard, if applicable)

📂 Project Structure
chatbot-tc/
│
├── chatbot code/           # Main chatbot code
│   ├── chatbot.py          # Core chatbot logic
│   └── dataset.csv         # Manually collected Q&A dataset
│
├── dashboard/              # Optional: placement dashboard code
│   └── dashboard.py
│
└── README.md
⚙️ How to Run
Clone the repo:


git clone https://github.com/Ani060697/chatbot-tc.git
cd chatbot-tc/chatbot\ code/
Install dependencies:


pip install -r requirements.txt
Run the chatbot:


python chatbot.py
⚠️ Make sure dataset.csv is in the same folder as the chatbot script.

🧠 How it Works
The chatbot uses sentence-transformers to convert user queries and dataset entries into embeddings. It then computes the cosine similarity to find the closest match and returns the most relevant answer.


🎯 Purpose
This chatbot was developed during Hack Catalyst, our college’s hackathon, to provide a quick and interactive solution for admission-related FAQs.

📬 Feedback & Contributions
Feel free to fork, explore, or improve the project. Contributions are welcome!

![WhatsApp Image 2025-04-10 at 7 31 28 PM](https://github.com/user-attachments/assets/52c6aad2-a02d-4638-8dd7-dead5f531f08)
![WhatsApp Image 2025-04-10 at 7 31 29 PM](https://github.com/user-attachments/assets/ff84bd6b-d21b-4df7-94cb-b8d8f4699089)
![WhatsApp Image 2025-04-10 at 7 31 29 PM (1)](https://github.com/user-attachments/assets/da895a1e-02f3-4451-bafa-d692df80b802)




