# My first repository

## These are the git commands I already learned

- git clone
- git branch
- git checkout
- git commit
- git add
- git push
- git pull


## How to create python environment
- command: `python3 -m venv .venv` or `python -m venv .venv`

## How to activate python environment
### Windows
- powershell command: `.venv\Scripts\Activate.ps1`
- cmd command: `.venv\Scripts\activate.bat`

#### Windows Troubleshooting
- In case python environment can not be activated, use command in terminal: `Set-ExecutionPolicy Unrestricted -Scope Process`

### Linux / Mac
- command: `source .venv/bin/activate`

## execute python scripts
command: `python <scriptname>.py`, example: `python myfile.py`

## add dependencies
- command: `pip install pandas`

## save dependencies to file
- command: `pip freeze > requirements.txt`

## install dependencies from file
- command: `pip install -r requirements.txt`