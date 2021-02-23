# Hi! My name is Rodrigo :coffee:

```python
from flask import Flask

app = Flask(__name__)


@app.route('/')
def home():
    return {
        'name': 'Rodrigo Rodrigues Scotti',
        'email': 'rrscotti@hotmail.com',
        'working': 'Canopus Tecnologia & Inovação',
        'detail': 'I love coffee',
    }

if __name__ == '__main__':
    app.run(port=5000)
```
