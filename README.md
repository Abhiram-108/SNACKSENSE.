# 🧠 SnackSense

> Your AI-powered health companion for smarter snacking 🍎🍫

**SnackSense** is an innovative web application that leverages **Large Language Models (LLMs)** to provide personalized health insights and snack suggestions. Designed to promote healthier eating habits, SnackSense analyzes user inputs to recommend snacks tailored to individual dietary preferences and goals.

🏆 **Winner of Hack SRM 6.0** — National-level hackathon organized by SRM University  
👥 Team Navacharak: Neha Erigidindla, Yasaswini Gaddam, Abhiram Pedada, Mahesh Babu Chittem  
💰 Prize: ₹60,000

---

## 🚀 Features

- 🧠 **AI-Powered Recommendations**  
  Uses LLMs to suggest snacks based on your health profile, mood, and preferences.

- 📊 **Personalized Health Insights**  
  Generates a summary of your current habits and suggests improvements.

- 🥗 **Smart Snack Choices**  
  Filters suggestions by dietary needs — vegan, keto, gluten-free, etc.

- 🗂️ **Snack Database**  
  Curated list of healthy snacks with nutritional breakdowns.

- 📈 **Progress Tracker** *(optional feature)*  
  Logs past choices and monitors improvements over time.

---

## 🛠️ Tech Stack

| Frontend       | Backend       | AI/ML           | Database        | Other         |
|----------------|----------------|------------------|------------------|---------------|
| React.js       | Node.js, Express.js | OpenAI LLM (GPT) | MongoDB          | Tailwind CSS, REST APIs |

---

## 🖥️ Screenshots

> *(Add some screenshots or a demo gif of your application here)*
[loginpage](https://github.com/user-attachments/assets/0d9e2e66-b087-473c-94bb-667f0a637365)

---

## ⚙️ Installation & Setup

### 1. Clone the repo
```bash
git clone https://github.com/Abhiram-108/snacksense.git
cd snacksense
2. Install dependencies
bash
Copy
Edit
# For frontend
cd client
npm install

# For backend
cd ../server
npm install
3. Setup environment variables
Create a .env file in the /server directory with:

ini
Copy
Edit
OPENAI_API_KEY=your_openai_key
MONGODB_URI=your_mongodb_connection_string
4. Run the application
bash
Copy
Edit
# Start backend
cd server
npm start

# Start frontend
cd ../client
npm start







