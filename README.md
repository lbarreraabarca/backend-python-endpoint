# Backend python endpoint

This microservice was development in Python 3.8. Also, we used Flask framework.

## How to use?

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r src/requirements.txt
cd src
python App.py
```

- If you want to submit a request then you need to use the following command.

```
curl --location --request GET 'localhost:8080/api/v1/index'
```