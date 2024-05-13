**Step1:** To create a project using Olama, go to https://ollama.com/ and download the Olama .exe file and install it

**Step2:** Create Virtual enviornment in VS code or any other IDE, 
Open terminal: to open vs code type cmd +shift +P

Type shell command
Type code and add to path

Open terminal : go to folder and type code .
It will open vscode from terminall

Virtual env: 
Conda create -n mlenv python=3.8 anaconda

Conda activate mlenv

**Step3:** In the Virual env , install the requirements.txt 
pip install -r requirements.txt

**Step 4:** in the termail run : olama run llama3
now the olama will download the Llama3 model in the Virtual env and ready to use.
