The entry point for your Kafka implementation is in `app/main.py`.

Study and uncomment the relevant code: 

```python
# Uncomment this to pass the first stage

server_socket = socket.create_server(("localhost", 6379), reuse_port=True)
server_socket.accept() # wait for client
```

Push your changes to pass the first stage:

```
git add .
git commit -m "pass 1st stage" # any msg
git push origin master
```
