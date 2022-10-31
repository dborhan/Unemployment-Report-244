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

##Configuration

[Obtain an API Key] (https://www.alphavantage.co/support/#support) from AlphaVantage. 

Then create a local ".env" file and provide the key like this: 

```sh
# this is the ".env" file...

ALPHAVANTAGE_API_KEY="______"
```

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

