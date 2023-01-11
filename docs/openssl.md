### server 
openssl genrsa -out server.key 2048
openssl req -new -x509 -key server.key -out server.pem -days 3650

### client 
openssl genrsa -out client.key 2048
openssl req -new -x509 -key client.key -out client.pem -days 3650
