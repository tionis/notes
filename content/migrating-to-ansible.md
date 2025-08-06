# Migrating to Ansible
In the past I mainly used a one git repo with a docker compose yaml + service config files per node. I then did most admin work manually via ssh, but this ends now.  
My new setup will use one ansible repo to manage my raspberry pi cluster, small raspberry pi zeros in my flat, the VPS and some other nodes. For my VPS I will mainly use quadlets (migrating them from the docker-compose config) with the config files also being pushed by ansible. For backups I will keep the existing restic backup scripts. In the future I might migrate all the services into a kubernetes cluster, but for that I first need to learn how to handle kubernetes using my raspi based cluster at home.
I will update this page when I finished the migration.
