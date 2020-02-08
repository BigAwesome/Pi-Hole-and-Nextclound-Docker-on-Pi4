# PiHole and Nextclound on Pi4 using Docker

WRNING! This project does NOT USE HTTPS! ONLY INTENDED FOR USSAGE IN CLOSED NETWORKS OR TESTING.

If you need to install docker: https://dev.to/rohansawant/installing-docker-and-docker-compose-on-the-raspberry-pi-in-5-simple-steps-3mgl

1. Create the folders "/srv/nextcloud/db", "/srv/nextcloud/forntend" and "/srv/pihole/"
2. Set "POSTGRES_PASSWORD=[PASSWORD]" in the db.env file to a save password
3. Copy "docker-compose.yml" and "db.env" to the "/srv" folder on your Pi
4. sudo docker-compose up -d
Done!

WRNING! This project does NOT USE HTTPS! ONLY INTENDED FOR USSAGE IN CLOSED NETWORKS OR TESTING.
