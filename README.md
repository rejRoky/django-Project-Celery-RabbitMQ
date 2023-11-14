### djangoCeleryRabbitMQ

## Installation

### RabbitMQ
```bash
sudo apt-get install rabbitmq-server
```

### Celery
```bash
pip install celery
```

### Django
```bash
pip install django
```

## Usage

### RabbitMQ
```bash
sudo rabbitmq-server
```

### Celery
```bash
celery -A djangoCeleryRabbitMQ worker -l info
```

### Django
```bash
python manage.py runserver
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
```

## Output
```bash
$ python3 main.py
README.md
```
