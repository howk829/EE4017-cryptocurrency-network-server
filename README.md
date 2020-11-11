# EE4017-cryptocurrency-network-server

Cryptocurrency network server side

# Usage
```
python3 server.py 5000
python3 server.py 5001
python3 server.py 5002
```

```
curl -d "node=127.0.0.1:5000" -X POST http://0.0.0.0:5001/register_node
curl -d "node=127.0.0.1:5001" -X POST http://0.0.0.0:5002/register_node
```
