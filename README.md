This project builds a chatbot system that mimics a human-like assistant deployed on a website (e.g., LinkedIn-based assistant) and evaluates its conversational responses using Google Gemini as an evaluator model.

# 🤖 Conversational Website Bot with LLM and Gemini Integration

This project simulates a website-deployed chatbot assistant (e.g., on LinkedIn) and uses Google Gemini to evaluate the responses of the chatbot powered by OpenAI. It combines chatbot response generation and automated evaluation into one streamlined notebook interface.

---

## 🧩 Project Workflow

1. **User Message Simulation**  
   Prompts are like:  
   - "Who are you?"  
   - "What is your email so that I can connect with you?"

2. **Chatbot Reply Generation**  
   System prompt:  
   > *You are a chatbot deployed on {name}'s website...*

3. **Evaluation via Gemini**  
   - Initializes Gemini API.
   - Sends the entire conversation (user prompt, bot reply, and history) to Gemini.
   - Gemini acts as an evaluator and returns feedback or rating.

---

## 🔧 Technologies Used

- **Python**
- **[OpenAI API](https://platform.openai.com/docs)** - for chatbot responses
- **[Google Gemini API](https://ai.google.dev/)** - for response evaluation
- **[Gradio](https://gradio.app/)** - for building UI interfaces
- **[PyPDF2](https://pypi.org/project/PyPDF2/)** - for PDF extraction (optional)
- **dotenv** - for managing API keys

---

## 📁 File Structure
![image](https://github.com/user-attachments/assets/b735999e-ee94-4d60-b175-d9348ebe475c)


## 🚀 How to Run
- Open main.ipynb in Jupyter Notebook.

- Ensure your .env file contains valid API keys.

- Execute the cells sequentially.

- Optionally, extend with Gradio for UI-based interaction.


## Screenshots:

![image](https://github.com/user-attachments/assets/fcfd768e-6a30-4fdf-9014-be462310db7f)



