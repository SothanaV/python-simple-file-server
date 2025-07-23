# python-simple-file-server
- run
```
docker compose up
```

- upload 
```
curl -F "file=@test.txt" http://localhost:5050/upload/
```

- download
```
curl http://localhost:5050/upload/test.txt -o test.txt
```