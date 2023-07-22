## Simple HAProxy with two nginx in local Docker environment

Start with `docker-compose up -d && docker-compose logs -f`.

Test website on nginx 1 with `curl -v http://172.23.9.2` or same URL in browser.

Test app on nginx 2 `curl -v http://172.23.9.2/app/` or same URL in browser.

Stop with `docker-compose down`.
