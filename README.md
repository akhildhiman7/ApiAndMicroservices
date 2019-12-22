# ApiAndMicroservices freeCodeCamp
This repo contains the source code for APIs and Microservices project 

The API endpoint is GET [project_url]/api/timestamp/:date_string?

A date string is valid if can be successfully parsed by new Date(date_string).

Example Usage:

[project url]/api/timestamp/2015-12-25

[project url]/api/timestamp/1450137600

Example Output: 
{"unix":1451001600000, "utc":"Fri, 25 Dec 2015 00:00:00 GMT"}
