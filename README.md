# PiHole-and-Nextclound-Docker-on-Pi4

If you need to install docker: https://dev.to/rohansawant/installing-docker-and-docker-compose-on-the-raspberry-pi-in-5-simple-steps-3mgl

1. Create the Folders "/srv/nextcloud/db", "/srv/nextcloud/forntend" and "/srv/pihole/"
2. Set "db.env" "POSTGRES_PASSWORD=" to a save Password
3. Copy "docker-compose.yml" and "db.env" to the "/srv" Folder on your Pi
4. sudo docker-compose up -d

WRNING! This project does NOT USE HTTPS! ONLY INTENDED FOR USSAGE IN CLOSED NETWORKS OR TESTING.

Done
