# HISTOGRAPHER BOOTSTRAPPER #

## How to install and run

- Fill the init.sh file
- Run the init.sh script
- Run docker-compose up -d (-d is optional)


## Folder structure
Each folder in this repo represents a service, with all its config plus a dockerfile inside.

## Local development
For local development use:


And don't forget to add the following to your `/etc/hosts` file:
```
127.0.0.1   localhost-core
127.0.0.1   localhost-ims
127.0.0.1   localhost-ims2
127.0.0.1   localhost-upload
127.0.0.1   localhost-pat-or-nat-frontend
```

## Misc

View the logs of a specific service by running docker-compose logs -f <service>



