# Automatic Honeygain pot draws

### Requirements

1. Linux with Docker

### Setup

#### 1. Get JWT token

1. Login to [honeygain dashboard](https://dashboard.honeygain.com/) on web.
2. Right click and open Inspect Element / Inspect.
3. Got to "Local storage" section and find the "JWT Token".
4. Paste the token into the auth.txt file from this repository.

#### 2. Run App

1. Run this command `docker build -t hg-bot:latest . `
2. Start the docker container and run everytime on boot `docker run -dti --name hg-bot --restart=always hg-bot:latest`

# Congratulations!
