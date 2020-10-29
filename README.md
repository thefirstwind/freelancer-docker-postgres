# Set a postgres container with secrets from file

I have tried to set up a Postgres container using secrets. My secrets are stored in individual text files.
My docker-compose file is attached to this project. Unfortunately, when I run docker-compose up, I am getting the following error:
ERROR: for postgres Cannot create container for service postgres: invalid volume specification: 'C:\users\rolan\Desktop\TEST\secrets\DB_USERNAME:/run/secrets/db-username:ro'

I need help to make it run, even if i need an additional script to create the variables from the secrets files. I also need a volume to be set in order to have persistent data when the container stops and restarts.

I don´t want to use swarn


##
