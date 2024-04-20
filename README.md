# PDFChat

This is a modified version of [ChatPDF](https://www.thesamur.ai/chatpdf-alternative) to suit paper summaries for counting cow bites.

### Getting Started

### How to run

1. Clone the repo:
   ```
   git clone https://github.com/prototaip-134/pdf-summarizer.git
   ```
2. Set up a virtual environment in python using `venv` or `conda`. The following are steps to set up `conda`.
   
#### Install MiniConda
The following instructions are for Linux. For other operating systems, download and install from here.
```
curl -sL \
  "https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh" > \
 "Miniconda3.sh"
```
Install the .sh file.
```
bash Miniconda3.sh
```
Remove the installer:
```
rm Miniconda3.sh
```
#### Creating a virtual environment
Run the following commands to create a virtual environment and to activate it:
```
conda create -n pdfchat python=3.8 -y
conda activate pdfchat
```
Make sure to run `conda activate pdfchat` before running any of the scripts in this repo.

3. Run from the root of the repository assuming that you have already cloned the repo:
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
