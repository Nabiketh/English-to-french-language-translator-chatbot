# 🌍 English to French Translator

An AI-powered language translation application that translates English text into French using the Hugging Face Transformers library and the **Helsinki-NLP/opus-mt-en-fr** pretrained neural machine translation model. The project demonstrates how pretrained Large Language Models (LLMs) can be integrated into Python applications for accurate and efficient language translation.

---

# 📖 Project Overview

The **English to French Translator** is a command-line application that accepts English text from the user and generates its French translation in real time. To enhance the user experience, the translated response is displayed with a word-by-word typing animation, creating a conversational feel.

This project was developed using **Python**, **Google Colab**, and the **Hugging Face Transformers** library.

---

# ✨ Features

* 🌐 English to French translation
* 🤖 Powered by a pretrained Hugging Face translation model
* ⚡ Fast and accurate neural machine translation
* 💬 Interactive command-line interface
* ⌨️ Word-by-word typing animation
* 🔄 Continuous translation until the user exits

---

# 🛠️ Tech Stack

* Python
* Google Colab
* Hugging Face Transformers
* Helsinki-NLP/opus-mt-en-fr Model

---

# 📂 Project Structure

```text
Case Project 2/
│
├── English_to_French_Translator.ipynb
├── Case_project 2.docx
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone the Repository

```bash
git clone <repository-url>

cd Case-Project-2
```

## 2. Install Dependencies

```bash
pip install transformers
```

---

# ▶️ Run the Project

Open the notebook:

```text
English_to_French_Translator.ipynb
```

Run all cells and start translating English sentences into French.

---

# 💬 Example

### Input

```text
Hello, how are you today?
```

### Output

```text
Bonjour, comment allez-vous aujourd'hui ?
```

---

# ⚙️ How It Works

1. Loads the pretrained **Helsinki-NLP/opus-mt-en-fr** translation model.
2. Accepts English text from the user.
3. Processes the input using the Hugging Face translation pipeline.
4. Generates the French translation.
5. Displays the translated text with a typing animation.
6. Continues accepting new inputs until the user chooses to quit.

---

# 🎯 Learning Outcomes

Through this project, I learned:

* Using pretrained NLP models with Hugging Face Transformers
* Implementing neural machine translation
* Building interactive command-line applications
* Integrating AI models into Python projects
* Creating user-friendly console applications with streaming output

---

# 🚧 Challenges Faced

* Installing and configuring the Transformers library
* Selecting an appropriate translation model
* Managing model loading time
* Implementing a smooth typing animation for translated responses

---

# 🔮 Future Improvements

* Support for multiple languages
* Voice input and speech translation
* Web interface using Streamlit or Flask
* Translation history
* Automatic language detection
* Text-to-speech for translated output

---

# 👨‍💻 Author

**Nabiketh Thalari**

---

# 📄 License

This project is intended for educational and learning purposes.
