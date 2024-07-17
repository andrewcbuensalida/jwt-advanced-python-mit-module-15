To get started

## Create a virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment (mac/linux):

```bash
source .venv/bin/activate
```

For Windows
```bash
.venv\Scripts\activate.bat
```

In the future, to deactivate venv
```bash
.venv\Scripts\deactivate.bat 
```

## Install dependencies. This is not needed if doing a pip install in the notebook
pip install -r requirements.txt

## To save dependencies into requirements.txt
pip freeze > requirements.txt



## To run a fask app
flask --app app --debug run
--debug is for live reload