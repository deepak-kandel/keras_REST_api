This guide shows you to:

- build a REST API that predicts prices based on the model (using Flask and gunicorn)


# Quick start

Requirements:

- Python 3.7



Clone repo and Install libraries:

```bash
git clone git@github.com:deepak-kandel/keras_REST_api.git
cd keras_REST_api
virtualenv --no-site-packages venv
source venv/Scripts/activate
pip install -r requirements.txt
```

## Start local server

```bash
flask run
```

## Make predictions
```bash
python test_api.py
```
