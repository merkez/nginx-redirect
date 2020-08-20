

Redirect provided URL (-where you have a domain with A record-) to another URL. 

**Build Image** 

`$ docker build -t nginx-redirect .`

**Run Image**

`$ docker run -v $(pwd)/certs:/certs -p 8081:443 nginx-redirect`