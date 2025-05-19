Be very careful you don't have two inspectors in the web browser open at
```http://127.0.0.1:6274/#resources```
Otherwise you'll get connect disconnect loop


Activate python virtual environment
```.venv\Scripts\activate```


to run with local mcp inspector mode, which works against the server
```uv run mcp dev app.py ```

Install the server in claude desktop to itneract with it
```uv run mcp install app.py```


