\# Docker Website Project 🚀



\## Overview

This project demonstrates how to containerize a static website using Docker and NGINX.



\## What I did

\- Created a Dockerfile

\- Used NGINX as a base image

\- Deployed a custom HTML page

\- Ran the container locally



\## How to run



```bash

docker build -t my-website .

docker run -d -p 8081:80 my-website

