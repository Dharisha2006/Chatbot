# 🗨️ Rule-Based Chatbot using NLTK

This is a simple **rule-based chatbot** built with **Python** and the **Natural Language Toolkit (NLTK)**. It uses regular expressions to match input patterns and respond accordingly.

## ✨ Features

- Responds to greetings and farewells
- Recognizes user name
- Tells a simple joke
- Gives instructions for making Maggi
- Basic fallback for unknown inputs

## 📦 Requirements

- Python 3.x
- NLTK

## 🔧 Installation

1. **Clone the repository** or copy the script.
2. **Install dependencies** using pip:

   ```bash
   pip install nltk
   ```

3. **Download necessary NLTK resources**:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('averaged_perceptron_tagger')
   ```

## ▶️ How to Run

Run the chatbot script in your terminal or IDE:

```bash
python chatbot.py
```

Sample interaction:

```
Hello, I am your chatbot! Type 'exit' to end the conversation.
You: hi
Chatbot: Hello! How can I help you today?

You: tell me a joke
Chatbot: Why don't skeletons fight each other? They don't have the guts!

You: how to make a maggie?
Chatbot: 1.Boil water 2.Add Noodles 3.Add Tastemaker 4.Cook

You: exit
Chatbot: Goodbye! Have a nice day!
```

## 🗂️ File Structure

```
📁 chatbot_project/
├── chatbot.py      # Main Python script with chatbot logic
└── README.md       # Project documentation
```

## 💡 Notes

- This is a **rule-based chatbot**, so its ability to understand language is limited to predefined patterns.
- Good for learning **pattern matching**, **chatbot structure**, and **basic NLP** concepts.

---

Made with ❤️ using Python & NLTK.
