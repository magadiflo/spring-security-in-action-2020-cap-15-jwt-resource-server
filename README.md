# Servidor de autorización usando JWT

## Para el capítulo 15, sección "Implementando un servidor de recursos que usa JWT"

## Ejemplo del uso de este servidor

````bash
curl -v -H "Authorization: bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2ODY4MDU3NjgsInVzZXJfbmFtZSI6ImFkbWluIiwiYXV0aG9yaXRpZXMiOlsicmVhZCJdLCJqdGkiOiI4YjdkYjJiYy03NTZlLTRjNjYtYTIwNi1jY2UwZWYyOTEyYjciLCJjbGllbnRfaWQiOiJjbGllbnQiLCJzY29wZSI6WyJyZWFkIl19.mOhgpAlS_9SxG7ofbq556M-2PXRvBYSEnXlIAcKtN-U" http://localhost:9090/hello

--- Response ---
< HTTP/1.1 200
<
Hello!
````
