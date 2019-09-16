ShinyProxy Docker Template
================
Docker compose with an example shiny web-app using plotly running on an nginx webserver and shinyproxy. 
The example app can be found under webapp/shiny

### Deployment

1.  Build the Shiny App Docker image:
    `docker build -t mynew/shiny-app ./webapp`
2.  Start Docker containers `docker-compose up -d`
3.  Navigate to 127.17.0.1

HTTPS encryption can be configured by adapting the nginx.conf.

more infos under:
-   https://www.shinyproxy.io
-   https://shiny.rstudio.com/
-   https://hub.docker.com/_/nginx
