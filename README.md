# Простой URL сократитель

<img width="1339" height="689" alt="image" src="https://github.com/user-attachments/assets/701bbebd-8e54-4c8b-9fd2-64ed0aaab258" />


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
