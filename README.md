## Sentiment Analysis API

A simple sentiment analysis example.

### Usage

- Build

```
pip install -r requirements.txt 
```

- Run

```
python server.py
```

- Use

```
curl http://10.24.105.141:3000/sentiment -X POST -d '{"text":"The food was wonderful, not too spicy and not too mild; just perfect! I will come back for sure!"}' -H "Content-Type: application/json"
```