# automatedSQL

This is an attempt to leverage existing LLMs to generate SQL queries with prompts. Reference can be found here.
https://huggingface.co/mrm8488/t5-base-finetuned-wikiSQL?text=translate+English+to+SQL%3A+How+many+models+were+finetuned+using+BERT+as+base+model%3F

# Setting up.

## A. Cloning
1. Clone this into `GitHub Desktop`
2. After cloning, open using `VisualStudio Code`

## B. Preparing the workspace(`WorkSpaceSetup`).
1. Prepare a working environment. `Terminal > New Terminal`
2. Switch to `Command Prompt`
3. Let us create a workspace called `.wiki`. Type `py -3 -m venv .wiki`
4. Activate the enviroment using `.wiki\scripts\activate`
5. (optional) To install django, first upgrading pip`python -m pip install --upgrade pip`
6. If you have a set of all packages in a file called `requirements.txt` then install then all in one go using this `python -m pip install -r requirements.txt` 
