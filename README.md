# Test 
Build it
```bash
docker build -t node-hello:latest
```

Run it
```bash
docker run -d -p 80:8080 node-hello:latest
```

Test it 
```bash
curl http://127.0.0.1
```

Kill it
```bash
docker stop <containerID>
```
