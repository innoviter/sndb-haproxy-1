## Simple HAProxy with two nginx in local Docker environment

This HAProxy setup and config routes website (nginx 1) and app (nginx 2) to the same URL.

### Start

Start with `docker-compose up -d && docker-compose logs -f`.

### Test

Test website with `curl -v http://172.23.9.2`.

Test app with `curl -v http://172.23.9.2/app/`.

### Stop

Stop with `docker-compose down`.
