# r-shinny-demo

Download [Docker](https://www.docker.com/products/docker-desktop)
```
* cd C:\
* git clone https://github.com/paulius-kazokas/r-shinny-demo.git
* cd r-shinny-demo
* docker build . -t i-r-shinny
* docker run --detach --publish 80:80 --name c-r-shinny i-r-shinny
```
- create container
<img src="https://drive.google.com/uc?export=view&id=1mFWgyXlPTqvHcCCQEBLkMcxFzepCH4kS">

- reach application via localhost:8080
<img src="https://drive.google.com/uc?export=view&id=1-7DzSKUstaH6ds4b-iuPT9vLFlvTFoz8">

```
* docker tag i-r-shinny dockerID/i-r-shinny-demo
* docker push dockerID/i-r-shinny-demo
```
