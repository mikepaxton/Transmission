# Transmission in Docker for CyberDeck Project

## Prerequisites
- Docker installed on your Raspberry Pi
- Docker Compose installed on your Raspberry Pi

## Sources:
 - https://github.com/jketterl/transmission.git

## Instructions
### Step 1: Clone the Repository
```
git clone https://github.com/mikepaxton/transmission.git
cd transmission
```

### Step 2: Edit docker-compose.yml
- Change the port if needed.  In this example 8170 is the opened hosts port and 9091 is the contianers port number.
- Change PUID and GUID to reflect the ID of admin
- Change TZ to reflect your timezone.

### Step 3: Edit .env file
- Change both the user and password for your admin account

### Step 4: Run docker compose and verify container runs with no errors
`docker compose up`

### Step 4: If no errors, stop the container
`Ctrl + c`

## Additional Information

