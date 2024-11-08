# my-first-app-fall

## Setup

Create a virtual environment (first time only):

```sh
conda create -n reports-env-2024 python=3.10
```

Activiate the environment (whenever you come back to this project):

```sh
conda activate reports-env-2024
```

Install packages

```sh
pip install -r requirements.txt
```

[Obtain an API Key](https://www.alphavantage.co/support/#api-key) from AlphaVantage.

Create a ".env" file and add contents like the following (using your own AlphaVantage API Key):

```sh
ALPHAVANTAGE_API_KEY="..."
```

## Usage

Run the example script:

```sh
python app/my_script.py
```

Run the unemployment report:

```sh
python app/unemployment.py
```