ShinyProxy Docker Template
================
Docker compose with an example Shiny-app running on an nginx webserver. 
The example Shiny app with plotly can be found under webapp/shiny

### Docker App Deployment

1.  Build the Shiny App Docker image:
    `docker build -t mynew/shiny-app ./webapp`
2.  Start Docker containers `docker-compose up -d`
3.  Navigate to 127.17.0.1

HTTPS encryption can be configured by adapting the nginx.conf.