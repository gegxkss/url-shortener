# Простой URL сократитель

<img width="1090" height="569" alt="image" src="https://github.com/user-attachments/assets/b79f6107-4041-483d-ab1b-f0f912f8754c" />

API

        $ curl -X POST http://mydomain.com/save -d '{"url": "http://google.com"}'
        {"error":"","id":"M","url":"http://mydomain.com/M"}

#### Docker:

    docker run -dv /local/data/path:/data \
    	-p 1337:1337 \
    	-e BASE_URL=http://mydomain.com \
    	-e DB_PATH=/data \
    	jhaals/url-shortener

Или `docker-compose`  

    docker-compose up -d
