```
curl http://localhost:3000
curl http://localhost:3000/quotes
curl https://localhost:3000/quotes?page=2
curl -i -X POST -H 'Accept: application/json' \
    -H 'Content-type: application/json' http://localhost:3000/quotes \
    --data '{"quote":"Before software can be reusable it first has to be usable.","author":"Ralph Johnson"}'
```
