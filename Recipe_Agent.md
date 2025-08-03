# Recipe_Agent
# 🍲 Recipe Preparation Agent – AI-Powered Cooking Assistant

This AI-powered assistant helps users prepare South Indian dishes based on the ingredients they have. Built using IBM Watsonx and RAG (Retrieval-Augmented Generation) architecture, the agent delivers recipe suggestions, preparation steps, nutrient info, and substitute ingredients through a smart conversational interface.

---

## 🚀 Live Demo

> 👇 Try it here (IBM Cloud Deployment):
[🔗 Live Demo Link (replace with your Watsonx link)](https://your-ibm-cloud-link)

---

## 🧠 About the Project

**Objective:**  
To reduce food waste and save time by suggesting recipes based on available ingredients using AI.

**Key Capabilities:**
- Accepts user input (ingredients) via chat
- Performs semantic search across a recipe dataset
- Uses IBM Granite model for generating natural responses
- Returns complete recipe steps with nutrient info and suggestions

---

## 🔧 Tech Stack

| Component       | Technology Used                   |
|----------------|------------------------------------|
| LLM Model       | IBM Granite Foundation Model       |
| Prompt Testing  | IBM Watsonx AI Studio              |
| Deployment      | IBM Watsonx AI Runtime             |
| Chat Interface  | IBM Watsonx Assistant (Agent Lab)  |
| Data Storage    | IBM Cloud Vector Store             |
| Backend Logic   | Python (Flask if used)             |

---

## 📁 Dataset

- 40 curated South Indian recipes:
  - 🍛 10 Breakfast
  - 🍲 10 Lunch
  - 🍟 10 Snacks
  - 🌙 10 Dinner  
- Each entry includes:
  - Ingredients  
  - Preparation steps  
  - Nutritional information

---

## 💻 Local Setup (Optional)

```bash
git clone https://github.com/YOUR_USERNAME/recipe-preparation-agent.git
cd recipe-preparation-agent
pip install -r requirements.txt
python app.py
