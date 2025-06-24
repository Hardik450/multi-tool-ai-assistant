

```markdown
# 🧠 Voice-Activated AI Assistant using LangChain & Gemini

This project is a **voice-driven AI assistant** built using [LangChain](https://www.langchain.com/), [Gemini (Google Generative AI)](https://ai.google.dev), and Python tools such as **speech recognition**, **text-to-speech**, and **Python REPL execution**. You can **speak your query**, and the agent will **understand, respond, and even speak back**.


## 🔥 Features

- 🎤 **Speech-to-Text**: Converts your voice into text using Google Speech Recognition.
- 🤖 **LLM Agent**: Uses Gemini 2.0 Flash model via LangChain for generating intelligent responses.
- 🧪 **Python Code Execution**: Runs Python code dynamically using a REPL tool.
- 🗣️ **Text-to-Speech**: Speaks the assistant's response using `pyttsx3`.
- 📅 **Custom Tools**: Includes a custom `get_time` tool to fetch the current date.
- 🛠️ **Extensible**: Easily add more tools like web search, calculator, etc.


## 📸 Demo

User: "Write a Python program to sort a list."
Assistant: *Writes code*, executes it, and reads out the sorted list.
User: "Exit the chat"
Assistant: Endes the chat



## ⚙️ Tech Stack

| Tool / Library         | Purpose                               |
| ---------------------- | ------------------------------------- |
| `LangChain`            | Agent framework + tool integration    |
| `Google Generative AI` | LLM used via `langchain-google-genai` |
| `SpeechRecognition`    | Convert microphone input to text      |
| `pyttsx3`              | Text-to-speech voice response         |
| `PythonREPL`           | Execute Python code dynamically       |
| `dotenv`               | Load environment variables            |



## 📌 Future Improvements

* 🌐 Add Web Search using Google Serper or DuckDuckGo.
* 🧠 Add memory to maintain multi-turn conversations.
* 🧾 Log all interactions to a file.
* 🎛 GUI version using Tkinter or PyQt.



## 🤝 Contributions

PRs are welcome! If you have any ideas or fixes, feel free to open a pull request.



## 📄 License

This project is open-sourced under the [MIT License](LICENSE).



## 🙌 Acknowledgements

* [LangChain Docs](https://docs.langchain.com/)
* [Gemini AI](https://ai.google.dev/)
* [SpeechRecognition Library](https://pypi.org/project/SpeechRecognition/)
* [pyttsx3](https://pypi.org/project/pyttsx3/)

