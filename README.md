This docker compose configuration will start a Drone CI/CD server.  Details about Drone can be found at https://drone.io/

Getting Started
---
1. Copy example .env file into place
    ```
    cp .env.example .env
    ```
2. Create an oAuth app on gihub:

    1. Go to settings page https://github.com/settings/profile
    
    2. Click "Developer Settings"
    
    3. Click "OAuth Apps"
    
    4. Click "Register a new application"
    
    5. Enter required information
    
    6. Click "Register application"
    

3. Copy the resulting client id and client secret into your .env file


Start Drone Server
---
    docker-compose up
    

Useful Information
---
* Drone server installation instructions:
    https://docs.drone.io/installation/github/single-machine/
