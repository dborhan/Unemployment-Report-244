# Unemployment-Report-244


## Setup

Create and activate a virtual environment:

```sh 
conda create -n Unemployment-env python=3.8

conda activate Unemployment-env
```

Install pacakge dependencies:
```sh
pip install -r Requirements.txt


## Usage

Run an example script:

```sh
python app/my_script.py
```

Run the unemployment report:

```sh
python app/Unemployment.py

# or pass env var from command line:
ALPHAVANTAGE_API_KEY="____" python app/Unemployment.py
```

