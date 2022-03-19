# docker
docker-compose configuration for my vps :)

## for pgAdmin run

`sudo chown -R 5050:5050 ./database/./.data/pgadmin`

# for traefik run

`export PRIMARY_DOMAIN=YOUR_DOMAIN`

# to generate user run
`echo $(htpasswd -nb user password)`