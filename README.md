# AddonTranslator
Translates a given list of strings into the languages supported by WoW and saves the output into a file.

# Requirements
* Python 3
* venv Python module: pip install venv

# Installation as submodule
1) Clone your other repo: git clone <repo_url>
2) Run: git submodule init
3) Run: git submodule update
4) Continue to normal installation
OR
1) Clone your repo with the --recurse-submodules flag: git clone --recurse-submodules <repo_url>
2) Continue to normal installation

# Installation
1) Move to the AddonTranslator repo's directory
2) Start the venv: venv\Scripts\activate
3) Install the other Python modules: pip install -r requirements.txt
4) (Optional) Deactivate the venv once your done: venv\Scripts\deactivate.bat

# Using the program
1) Start the venv if it isn't already started: venv\Scripts\activate
2) Create a file of every string you want to translate with a newline between each string (Currently no support for newlines in strings)
3) Call the program: python AddonTranslator.py <path to sstring file>

    example) python AddonTranslator.py hello.tx
4) Place the generated localization.lua file where ever you want
5) (Optional) Deactivate the venv once your done: venv\Scripts\deactivate.bat
