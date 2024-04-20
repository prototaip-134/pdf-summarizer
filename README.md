# PDFChat

This is a modified version of [ChatPDF](https://www.thesamur.ai/chatpdf-alternative) to suit paper summaries for counting cow bites.

### Getting Started

### How to run

1. Create a virtual environment in python using `venv` or `conda`.

2. Run from the root of the repository assuming that you have already cloned the repo:
   ```
   pip install -r requirements.txt
   ```

4. Then run the following to run the frontend server locally:
   ```
   streamlit run streamlitui.py
   ```
   
5. Input the OpenAI API key, change/upload pdf file and add a `.` or any character and press `ENTER` to run the summarizer.
6. *Optional:* You can then also ask questions about the paper or use it to understand the paper better.

### Citation
```
@misc{Anil-matcha2024,
    title={ChatPDF},
    author={Anil-matcha},
    howpublished = {\url{https://github.com/Anil-matcha/ChatPDF}},
    year={2024}
}
```
