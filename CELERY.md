# Personal notes on Celery

Celery has been chosen as the _task manager_ I didn't know I needed.

Redis is selected as _message broker_ for simplicity, compared to RabbitMQ. It is necessary to install:

- Redis on the computer, with `brew install redis` ([on macOS](https://redis.io/docs/install/install-stack/mac-os/)) or `sudo apt install redis-server` ([on Ubuntu](https://redis.io/docs/install/install-stack/linux/))
- Celery with the Redis bundle, with `pip install "celery[redis]"` 

Redis must be running for 