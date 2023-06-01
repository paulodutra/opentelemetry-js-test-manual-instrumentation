# OpenTelemetry Project

This project is a clone of the repository: https://github.com/kubowania/opentelemetry-movies-microservices

The project uses opentelemetry-js in version 0.16.0 and following the instructions on this link: https://github.com/open-telemetry/opentelemetry-js/tree/v0.16.0/getting-started

1. to start this app run to start a zipkin container

```
docker run -d -p 9411:9411 openzipkin/zipkin --name zipkin
```

2. to install the packages

```
npm i

```

3. to starting all services:

```
npm start
```

4. then visit http://localhost:3000/movies and localhost:3001/dashboard  

Now view the tracing data in zipkin : http://localhost:9411/zipkin/
