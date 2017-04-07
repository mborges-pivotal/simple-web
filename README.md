# basic pipeline for static web apps

fly -t ci set-pipeline -p simple-web -c pipeline.yml -v "cf-password=YOUR_PASSWORD" -l properties.yml
