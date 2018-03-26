# project-docker-gameserver-eco
Files to run a dedicated Eco GameServer in Docker

In order to run, navigate into the folder where you have extracted the docker-compose and the Dockerfile, add a current zipped version of the EcoServer-Files, named 'EcoServer.zip' to the folder, and execute 'docker-compose up' in a shell. The container should be automatically built and started, and be reachable under 127.0.0.1:3000 soon after. The container is able to persist server settings over restarts.

Things to do:
- Add switches for all important settings in the docker-compose and dockerfile
- Add function to automatically download newer eco server files from the forum, if a valid username/password for a forum account with access to the files is provided
- Attach an X Server to show the GUI in a VNC client

