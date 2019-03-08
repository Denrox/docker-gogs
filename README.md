# docker-gogs
Get a private git repository with web interface by running a single command. GOGS is going used as a web client for your repo.

## How To Run
Just run command `docker-compose up -d`

## How To Check
By default this setup binds to address `gogs.localhost`.
So you can either add a snippet `127.0.0.1 gogs.localhost` to your /etc/hosts, or you can specify your own host for running gogs in `nginx/sites-enabled/gogs`
