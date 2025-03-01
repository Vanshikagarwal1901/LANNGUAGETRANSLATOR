# Language Translator using Python and GoogleTrans

## 📘 Project Overview
This project is a simple language translator built using Python and the `googletrans` library. It takes user input, translates it to a desired target language, and displays the translated text. The tool is easy to use and works directly in a terminal or Google Colab environment.

---

## 🚀 Features
- Translate text between 100+ languages
- Automatic language detection
- Real-time user input
- Error handling for invalid language codes

---

## 🛠️ Installation
First, you need to install the `googletrans` library:

```bash
pip install googletrans==4.0.0-rc1
```

---

## 📂 Project Structure
```
.
├── LANGUAGETRANSLATOR         # Main Python script for translation
└── README.md             # Project documentation (this file)
```

---

## 🖥️ Usage
Run the script using Python:

```bash
python translator.py
```

Or in Google Colab, just run the cells!

Example:

```
Enter the text you want to translate: Hello
Enter the target language code (e.g., 'fr' for French, 'es' for Spanish): fr

Translated Text (fr): Bonjour
```

---

## 🌍 Language Codes
Use ISO 639-1 language codes. Some examples:

- `en`: English
- `fr`: French
- `es`: Spanish
- `de`: German
- `hi`: Hindi

You can find the full list of supported languages [here](https://cloud.google.com/translate/docs/languages).

---

## 🛡️ Error Handling
If you enter an invalid language code, the script will display an error message and prompt you to try again.

Example error:
```
Error: invalid destination language
```

---

## 📚 Future Enhancements
- Support for file translation
- Text-to-speech integration
- Language auto-suggestions
-building the same from scratch without using googletrans library
---

## 🧑‍💻 Author
Created by Vanshika Agarwal

Let me know if you want me to add anything or tweak the structure! 🚀

