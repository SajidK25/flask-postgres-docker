## Run the docker containers

```
git clone https://github.com/SajidK25/flask-postgres-docker.git
cd flask-postgres-docker/
docker-compose up -d
```

## Test the api

``` POST http://localhost:5001/accounts/```

```json
# body data
{
	"name": "sajid"
}

```
Respone CODE: `200 OK`
Message: `successfully created!`
