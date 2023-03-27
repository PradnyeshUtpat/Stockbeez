# News Application using Flask

To create a news application, we use [News Api](https://newsapi.org/).
Signup for a free account and get an API Key from News API. Once you get the API Key, create a `.env` file at the top-level directory and store your API Key there as:
```sh
NEWS_API_KEY=YOUR-API-KEY-HERE
```

 Activate venv
```sh
$ source venv/bin/activate
```

Install dependencies
```sh
$ pip install -r requirements.txt
```

Run Server (http://localhost:5000)
```sh
$ python main.py
```

Endpoint
```sh
http://127.0.0.1:5000/news
```
