# writer MS

## Build locally

`docker build . -t writer-ms`

## Run locally

`docker run -p 8080:8080 writer-ms`

and then visit in your browser

* http://localhost:8080/greeting

will produce default message

* http://localhost:8080/greeting?name=Meir

will produce greeting "Hello Meir" 

