# Простой URL сократитель

<img width="1000" height="197" alt="image" src="https://github.com/user-attachments/assets/32dd228f-3046-4ded-a03f-5d01b9a2a345" />


API

        $ curl -X POST http://mydomain.com/save -d '{"url": "http://google.com"}'
        {"error":"","id":"M","url":"http://mydomain.com/M"}

#### Docker:

    docker run -dv /local/data/path:/data \
    	-p 1337:1337 \
    	-e BASE_URL=http://mydomain.com \
    	-e DB_PATH=/data \
    	gegxkss/url-shortener

Или  `docker-compose`  

    docker-compose up -d
